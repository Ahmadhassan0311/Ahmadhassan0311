<!-- Profile Header -->
<h1 align="center">Hi 👋, I'm Ahmad Hassan</h1>
<h3 align="center">Software Developer & DevOps Engineer</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Ahmadhassan0311&label=Profile%20views&color=0e75b6&style=flat" alt="Ahmadhassan0311's profile views"/>
</p>

<!-- Typing Effect -->
<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=20C20E&center=true&vCenter=true&width=600&lines=Software+Developer;DevOps+Engineer;Git+%7C+GitHub+%7C+CI%2FCD;Docker+%7C+Deployment+Automation;C%2B%2B+%7C+Java+%7C+C%23+%7C+Assembly" alt="Typing SVG" />
  </a>
</p>

---

## 🚀 About Me
- 🌱 Currently working on **Blazor + SQL Server projects**
- 💬 Ask me about **Git, GitHub, CI/CD Pipelines, Docker, and Deployment Automation**
- 🛠️ Skilled in **C++, Java, C#, Assembly, MySQL, SQL Server**
- ⚡ I automate workflows from **commit → test → build → deploy**

---

## 🛠️ Tech Stack

### 💻 Programming
<p align="center">
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#"/>
  <img src="https://img.shields.io/badge/Assembly-6E4C13?style=for-the-badge" alt="Assembly"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white" alt="SQL Server"/>
</p>

### ⚙️ DevOps & Automation
<p align="center">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" alt="Jenkins"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes"/>
  <img src="https://img.shields.io/badge/Deployment%20Automation-0A66C2?style=for-the-badge" alt="Deployment Automation"/>
</p>

---

## 🔁 DevOps CI/CD Workflow

```mermaid
graph LR
A[Commit/Push Code] --> B[GitHub Actions CI]
B --> C{Run Build & Tests}
C -->|✅ Pass| D[Build Docker Image]
C -->|❌ Fail| X[Fix Code & Retry]
D --> E[Push Image to Docker Hub]
E --> F[Deploy to Staging/Prod]
F --> G[App Running 🚀]
G --> H[Monitoring & Alerts]
