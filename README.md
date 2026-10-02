<div align="center">

<img src="./assets/header.svg" alt="Segun Alabi — Senior Full Stack Engineer · Founding Engineer (AI/LLM & Cloud)" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1400&color=00E5A0&center=true&vCenter=true&width=720&lines=I+build+real-time+systems+that+make+decisions+in+milliseconds.;LLM+%2B+RAG+copilots+that+cut+investigation+time+by+40%25.;From+0%E2%86%921%3A+architecture%2C+AI%2C+pipelines%2C+cloud%2C+UI.)](https://portfolio-segun.vercel.app)

<a href="https://portfolio-segun.vercel.app"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-portfolio--segun.vercel.app-00e5a0?style=for-the-badge&logo=vercel&logoColor=black&labelColor=0d1117"/></a>
<a href="https://www.linkedin.com/in/segun-alabi-baa17225"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Segun%20Alabi-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117"/></a>
<a href="mailto:segunalabi383@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-segunalabi383-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d1117"/></a>
<a href="https://github.com/segunalabi383"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-segunalabi383-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117"/></a>
<img alt="Location" src="https://img.shields.io/badge/Based%20in-East%20Orange%2C%20NJ-8b949e?style=for-the-badge&logo=googlemaps&logoColor=white&labelColor=0d1117"/>


<img alt="Profile views" src="https://komarev.com/ghpvc/?username=segunalabi383&label=Profile%20views&color=00e5a0&style=flat-square&labelColor=0d1117"/>

</div>

<br/>

> **Senior engineer with 10+ years building real-time, high-throughput and AI-driven systems** across ride-sharing, enterprise SaaS, industrial IoT and e-commerce.
> As a **Founding Engineer**, I own the whole path from 0→1: product architecture, LLM integrations, streaming data pipelines and full-stack delivery on AWS/GCP.
> I care about one thing above all: **shipping work that moves a number.**

<br/>

## ⚡ Impact at a glance

<img src="./assets/impact.svg" alt="Impact metrics" width="100%"/>

## 🧭 Career path

<img src="./assets/timeline.svg" alt="Career timeline" width="100%"/>

---

## 🏗️ Flagship work

<details open>
<summary><b>🛡️ Uber — Real-Time Fraud Detection &amp; Risk Scoring Platform</b> &nbsp;·&nbsp; <code>2022 – now</code></summary>
<br/>

**The problem:** spot suspicious transactions in real time across high-volume workloads, without slowing riders, drivers or analysts down.

```mermaid
flowchart LR
    A["Transactions &<br/>user activity"]:::src --> B["Ingestion APIs<br/>Nest.js · OAuth"]:::svc
    B --> C[("Redis<br/>hot features")]:::db
    B --> D["Risk scoring<br/>Python · Django"]:::svc
    C --> D
    D --> M[("MongoDB")]:::db
    D --> E{{"Decision"}}:::dec
    E -- low risk --> F["Auto-approve"]:::ok
    E -- suspicious --> G["LLM + RAG copilot<br/>LangChain"]:::ai
    G --> H["Analyst dashboard<br/>Next.js · TypeScript"]:::ui

    classDef src fill:#161b22,stroke:#8b949e,color:#e6edf3
    classDef svc fill:#0d1117,stroke:#00e5a0,color:#e6edf3
    classDef db  fill:#0d1117,stroke:#5fbf9f,color:#e6edf3
    classDef dec fill:#0f2a23,stroke:#00e5a0,color:#00e5a0
    classDef ai  fill:#00e5a0,stroke:#00e5a0,color:#0d1117
    classDef ui  fill:#0d1117,stroke:#58a6ff,color:#e6edf3
    classDef ok  fill:#0d1117,stroke:#3fb950,color:#3fb950
```
<sub><i>Simplified architecture.</i></sub>

| What I built | Result |
| :-- | :-- |
| API-first Python/Django + Node.js/Nest.js microservices with OAuth and role-based access | Secure, independently scalable services |
| Real-time scoring pipelines over transaction behavior, user activity and contextual signals | Automated risk decisions |
| LLM + RAG + LangChain analyst copilot for suspicious-transaction review | Faster, more accurate investigations |
| MongoDB and Redis access-pattern tuning | **30% lower latency** |
| React / Next.js risk-operations dashboards | **40% faster investigation decisions** |
| WebSocket / Socket.IO live earnings and incentive updates | Real-time UX |
| AWS, Docker, Kubernetes, Terraform, distributed tracing and observability | Higher production reliability |
| Mentored 3 engineers on AI integration, cloud-native design and API design | A stronger team |

`Python` `Django` `TypeScript` `Next.js` `Nest.js` `LLMs` `RAG` `LangChain` `MongoDB` `Redis` `AWS` `Docker` `Kubernetes` `Terraform`

</details>

<details>
<summary><b>🏭 Scribe — Predictive Maintenance &amp; Industrial Visualization Platform</b> &nbsp;·&nbsp; <code>2019 – 2022</code></summary>
<br/>

**The problem:** turn millions of industrial sensor readings into early warnings before equipment fails.

- 📉 **25% less equipment downtime** from predictive analytics and anomaly-detection models
- 🌊 Ingestion pipelines processing **50,000+ events per minute** for real-time analytics
- 📊 Real-time React, D3.js and Chart.js dashboards over **millions of data points**, with **40% faster rendering** through virtualization
- 🧩 A reusable TypeScript visualization library adopted by **6+ enterprise clients**
- 🔁 Worked with data scientists to put ML models into production with automated retraining
- 🚨 Event-driven alerting and monitoring for industrial systems

`React` `TypeScript` `D3.js` `Chart.js` `Python` `Node.js` `AWS` `Docker` `Kubernetes` `Predictive Analytics`

</details>

<details>
<summary><b>🎞️ Cognizant — Multimedia Data Analytics ETL Pipeline</b> &nbsp;·&nbsp; <code>2015 – 2019</code></summary>
<br/>

**The problem:** give analysts and field teams reliable visibility into high-volume multimedia ETL jobs.

- ⚙️ REST APIs and backend services for multimedia ingestion, processing, analytics and pipeline management
- 📱 React / React Native dashboards for ETL status, data quality and results, with **22% higher mobile engagement**
- ⚡ **40% faster web load times** from a modernized React architecture and faster APIs
- 📶 Offline-first mobile features with local sync, making field teams **30% more reliable**
- 🗄️ **50% faster reporting** from PostgreSQL query optimization and indexing
- 🚀 CI/CD with Docker on AWS that cut **deployments from hours to minutes**, plus Jest and Cypress test suites

`React` `React Native` `Node.js` `Nest.js` `PostgreSQL` `AWS` `Docker` `CI/CD` `Jest` `Cypress`

</details>

<sub>🎓 <b>B.S. Computer Science</b> — Princeton University (2011 – 2015)</sub>

---

## 🧠 How I build

| | Principle | In practice |
| :-: | :-- | :-- |
| 🎯 | **Impact first** | Every project starts with the metric it should move: latency, downtime or decision time. |
| ⚡ | **Real-time by default** | Streaming pipelines, WebSockets and caches so decisions happen while they still matter. |
| 🤖 | **AI with guardrails** | LLM and RAG features backed by automated evaluation pipelines, observability and retraining. |
| 🧱 | **Own the whole stack** | From Terraform and Kubernetes to the API contract and the pixel on the dashboard. |
| 🌱 | **Multiply the team** | Mentoring engineers on AI integration, streaming and scalable API design. |

---

## 🛠️ Toolbox

<table>
<tr><td><b>Languages &amp; Frontend</b></td><td><img src="https://skillicons.dev/icons?i=ts,js,py,php,cs,react,nextjs,threejs,d3,tailwind,bootstrap,materialui&perline=12" alt="Languages and frontend"/></td></tr>
<tr><td><b>Backend &amp; Data</b></td><td><img src="https://skillicons.dev/icons?i=nodejs,nestjs,django,dotnet,laravel,postgres,mysql,mongodb,redis,dynamodb,sqlite&perline=12" alt="Backend and databases"/></td></tr>
<tr><td><b>Cloud, DevOps &amp; QA</b></td><td><img src="https://skillicons.dev/icons?i=aws,gcp,docker,kubernetes,terraform,githubactions,git,github,postman,jest,cypress,playwright&perline=12" alt="Cloud, DevOps and testing"/></td></tr>
<tr><td><b>AI / ML</b></td><td>

![LLMs](https://img.shields.io/badge/LLMs-0d1117?style=flat-square&logo=openai&logoColor=00e5a0)
![RAG](https://img.shields.io/badge/RAG-0d1117?style=flat-square&logo=databricks&logoColor=00e5a0)
![LangChain](https://img.shields.io/badge/LangChain-0d1117?style=flat-square&logo=langchain&logoColor=00e5a0)
![Predictive Analytics](https://img.shields.io/badge/Predictive%20Analytics-0d1117?style=flat-square&logo=scikitlearn&logoColor=00e5a0)
![Eval Pipelines](https://img.shields.io/badge/Automated%20Eval%20Pipelines-0d1117?style=flat-square&logo=githubactions&logoColor=00e5a0)
![Model Ops](https://img.shields.io/badge/Model%20Deployment%20%26%20Retraining-0d1117?style=flat-square&logo=kubernetes&logoColor=00e5a0)

</td></tr>
</table>

<details>
<summary><code>segun@dev:~$ cat stack.json</code></summary>

```json
{
  "name": "Segun Alabi",
  "title": "Senior Full Stack Engineer | Founding Engineer — AI/LLM & Cloud Platforms",
  "location": "East Orange, NJ",
  "experience": "10+ years",
  "languages": ["JavaScript (ES6+)", "TypeScript", "Python", "PHP", "SQL", "C#"],
  "frontend": ["React", "React Native", "Next.js", "Three.js", "D3.js", "Tailwind CSS", "Bootstrap", "Material-UI"],
  "backend": ["Nest.js", "Node.js", "Django", ".NET", "Laravel", "OAuth", "REST APIs", "Microservices"],
  "cloud": ["AWS", "EC2", "S3", "Lambda", "GCP", "Docker", "Kubernetes", "Terraform", "CI/CD Pipelines", "Distributed Tracing", "Observability"],
  "databases": ["PostgreSQL", "MySQL", "MongoDB", "Redis", "DynamoDB", "SQLite"],
  "ai": ["LLMs", "RAG", "LangChain", "Predictive Analytics", "Automated Evaluation Pipelines", "Model Deployment & Retraining"],
  "tools": ["Git", "GitHub", "Postman", "Jest", "Cypress", "Playwright", "Swagger/OpenAPI", "ESLint", "Prettier"]
}
```

</details>

---

<!-- ══════════════ OPEN SOURCE ══════════════ -->

## 🚀 Open-source builds

| Project | What it does | Stack |
| :-- | :-- | :-- |
| [**eCommerce-next-nest.js**](https://github.com/segunalabi383/eCommerce-next-nest.js) 🛒 | Full-stack eCommerce platform with AI-powered product creation via the Vercel AI SDK | `Next.js` `Nest.js` `MongoDB` `AI SDK` |
| [**Data-Extractor**](https://github.com/segunalabi383/Data-Extractor) 🔎 | Structured data extractor for AI agents: search documents or the web and get JSON or Markdown back in a single tool call | `Python` `AI Agents` |
| [**LLM-APPs**](https://github.com/segunalabi383/LLM-APPs) 🤖 | Collection of LLM apps with AI agents and RAG across OpenAI, Anthropic, Gemini and open-source models | `Python` `RAG` `Agents` |
| [**Multi-Tenant Invoice Reconciliation API**](https://github.com/segunalabi383/Multi-Tenant-Invoice-Reconciliation-API-Python) 🧾 | Multi-tenant API for reconciling invoices | `Python` `REST` |
| [**lightweight-chat-app**](https://github.com/segunalabi383/lightweight-chat-app) 💬 | Lightweight chat application | `TypeScript` |
| [**portfolio-segun**](https://github.com/segunalabi383/portfolio-segun) 🌐 | Source for [portfolio-segun.vercel.app](https://portfolio-segun.vercel.app) | `TypeScript` |

---

<!-- ══════════════ GITHUB STATS ══════════════ -->

## 📊 GitHub Stats

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com/?user=segunalabi383&theme=dark&hide_border=true&background=0d1117&ring=00e5a0&fire=00897b&currStreakLabel=00e5a0&sideLabels=8b949e&dates=8b949e&sideNums=ffffff&currStreakNum=ffffff)

<br/>

<img height="170" src="https://github-readme-stats.vercel.app/api?username=segunalabi383&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00e5a0&icon_color=00e5a0&text_color=8b949e&ring_color=00e5a0&count_private=true" alt="GitHub Stats"/>
&nbsp;
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=segunalabi383&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00e5a0&text_color=8b949e&langs_count=6" alt="Top Languages"/>

</div>

---

<!-- ══════════════ CONTRIBUTION ANIMATIONS ══════════════ -->

## 🐍 Contribution Activity

<div align="center">

![Pacman](https://raw.githubusercontent.com/segunalabi383/segunalabi383/output/pacman-contribution-graph.svg)

</div>

---

<!-- ══════════════ CONNECT ══════════════ -->

## 🤝 Let's build something

<div align="center">

I'm happiest working on **0→1 products**, **AI/LLM platforms** and **real-time systems at scale**.
If that sounds like your roadmap, let's talk.

<a href="mailto:segunalabi383@gmail.com"><img alt="Email me" src="https://img.shields.io/badge/Email%20me-00e5a0?style=for-the-badge&logo=gmail&logoColor=0d1117"/></a>
<a href="https://www.linkedin.com/in/segun-alabi-baa17225"><img alt="Connect on LinkedIn" src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/segunalabi383"><img alt="Follow on GitHub" src="https://img.shields.io/badge/Follow%20on%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://portfolio-segun.vercel.app"><img alt="See portfolio" src="https://img.shields.io/badge/See%20portfolio-0d1117?style=for-the-badge&logo=vercel&logoColor=white"/></a>

<br/><br/>

<img src="./assets/footer.svg" alt="Systems that scale. AI that ships. Impact you can measure." width="100%"/>

</div>
