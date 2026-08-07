<h1 align="center">Hi 👋, I'm Khushi Yadav</h1>
<h3 align="center">Aspiring Cloud Engineer | B.Tech CSE (AI & ML)</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1000&color=00D2FF&center=true&vcenter=true&width=500&lines=Cloud+Architecture+%26+AWS+Enthusiast;Building+Scalable+Cloud+%26+AI+Systems;Open+Source+Contributor" alt="Typing SVG" />
</p>

---

## ☁️ About Me

xml
<p style="font-size: 15px; line-height: 1.6;">
  ☁️ <b>Cloud Focus:</b> Exploring AWS, Linux Server Management, Networking & Cloud Infrastructure.<br/>
  
  🤖 <b>AI/ML Background:</b> Integrating Machine Learning models into cloud-native applications.<br/>
  
  🎯 <b>Current Goal:</b> Building robust, auto-scalable, and secure cloud solutions.
</p>

<div align="center">
<a href="https://www.linkedin.com/in/khushi-yadav-6417213a7?utm_source=share_via&utm_content=profile&utm_medium=member_android" target="_blank">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="https://x.com/khushiyadav_08" target="_blank">
<img src="https://img.shields.io/badge/X%20(Twitter)-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"/>
</a>
<a href="https://leetcode.com/u/Khushiyadav-Dev" target="_blank">
<img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/>
</a>
<a href="https://www.kaggle.com/khushiy08" target="_blank">
<img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle"/>
</a>
</div>

<p align="center">
<img height="185" src="https://github-readme-stats.vercel.app/api?username=khushiyadav-Dev&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Khushi's GitHub Stats" </p>
  
<img height="180" src="https://github-readme-streak-stats.herokuapp.com/?user=khushiyadav-Dev&theme=tokyonight&hide_border=true" alt="Khushi's GitHub Streak" />
</div>
<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=khushiyadav-Dev&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</div>


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>GitHub Dashboard</title>
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
  <style>
    body {
      margin: 0;
      font-family: Arial;
      background: #0f172a;
      color: white;
    }

    .container {
      width: 90%;
      margin: auto;
      margin-top: 30px;
    }

    .card {
      background: linear-gradient(135deg, #1e293b, #0f172a);
      padding: 20px;
      border-radius: 15px;
      margin-bottom: 20px;
      box-shadow: 0px 0px 15px rgba(0,0,0,0.5);
    }

    .top {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .stats-box {
      display: flex;
      gap: 20px;
    }

    .box {
      flex: 1;
      padding: 20px;
      border-radius: 15px;
      background: #1e293b;
    }

    h2 {
      color: #38bdf8;
    }

    .highlight {
      color: #22c55e;
    }
  </style>
</head>
<body>

<div class="container">

  <!-- Top Card -->
  <div class="card top">
    <div>
      <h2>khushiyadav-Dev</h2>
      <p class="highlight">📊 GitHub Contributions</p>
      <p>📁 Public Repos: 5</p>
      <p>📅 Joined: 2025</p>
      <p>📧 khushiyadav1254@gmail.com</p>
    </div>

    <canvas id="areaChart" width="400" height="200"></canvas>
  </div>

  <!-- Bottom Cards -->
  <div class="stats-box">
    
    <div class="box">
      <h2>Top Languages</h2>
      <canvas id="donutChart"></canvas>
    </div>

    <div class="box">
      <h2>Stats</h2>
      <p>⭐ Stars: 8</p>
      <p>💻 Commits: 200+</p>
      <p>🔀 PRs: 40+</p>
      <p>⚠ Issues: 1</p>
    </div>

  </div>

</div>

<script>
  // Area Chart
  const ctx = document.getElementById('areaChart');
  new Chart(ctx, {
    type: 'line',
    data: {
      labels: ['Jan','Feb','Mar','Apr','May','Jun','Jul'],
      datasets: [{
        label: 'Contributions',
        data: [5, 10, 15, 20, 50, 120, 80],
        fill: true,
        borderColor: '#a855f7',
        backgroundColor: 'rgba(168,85,247,0.3)'
      }]
    }
  });

  // Donut Chart
  const ctx2 = document.getElementById('donutChart');
  new Chart(ctx2, {
    type: 'doughnut',
    data: {
      labels: ['Python', 'Jupyter', 'JavaScript'],
      datasets: [{
        data: [50, 30, 20],
        backgroundColor: ['#38bdf8', '#facc15', '#22c55e']
      }]
    }
  });
</script>

</body>
</html>

graph LR
A[Client Request] -->B[AWS Route53 / CDN]
B --> C[Application Load Balancer]
C --> D[Dockerized Container - AWS EC2]
D --> E[Amazon S3 / RDS Database]

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)

</div>
<p align="center">
<i>"Code is just logic in disguise. My goal is to build cloud-native software that scales globally."</i>
</p>





