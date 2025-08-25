<!DOCTYPE html>
<html>
<head>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Inter', sans-serif;
        }
        
        body {
            background-color: #0d1117;
            color: #c9d1d9;
            line-height: 1.6;
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }
        
        .header {
            text-align: center;
            margin-bottom: 40px;
            padding: 30px 0;
            border-bottom: 1px solid #30363d;
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            color: #f0f6fc;
            font-weight: 700;
        }
        
        h2 {
            font-size: 1.8rem;
            margin: 30px 0 15px 0;
            color: #f0f6fc;
            border-left: 4px solid #58a6ff;
            padding-left: 15px;
        }
        
        h3 {
            font-size: 1.5rem;
            color: #58a6ff;
            margin-bottom: 20px;
            font-weight: 600;
        }
        
        p {
            margin-bottom: 15px;
            font-size: 1.05rem;
        }
        
        .badges {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 8px;
            margin: 20px 0;
        }
        
        .badge {
            background-color: #21262d;
            color: #c9d1d9;
            padding: 6px 12px;
            border-radius: 20px;
            font-size: 0.85rem;
            border: 1px solid #30363d;
            display: inline-flex;
            align-items: center;
        }
        
        .badge img {
            margin-right: 6px;
            height: 16px;
        }
        
        .section {
            background-color: #161b22;
            border-radius: 10px;
            padding: 25px;
            margin-bottom: 30px;
            border: 1px solid #30363d;
        }
        
        .typing-effect {
            font-size: 1.2rem;
            margin: 20px 0;
            min-height: 60px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #8b949e;
        }
        
        .skills-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .skill-category {
            background-color: #21262d;
            padding: 20px;
            border-radius: 8px;
            border: 1px solid #30363d;
        }
        
        .skill-category h4 {
            color: #58a6ff;
            margin-bottom: 15px;
            font-size: 1.2rem;
        }
        
        .workflow {
            background-color: #21262d;
            padding: 20px;
            border-radius: 8px;
            margin: 20px 0;
            border: 1px solid #30363d;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }
        
        .social-link {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            padding: 12px 25px;
            background-color: #238636;
            color: white;
            text-decoration: none;
            border-radius: 6px;
            font-weight: 500;
            transition: background-color 0.3s;
        }
        
        .social-link:hover {
            background-color: #2ea043;
        }
        
        .social-link.linkedin {
            background-color: #0A66C2;
        }
        
        .social-link.linkedin:hover {
            background-color: #0D8BD9;
        }
        
        .social-link.email {
            background-color: #EA4335;
        }
        
        .social-link.email:hover {
            background-color: #F25C50;
        }
        
        .profile-views {
            text-align: center;
            margin: 15px 0;
            color: #8b949e;
            font-size: 0.9rem;
        }
        
        .quote {
            font-style: italic;
            text-align: center;
            margin: 30px 0;
            color: #8b949e;
            padding: 0 20px;
        }
        
        @media (max-width: 768px) {
            .skills-container {
                grid-template-columns: 1fr;
            }
            
            .social-links {
                flex-direction: column;
                align-items: center;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            h2 {
                font-size: 1.5rem;
            }
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Hi, I'm Ahmad Hassan 👋</h1>
        <h3>Software Developer & DevOps Engineer</h3>
        
        <div class="profile-views">
            <img src="https://komarev.com/ghpvc/?username=Ahmadhassan0311&label=Profile%20views&color=0e75b6&style=flat" alt="profile views"/>
        </div>
        
        <div class="typing-effect">
            <span id="typing-text">Software Developer | DevOps Engineer | CI/CD Specialist</span>
        </div>
    </div>
    
    <div class="section">
        <h2>🚀 About Me</h2>
        <p>I'm a passionate software developer and DevOps engineer with expertise in automating workflows and building efficient CI/CD pipelines. I enjoy turning complex problems into simple, beautiful solutions.</p>
        
        <ul>
            <li>🌱 Currently working on <strong>Blazor + SQL Server projects</strong></li>
            <li>💬 Ask me about <strong>Git, GitHub, CI/CD Pipelines, Docker, and Deployment Automation</strong></li>
            <li>🛠️ Skilled in <strong>C++, Java, C#, Assembly, MySQL, SQL Server</strong></li>
            <li>⚡ I automate workflows from <strong>commit → test → build → deploy</strong></li>
        </ul>
    </div>
    
    <div class="section">
        <h2>🛠️ Tech Stack</h2>
        
        <div class="skills-container">
            <div class="skill-category">
                <h4>💻 Programming</h4>
                <div class="badges">
                    <span class="badge">C++</span>
                    <span class="badge">Java</span>
                    <span class="badge">C#</span>
                    <span class="badge">Assembly</span>
                    <span class="badge">MySQL</span>
                    <span class="badge">SQL Server</span>
                </div>
            </div>
            
            <div class="skill-category">
                <h4>⚙️ DevOps & Automation</h4>
                <div class="badges">
                    <span class="badge">Git</span>
                    <span class="badge">GitHub</span>
                    <span class="badge">GitHub Actions</span>
                    <span class="badge">Jenkins</span>
                    <span class="badge">Docker</span>
                    <span class="badge">Kubernetes</span>
                    <span class="badge">Deployment Automation</span>
                </div>
            </div>
        </div>
    </div>
    
    <div class="section">
        <h2>🔁 DevOps CI/CD Workflow</h2>
        
        <div class="workflow">
            <p><strong>My typical CI/CD workflow:</strong></p>
            <ol>
                <li>Commit/Push code to repository</li>
                <li>GitHub Actions CI triggers automatically</li>
                <li>Build process and tests run in isolated containers</li>
                <li>On success: Build Docker image and push to registry</li>
                <li>Automated deployment to staging/production environment</li>
                <li>Monitoring and alerting for deployed application</li>
            </ol>
        </div>
        
        <p>This automated workflow ensures consistent, reliable deployments with minimal manual intervention.</p>
    </div>
    
    <div class="section">
        <h2>🌐 Connect with Me</h2>
        
        <div class="social-links">
            <a href="https://www.linkedin.com/in/ahmad-hassan-845097305" class="social-link linkedin">LinkedIn</a>
            <a href="mailto:ahmad6515899@gmail.com" class="social-link email">Email</a>
            <a href="https://github.com/Ahmadhassan0311" class="social-link">GitHub</a>
        </div>
    </div>
    
    <p class="quote">"First, solve the problem. Then, write the code." - John Johnson</p>
    
    <script>
        // Simple typing effect
        const texts = [
            "Software Developer",
            "DevOps Engineer", 
            "CI/CD Specialist",
            "Docker Expert",
            "Automation Enthusiast"
        ];
        
        let textIndex = 0;
        let charIndex = 0;
        let isDeleting = false;
        let typingSpeed = 100;
        
        function typeEffect() {
            const currentText = texts[textIndex];
            const typingElement = document.getElementById('typing-text');
            
            if (isDeleting) {
                typingElement.textContent = currentText.substring(0, charIndex - 1);
                charIndex--;
                typingSpeed = 50;
            } else {
                typingElement.textContent = currentText.substring(0, charIndex + 1);
                charIndex++;
                typingSpeed = 100;
            }
            
            if (!isDeleting && charIndex === currentText.length) {
                isDeleting = true;
                typingSpeed = 1000;
            } else if (isDeleting && charIndex === 0) {
                isDeleting = false;
                textIndex = (textIndex + 1) % texts.length;
                typingSpeed = 500;
            }
            
            setTimeout(typeEffect, typingSpeed);
        }
        
        // Start the typing effect
        window.onload = function() {
            setTimeout(typeEffect, 1000);
        };
    </script>
</body>
</html>
