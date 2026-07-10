<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,50:414868,100:7aa2f7&height=200&section=header&text=Hi%20there,%20I'm%20Priyanshi%20%F0%9F%91%8B&fontSize=42&fontColor=c0caf5&animation=fadeIn&fontAlignY=38&desc=Cloud%20%26%20DevOps%20Engineer%20in%20training&descAlignY=58&descSize=18&descColor=9ece6a" width="100%"/>

<a href="https://github.com/priyanshisaugat01">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=22&duration=3000&pause=1000&color=7AA2F7&center=true&vCenter=true&width=650&lines=Computer+Science+Student;Learning+Cloud+%26+DevOps;Building+SkyShield+%F0%9F%9B%A1%EF%B8%8F;Aviation+Infrastructure+%2B+DevSecOps+Enthusiast" alt="Typing SVG" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=priyanshisaugat01&label=Profile%20Views&color=7aa2f7&style=for-the-badge" alt="Profile Views"/>
<img src="https://img.shields.io/github/followers/priyanshisaugat01?label=Followers&style=for-the-badge&color=bb9af7&labelColor=1a1b27" alt="Followers"/>

</div>

<br/>

## 🧭 About Me

I'm a **Computer Science student** currently learning **Cloud & DevOps**, with a strong interest in **aviation infrastructure and monitoring systems**. I like understanding how large, safety-critical systems stay reliable — and I'm building my skills toward exactly that.

```yaml
name:        Priyanshi Saugat
role:        Computer Science Student
focus:       Cloud Infrastructure · DevOps · Site Reliability
currently:   Building SkyShield - DevSecOps compliance automation for aviation infra
philosophy:  Learn by building - projects, deployments, debugging, real infra
```

- 🎓 Computer Science student, learning Cloud & DevOps fundamentals in depth
- ✈️ Deeply interested in aviation infrastructure and monitoring/observability systems
- 🔭 Currently building **SkyShield**, a DevSecOps compliance automation platform combining Terraform, Checkov, Trivy, and GitHub Actions
- 🛠️ I learn by *doing* — most of my growth comes from projects, deployments, debugging, and hands-on experimentation with cloud infrastructure, not just theory
- 🌱 Actively expanding into Site Reliability Engineering and aviation-domain infrastructure design

<br/>

## 🛡️ Featured Project

<table>
<tr>
<td width="100%">

### SkyShield — DevSecOps Compliance Automation for Aviation Infrastructure

<img src="https://img.shields.io/badge/status-actively%20building-9ece6a?style=flat-square&labelColor=1a1b27" alt="status"/>
<img src="https://img.shields.io/badge/domain-aviation%20infrastructure-7aa2f7?style=flat-square&labelColor=1a1b27" alt="domain"/>
<img src="https://img.shields.io/badge/type-devsecops%20%2F%20compliance-bb9af7?style=flat-square&labelColor=1a1b27" alt="type"/>

**The problem:** Aviation infrastructure operates under strict regulatory and safety requirements, yet Terraform misconfigurations, vulnerable container images, and leaked secrets routinely slip through manual review and aren't caught until after deployment. SkyShield automates security and compliance validation of cloud infrastructure and container artifacts *before* they reach production, replacing ad-hoc manual review with continuous, auditable scanning built directly into the CI/CD pipeline.

**Technologies used:** Terraform · Checkov · Trivy · Docker · GitHub Actions *(with AWS Lambda, DynamoDB, CloudWatch, SNS, and React planned for later phases)*

<details>
<summary><b>✅ What's built so far</b></summary>
<br/>

- Terraform IaC scanning gate using Checkov, running automatically on every push and pull request
- A remediated reference S3 bucket — taken from 13 failing Checkov checks down to 5 by enforcing encryption-by-default, versioning, disabled ACLs, and full public-access blocking
- A hardened, multi-stage Docker build for a demo service — non-root runtime user, stripped build tooling, and a defined health check
- Automated container vulnerability scanning with Trivy, gating the build on `HIGH`/`CRITICAL` findings

</details>

<details>
<summary><b>🗺️ Planned next</b></summary>
<br/>

- Secret detection across source and history using GitLeaks
- Automated scan-report normalization via AWS Lambda
- Persistent compliance history in DynamoDB
- Operational metrics via CloudWatch and violation alerts via SNS
- A React-based compliance dashboard
- End-to-end CI/CD orchestration tying every phase together through GitHub Actions

</details>

**What I'm learning:** how to turn scanner output (Checkov, Trivy) into an enforced CI/CD gate rather than just a report — reasoning about IaC security patterns like least-privilege S3 configuration and encryption-by-default, and designing container images that minimize CVE surface area at the base-OS layer, not just the application layer.

</td>
</tr>
</table>

<br/>

## 🧰 Tech Stack

<table>
<tr>
<td valign="top" width="50%">

**Cloud & Infrastructure as Code**

<img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS"/>
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform"/>

**Containers & Orchestration**

<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes"/>

</td>
<td valign="top" width="50%">

**CI/CD**

<img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" alt="Jenkins"/>
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions"/>

**OS, Language & Version Control**

<img src="https://img.shields.io/badge/Linux-1a1b27?style=for-the-badge&logo=linux&logoColor=FCC624" alt="Linux"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>

</td>
</tr>
</table>

<div align="center">

<img src="https://skillicons.dev/icons?i=aws,terraform,docker,kubernetes,jenkins,githubactions,linux,py,git,github&theme=dark" alt="skill icons"/>

</div>

<br/>

## 🌱 Currently Learning

<div align="center">

<img src="https://img.shields.io/badge/Advanced%20DevOps-7aa2f7?style=for-the-badge&labelColor=1a1b27" alt="Advanced DevOps"/>
<img src="https://img.shields.io/badge/Monitoring%20%26%20Observability-bb9af7?style=for-the-badge&labelColor=1a1b27" alt="Monitoring & Observability"/>
<img src="https://img.shields.io/badge/Site%20Reliability%20Engineering-f7768e?style=for-the-badge&labelColor=1a1b27" alt="SRE"/>
<img src="https://img.shields.io/badge/Aviation%20Infrastructure%20Systems-e0af68?style=for-the-badge&labelColor=1a1b27" alt="Aviation Infrastructure"/>
<img src="https://img.shields.io/badge/Kubernetes%20Architecture-9ece6a?style=for-the-badge&labelColor=1a1b27" alt="Kubernetes Architecture"/>

</div>

<br/>

## 🎯 Goal

> To become a **Cloud & DevOps Engineer** specializing in scalable and reliable aviation infrastructure systems.
>
> Building step by step, learning every day.

<br/>

## 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=priyanshisaugat01&show_icons=true&theme=tokyonight&hide_border=true&bg_color=1a1b27&title_color=7aa2f7&icon_color=bb9af7&text_color=c0caf5" alt="GitHub Stats" width="49%"/>
<img src="https://streak-stats.demolab.com/?user=priyanshisaugat01&theme=tokyonight&hide_border=true&background=1a1b27&stroke=7aa2f7&ring=bb9af7&fire=f7768e&currStreakLabel=c0caf5" alt="GitHub Streak" width="49%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=priyanshisaugat01&layout=compact&theme=tokyonight&hide_border=true&bg_color=1a1b27&title_color=7aa2f7&text_color=c0caf5" alt="Top Languages" width="49%"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=priyanshisaugat01&theme=tokyo-night&hide_border=true&bg_color=1a1b27&color=7aa2f7&line=bb9af7&point=f7768e" alt="Activity Graph" width="98%"/>

</div>

### 🏆 Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=priyanshisaugat01&theme=tokyonight&no-frame=true&margin-w=10&row=1&column=6" alt="GitHub Trophies"/>

</div>

### 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/priyanshisaugat01/priyanshisaugat01/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/priyanshisaugat01/priyanshisaugat01/output/github-contribution-grid-snake.svg"/>
  <img src="https://raw.githubusercontent.com/priyanshisaugat01/priyanshisaugat01/output/github-contribution-grid-snake.svg" alt="GitHub contribution snake animation" width="100%"/>
</picture>

</div>

<br/>

## 📫 Connect With Me

<div align="center">

<a href="https://github.com/priyanshisaugat01">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7aa2f7,50:414868,100:1a1b27&height=120&section=footer" width="100%"/>

</div>
