<!-- ===================== HEADER (animated wave) ===================== -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&color=0:512BD4,50:2E9EF7,100:00C9A7&height=230&section=header&text=Subhe%20Daher&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=.NET%20Backend%20Engineer%20%7C%20DevOps&descAlignY=60&descSize=22" alt="header"/>
</div>

<!-- ===================== TYPING ANIMATION ===================== -->
<div align="center">
  <a href="https://github.com/subhedaher">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=900&color=2E9EF7&center=true&vCenter=true&width=800&height=60&lines=From+Architecture+%E2%86%92+Monitored+Production+%F0%9F%9A%80;Clean+Architecture+%2B+CQRS+with+ASP.NET+Core;CI%2FCD+with+GitHub+Actions+%E2%9A%99%EF%B8%8F;Docker+%2B+Nginx+%2B+Linux+in+Production+%F0%9F%90%B3;Real-time+ERP+fed+by+100%2B+IoT+Devices+%E2%9A%A1" alt="Typing SVG"/>
  </a>
</div>

<div align="center">
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white"/>
</div>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=subhedaher&label=Profile%20Views&color=512bd4&style=for-the-badge" alt="views"/>
</p>

---

## 👨‍💻 About Me

```csharp
public sealed class SubheDaher : IBackendEngineer, IDevOpsEngineer
{
    public string Role       => ".NET Backend Engineer | DevOps";
    public string Location   => "Cairo, Egypt 🇪🇬";
    public int    Experience => 4; // years, production systems

    public string[] Stack => new[]
    {
        "ASP.NET Core", "EF Core", "SignalR", "Hangfire", "MediatR",
        "Docker", "GitHub Actions", "Nginx", "Linux", "AWS"
    };

    public string Philosophy =>
        "Ship fast, ship safe: modular code + automated pipelines.";

    public Task<Release> TakeFeatureToProduction(Feature f) =>
        f.Design()        // Clean Architecture + CQRS
         .Build()         // .NET 
         .Containerize()  // Docker
         .Deploy()        // GitHub Actions → push-to-deploy
         .Monitor();      // Serilog + Health Checks
}
```

- 🏢 **.NET Backend Engineer @ AI Cloud**: powering a real-time smart ERP fed by **100+ IoT devices**
- 🏗️ I design modular backends with **Clean Architecture & CQRS**, then automate the whole delivery pipeline
- 🔁 Every release: **build → push → deploy → migrate → health check → rollback**
- 🛡️ Secure production on **Linux + Nginx + SSL/TLS (auto-renewing)**
- 📫 **subhedaher@gmail.com**

---

## 📊 Impact in Numbers

<div align="center">

| ⚡ 100+ | 🧩 18 | 🔌 120+ | 🔐 64 | 🚢 10+ |
|:---:|:---:|:---:|:---:|:---:|
| **IoT devices** streaming into a live ERP | **Modules** in one compliance platform | **REST endpoints** delivered | **Permissions** mapped to policies & JWT claims | **Production backends** delivered |

</div>

---

## 🔄 How I Ship (CI/CD Pipeline)

```mermaid
flowchart LR
    A[💻 git push] --> B[🏗️ Build & Test]
    B --> C[🐳 Docker Image]
    C --> D[📦 Registry Push]
    D --> E[🚀 Deploy]
    E --> F[🗄️ EF Migrations]
    F --> G{❤️ Health Check}
    G -- ✅ Healthy --> H[🎉 Live]
    G -- ❌ Failed --> I[⏪ Auto Rollback]
    style A fill:#512BD4,color:#fff
    style H fill:#239120,color:#fff
    style I fill:#E44C30,color:#fff
```

---

## 🛠️ Tech Stack

### 🟣 .NET & Backend
<p>
<img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white"/>
<img src="https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>
<img src="https://img.shields.io/badge/EF_Core-512BD4?style=for-the-badge&logo=nuget&logoColor=white"/>
<img src="https://img.shields.io/badge/SignalR-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>
<img src="https://img.shields.io/badge/Hangfire-2C3E50?style=for-the-badge&logo=hangfire&logoColor=white"/>
<img src="https://img.shields.io/badge/MediatR-CQRS-5C2D91?style=for-the-badge"/>
<img src="https://img.shields.io/badge/FluentValidation-0078D4?style=for-the-badge"/>
<img src="https://img.shields.io/badge/LINQ-239120?style=for-the-badge"/>
</p>

### 🏛️ Architecture & Security
<p>
<img src="https://img.shields.io/badge/Clean_Architecture-0A66C2?style=for-the-badge"/>
<img src="https://img.shields.io/badge/CQRS-7B1FA2?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Repository_%26_UoW-455A64?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Dependency_Injection-00796B?style=for-the-badge"/>
<img src="https://img.shields.io/badge/JWT_Auth-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white"/>
<img src="https://img.shields.io/badge/RBAC-D32F2F?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Multi--Tenancy-F57C00?style=for-the-badge"/>
</p>

### 🐳 DevOps & Cloud
<p>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white"/>
<img src="https://img.shields.io/badge/CI%2FCD-4285F4?style=for-the-badge&logo=githubactions&logoColor=white"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
<img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white"/>
<img src="https://img.shields.io/badge/SSL%2FTLS-Certbot-003A70?style=for-the-badge&logo=letsencrypt&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS-EC2_%7C_VPC_%7C_IAM_%7C_S3-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white"/>
</p>

### 📈 Reliability & Observability
<p>
<img src="https://img.shields.io/badge/Serilog-Structured_Logging-1E88E5?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Health_Checks-43A047?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Monitoring-E65100?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Production_Troubleshooting-6D4C41?style=for-the-badge"/>
</p>

### 🗄️ Data & Tools
<p>
<img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-E44C30?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual-studio&logoColor=white"/>
<img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white"/>
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
</p>

<sub>Also worked with: PHP · Laravel · JavaScript</sub>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🛃 AlSalam Import Compliance Platform
`ASP.NET Core` `CQRS` `Hangfire` `Docker` `GitHub Actions`

- **18 modules / 120+ endpoints**: companies, suppliers, products, shipments, documents
- ⏰ Automated **expiry-reminder engine** (Hangfire + HTML email templates)
- 🔐 **RBAC**: 64 permissions → policies + JWT claims, audit trail, soft-delete/restore
- 🌍 Bilingual **EN / AR**
- 🐳 **Stage + Production** envs with push-to-deploy & automated migrations

</td>
<td width="50%" valign="top">

### 🧠 Smart ERP (Real-time IoT)
`ASP.NET Core` `SignalR` `Clean Architecture` `Nginx`

- ⚡ Live dashboards & instant notifications from **100+ IoT devices**
- 🧩 Independent modules: tasks, attendance, resource allocation
- 🚢 Full release automation: build → deploy → migrate → health check → **rollback**
- 📈 Serilog + health checks + monitoring for faster troubleshooting

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛒 E-Commerce Platform
`ASP.NET Core` `Clean Architecture` `EF Core`

- Catalog with variants, inventory, cart, discounts & coupons
- Secure checkout with **transactional integrity** across the full order lifecycle

</td>
<td width="50%" valign="top">

### 🏘️ PropTech Platform (Bikam) 🇸🇦
`Laravel` `MySQL` · *Project Manager & Backend*

- Real estate valuation platform for the Saudi market
- Scalable schema design + automated valuation workflow

</td>
</tr>
</table>

---

## 🎓 Education & Certifications

- 🎓 B.Sc. Software Development: *Islamic University of Gaza*
- ☁️ **AWS DevOps & Cloud Fundamentals**: Cloud Native Base Camp (2025)
- 🏛️ **Software Architecture**: Udemy (2024)
- 🌐 **ASP.NET Core Web Development**: Udemy (2023)

---

## 📈 GitHub Stats

<div align="center">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=subhedaher&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="stats"/>
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=subhedaher&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="langs"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=subhedaher&theme=tokyonight&hide_border=true" alt="streak"/>
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=subhedaher&theme=tokyo-night&hide_border=true&area=true" alt="activity"/>
</div>

---

## 🐍 Contribution Snake

<div align="center">
  <img src="https://raw.githubusercontent.com/subhedaher/subhedaher/output/github-contribution-grid-snake-dark.svg" alt="snake"/>
</div>

---

## 🤝 Let's Connect

<p align="center">
  <a href="https://www.linkedin.com/in/subhe-daher-843764214" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:subhedaher@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://www.facebook.com/profile.php?id=100007729127811" target="_blank">
    <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook"/>
  </a>
  <a href="https://www.instagram.com/subhedaher/" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/>
  </a>
</p>

<div align="center">

### 💼 Open for .NET & DevOps opportunities

**"First, solve the problem. Then, write the code."** – John Johnson

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:512BD4,50:2E9EF7,100:00C9A7&height=120&section=footer&animation=twinkling" width="100%" alt="footer"/>
