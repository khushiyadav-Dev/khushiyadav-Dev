<div align="center">

<img src="banner.png" alt="Khushi Yadav — Cloud + AI/ML Engineer in progress" width="100%" />

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1200&color=00D2FF&center=true&vCenter=true&width=700&lines=Hi%2C+I'm+Khushi+Yadav;Cloud+%2B+AI%2FML+Engineer+in+the+making;AWS+%7C+Linux+%7C+Docker+%7C+Terraform;Building+tools+that+make+cloud+cost+visible" alt="Typing SVG" />

### Cloud Engineer in progress · B.Tech CSE (AI & ML)

**I build AI-powered cloud tools — cost visibility, observability and automation.**

📍 Lucknow, India &nbsp;·&nbsp; 🎯 Open to Cloud / DevOps / Platform internships

<a href="https://www.linkedin.com/in/khushi-yadav-6417213a7">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://x.com/khushiyadav_08">
  <img src="https://img.shields.io/badge/X%20(Twitter)-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" />
</a>
<a href="https://instagram.com/khushiyadav_dev">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
</a>
<a href="https://leetcode.com/u/Khushiyadav-Dev">
  <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" />
</a>
<a href="https://www.kaggle.com/khushiy08">
  <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle" />
</a>
<a href="mailto:khushiyadav1254@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>

<img src="https://komarev.com/ghpvc/?username=khushiyadav-Dev&style=for-the-badge&color=00D2FF&label=PROFILE+VIEWS" alt="Profile views" />

</div>

---

## ☁️ About Me

- **Cloud:** AWS (EC2, S3, IAM, Lambda, CloudWatch), Linux administration, networking fundamentals — VPC, subnets, security groups, DNS, load balancing.
- **AI/ML:** Python, Pandas, scikit-learn, LLM APIs — and the infrastructure that makes models run in production.
- **Focus right now:** the two problems every cloud team is fighting in 2026 — **what AI and Kubernetes actually cost**, and **how to observe and automate the systems that run them**.
- **Goal:** build production-grade cloud tooling, ship it live, and grow into a Cloud / Platform Engineer role.

---

## 🚀 Featured Projects

### 🔴 Live now — [AgentCost](https://agentcost-sb3q.onrender.com/dashboard)

**A gateway that tells you which agent is burning your LLM budget.**

Every team using LLM APIs gets one big bill and cannot say which agent, feature or user spent it. AgentCost sits in front of the model calls: each request is tagged, priced from a per-model token table, and stored — then a dashboard shows spend **per agent, per task, per user**, with a daily budget alert. Runs offline with a mock provider, so it is testable with zero API keys.

`Python` · `FastAPI` · `SQLite` · `Docker` · `pytest` · `Render`

<a href="https://agentcost-sb3q.onrender.com/dashboard">
  <img src="https://img.shields.io/badge/▶_Try_Live_Demo-00D2FF?style=for-the-badge&logo=render&logoColor=black" alt="Live Demo" />
</a>
<a href="https://github.com/khushiyadav-Dev/AgentCost">
  <img src="https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source Code" />
</a>

> What it proves: designing a REST gateway, modelling cost attribution in a database, containerising with Docker, writing 12 automated tests, and shipping a public deployment — with the limitations stated openly instead of hidden.

### 🔴 Live now — [DhwaniSetu](https://dhwanis-mepxnw5imdendcfvmuogyb.streamlit.app)

**An ML model, deployed and running on the internet — not a notebook.**

DhwaniSetu listens to the sound of a tap on concrete and classifies it as **Normal / Warning / Danger**. It isolates the tap from the recording, extracts FFT spectrum, MFCC and ring-time features, and runs a Random Forest classifier — then serves the verdict through a phone-friendly web app in English and Hindi.

`Python` · `Streamlit` · `scikit-learn` · `Random Forest` · `FFT / MFCC` · `librosa`

<a href="https://dhwanis-mepxnw5imdendcfvmuogyb.streamlit.app">
  <img src="https://img.shields.io/badge/▶_Try_Live_Demo-00D2FF?style=for-the-badge&logo=streamlit&logoColor=black" alt="Live Demo" />
</a>
<a href="https://github.com/khushiyadav-Dev/DhwaniSetu">
  <img src="https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source Code" />
</a>

> What it proves: audio feature engineering, model training with cross-validation, a documented limitation section (the model is trained on synthetic sounds — stated openly, not hidden), and **end-to-end deployment**.

### More projects

<table>
<tr>
<td width="33%" valign="top">

**🤖 Cloud-Native AI Pipeline** *(WIP)*
<br/>
Multi-agent system that maps a student's skills against real job requirements and returns a gap report.

`Python` · `LLM APIs`

[Repository](https://github.com/khushiyadav-Dev/Cloud-Native-AI-Pipeline)

</td>
<td width="33%" valign="top">

**📊 Cloud Data Automation**
<br/>
Automates grocery billing with Pandas and writes clean CSV reports — repeatable data workflows, not manual sheets.

`Python` · `Pandas`

[Repository](https://github.com/khushiyadav-Dev/Cloud-Data-Automation)

</td>
<td width="33%" valign="top">

**🐍 Python Foundations**
<br/>
Daily Python practice — data structures, OOP, file handling, problem solving. 100+ commits and counting.

`Python`

[Repository](https://github.com/khushiyadav-Dev/Python-Basics-Practice)

</td>
</tr>
</table>

## 🚧 Currently Building

<table>
<tr>
<td width="100%">

**`AgentCost` — Phase 4: hardening + real cloud**

Live on Render's free tier. Next: move it to AWS with Terraform, then make it multi-tenant.

`Python` · `FastAPI` · `Docker` · `Terraform` · `AWS`

- [x] Gateway, cost engine, dashboard, budget alert
- [x] Docker + docker-compose + 12 pytest tests
- [x] Public deployment with a live URL
- [ ] Terraform: ECR + ECS Fargate + RDS on AWS
- [ ] API keys per tenant, rate limiting, CSV export

</td>
</tr>
</table>

**Learning now:** Terraform · AWS ECS/RDS · Kubernetes (CKA track) · GitHub Actions CI · Prometheus & Grafana

---

## 🛠️ Tech Stack

| Area | Tools |
|---|---|
| **Cloud** | AWS · EC2 · S3 · IAM · Lambda · CloudWatch · VPC |
| **DevOps** | Docker · Docker Compose · Terraform · GitHub Actions · Nginx · Git · Render |
| **Systems** | Linux · Bash · Networking (TCP/IP, DNS, HTTP, Load Balancing) |
| **Languages** | Python · JavaScript · HTML · CSS · SQL |
| **Backend** | FastAPI · REST APIs · SQLite · pytest |
| **AI / ML** | Pandas · NumPy · scikit-learn · LLM APIs · Prompt & agent design |
| **Data** | PostgreSQL · CSV / ETL with Pandas |
| **Tools** | VS Code · Postman · Jupyter · Git & GitHub |

---

## 📈 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=khushiyadav-Dev&show_icons=true&include_all_commits=true&theme=tokyonight&hide_border=true&title_color=00D2FF&icon_color=00D2FF" alt="GitHub Stats" />
<img height="170" src="https://github-readme-streak-stats.herokuapp.com/?user=khushiyadav-Dev&theme=tokyonight&hide_border=true&stroke=00D2FF&ring=00D2FF&fire=00D2FF" alt="GitHub Streak" />

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=khushiyadav-Dev&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&title_color=00D2FF" alt="Top Languages" />
<img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=khushiyadav-Dev&theme=github_dark" alt="Repos per language" />

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=khushiyadav-Dev&theme=tokyo-night&hide_border=true&color=00D2FF&line=00D2FF&point=FFFFFF" alt="Contribution Activity Graph" />

<img width="95%" src="https://github-profile-trophy.vercel.app/?username=khushiyadav-Dev&theme=tokyonight&no-frame=true&no-bg=true&column=6&margin-w=10" alt="GitHub Trophies" />

</div>

---

## 🎓 Certifications & Learning Path

| Status | Certification |
|---|---|
| 🎯 Next | AWS Certified Solutions Architect – Associate (SAA-C03) |
| 📚 Planned | Terraform Associate (HashiCorp) |
| 📚 Planned | CKA – Certified Kubernetes Administrator |

---

## 🤝 Open Source & Collaboration

- Contributed to team repositories (`Devdoots_Python`, `Devdoots_VyomAcre`) — pull requests, reviews and feature work.
- Comfortable with Git workflows: branches, PRs, code review, resolving conflicts.

---

<div align="center">

### Let's build something on the cloud

<a href="https://www.linkedin.com/in/khushi-yadav-6417213a7">
  <img src="https://img.shields.io/badge/Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn" />
</a>

<br/><br/>

<i>"Code is just logic in disguise. My goal is to build cloud-native software that scales globally."</i>

</div>







<div align="center">

<img src="banner.png" alt="Khushi Yadav — Cloud + AI/ML Engineer in progress" width="100%" />

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1200&color=00D2FF&center=true&vCenter=true&width=700&lines=Hi%2C+I'm+Khushi+Yadav;Cloud+%2B+AI%2FML+Engineer+in+the+making;AWS+%7C+Linux+%7C+Docker+%7C+Terraform;Building+tools+that+make+cloud+cost+visible" alt="Typing SVG" />

### Cloud Engineer in progress · B.Tech CSE (AI & ML)

**I build AI-powered cloud tools — cost visibility, observability and automation.**

📍 Lucknow, India &nbsp;·&nbsp; 🎯 Open to Cloud / DevOps / Platform internships

<a href="https://www.linkedin.com/in/khushi-yadav-6417213a7">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://x.com/khushiyadav_08">
  <img src="https://img.shields.io/badge/X%20(Twitter)-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" />
</a>
<a href="https://instagram.com/khushiyadav_dev">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
</a>
<a href="https://leetcode.com/u/Khushiyadav-Dev">
  <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" />
</a>
<a href="https://www.kaggle.com/khushiy08">
  <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle" />
</a>
<a href="mailto:khushiyadav1254@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>

<img src="https://komarev.com/ghpvc/?username=khushiyadav-Dev&style=for-the-badge&color=00D2FF&label=PROFILE+VIEWS" alt="Profile views" />

</div>

---

## ☁️ About Me

- **Cloud:** AWS (EC2, S3, IAM, Lambda, CloudWatch), Linux administration, networking fundamentals — VPC, subnets, security groups, DNS, load balancing.
- **AI/ML:** Python, Pandas, scikit-learn, LLM APIs — and the infrastructure that makes models run in production.
- **Focus right now:** the two problems every cloud team is fighting in 2026 — **what AI and Kubernetes actually cost**, and **how to observe and automate the systems that run them**.
- **Goal:** build production-grade cloud tooling, ship it live, and grow into a Cloud / Platform Engineer role.

---

## 🚀 Featured Projects

### 🔴 Live now — [DhwaniSetu](https://dhwanis-mepxnw5imdendcfvmuogyb.streamlit.app)

**An ML model, deployed and running on the internet — not a notebook.**

DhwaniSetu listens to the sound of a tap on concrete and classifies it as **Normal / Warning / Danger**. It isolates the tap from the recording, extracts FFT spectrum, MFCC and ring-time features, and runs a Random Forest classifier — then serves the verdict through a phone-friendly web app in English and Hindi.

`Python` · `Streamlit` · `scikit-learn` · `Random Forest` · `FFT / MFCC` · `librosa`

<a href="https://dhwanis-mepxnw5imdendcfvmuogyb.streamlit.app">
  <img src="https://img.shields.io/badge/▶_Try_Live_Demo-00D2FF?style=for-the-badge&logo=streamlit&logoColor=black" alt="Live Demo" />
</a>
<a href="https://github.com/khushiyadav-Dev/DhwaniSetu">
  <img src="https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source Code" />
</a>

> What it proves: audio feature engineering, model training with cross-validation, a documented limitation section (the model is trained on synthetic sounds — stated openly, not hidden), and **end-to-end deployment**.

### More projects

<table>
<tr>
<td width="33%" valign="top">

**🤖 Cloud-Native AI Pipeline** *(WIP)*
<br/>
Multi-agent system that maps a student's skills against real job requirements and returns a gap report.

`Python` · `LLM APIs`

[Repository](https://github.com/khushiyadav-Dev/Cloud-Native-AI-Pipeline)

</td>
<td width="33%" valign="top">

**📊 Cloud Data Automation**
<br/>
Automates grocery billing with Pandas and writes clean CSV reports — repeatable data workflows, not manual sheets.

`Python` · `Pandas`

[Repository](https://github.com/khushiyadav-Dev/Cloud-Data-Automation)

</td>
<td width="33%" valign="top">

**🐍 Python Foundations**
<br/>
Daily Python practice — data structures, OOP, file handling, problem solving. 100+ commits and counting.

`Python`

[Repository](https://github.com/khushiyadav-Dev/Python-Basics-Practice)

</td>
</tr>
</table>

## 🚧 Currently Building

<table>
<tr>
<td width="100%">

**`AgentCost` — per-agent LLM cost attribution** *(in progress)*

Every team using LLM APIs knows the bill is growing and nobody can say *which feature or agent* is spending it. AgentCost sits in front of model calls, tags every request, and reports **cost per user, per agent, per task** with budget alerts.

`Python` · `FastAPI` · `PostgreSQL` · `Docker` · `Terraform` · `AWS`

- [x] Problem definition + data model
- [ ] Gateway + cost calculator
- [ ] Dashboard + budget alerts
- [ ] Terraform deploy on AWS

</td>
</tr>
</table>

**Learning now:** Kubernetes (CKA track) · Terraform · GitHub Actions · Prometheus & Grafana · OpenTelemetry

---

## 🛠️ Tech Stack

| Area | Tools |
|---|---|
| **Cloud** | AWS · EC2 · S3 · IAM · Lambda · CloudWatch · VPC |
| **DevOps** | Docker · Terraform · GitHub Actions · Nginx · Git |
| **Systems** | Linux · Bash · Networking (TCP/IP, DNS, HTTP, Load Balancing) |
| **Languages** | Python · JavaScript · HTML · CSS · SQL |
| **AI / ML** | Pandas · NumPy · scikit-learn · LLM APIs · Prompt & agent design |
| **Data** | PostgreSQL · CSV / ETL with Pandas |
| **Tools** | VS Code · Postman · Jupyter · Git & GitHub |

---

## 📈 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=khushiyadav-Dev&show_icons=true&include_all_commits=true&theme=tokyonight&hide_border=true&title_color=00D2FF&icon_color=00D2FF" alt="GitHub Stats" />
<img height="170" src="https://github-readme-streak-stats.herokuapp.com/?user=khushiyadav-Dev&theme=tokyonight&hide_border=true&stroke=00D2FF&ring=00D2FF&fire=00D2FF" alt="GitHub Streak" />

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=khushiyadav-Dev&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&title_color=00D2FF" alt="Top Languages" />
<img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=khushiyadav-Dev&theme=github_dark" alt="Repos per language" />

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=khushiyadav-Dev&theme=tokyo-night&hide_border=true&color=00D2FF&line=00D2FF&point=FFFFFF" alt="Contribution Activity Graph" />

<img width="95%" src="https://github-profile-trophy.vercel.app/?username=khushiyadav-Dev&theme=tokyonight&no-frame=true&no-bg=true&column=6&margin-w=10" alt="GitHub Trophies" />

</div>

---

## 🎓 Certifications & Learning Path

| Status | Certification |
|---|---|
| 🎯 Next | AWS Certified Solutions Architect – Associate (SAA-C03) |
| 📚 Planned | Terraform Associate (HashiCorp) |
| 📚 Planned | CKA – Certified Kubernetes Administrator |

---

## 🤝 Open Source & Collaboration

- Contributed to team repositories (`Devdoots_Python`, `Devdoots_VyomAcre`) — pull requests, reviews and feature work.
- Comfortable with Git workflows: branches, PRs, code review, resolving conflicts.

---

<div align="center">

### Let's build something on the cloud

<a href="https://www.linkedin.com/in/khushi-yadav-6417213a7">
  <img src="https://img.shields.io/badge/Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn" />
</a>

<br/><br/>

<i>"Code is just logic in disguise. My goal is to build cloud-native software that scales globally."</i>

</div>
