<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:7D2A26,100:D97757&height=170&section=header&text=Keerat%20Singh%20Jaggi&fontSize=48&fontColor=ffffff&fontAlignY=38&animation=fadeIn" alt="Keerat Singh Jaggi">

<h3 align="center">B.Tech CSE — Artificial Intelligence &amp; Machine Learning · VIT Bhopal '29</h3>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=2600&pause=900&color=D97757&center=true&vCenter=true&width=600&lines=SQL+%7C+Python+%7C+Data+Analysis;Relational+database+design;Turning+curiosity+into+code" alt="Typing SVG">
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/keerat-singh-jaggi-a55a15384">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:singhjaggikeerat@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

---

### About

- Second-year CSE undergraduate specializing in **AI & Machine Learning** at VIT Bhopal.
- Most of my work so far is **SQL and data analysis** — query writing, relational schema design, and pulling operational insight out of messy tables.
- Currently working through **machine learning fundamentals** so my ML projects are as solid as my SQL ones.
- Certified in **Microsoft Transact-SQL (DP-080)**, and completing an **AI & Data Science program from IIT Roorkee** via Intellipaat.

---

### Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,mysql,c,cpp,java,docker,git,vscode&theme=dark" alt="Tech stack">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" alt="SQL Server">
  <img src="https://img.shields.io/badge/Azure%20SQL%20Edge-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure SQL Edge">
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
</p>

---

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&duration=3000&pause=1200&color=7D2A26&center=true&vCenter=true&width=460&lines=Featured+Work;Click+a+panel+to+expand" alt="Featured Work">
</p>

<br>

<details>
<summary>
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:7D2A26,100:D97757&height=80&section=header&text=Uber%20Operational%20Data%20Analysis&fontSize=30&fontColor=ffffff&fontAlignY=56" alt="">
  <p align="center"><i>52.21% cancellations &nbsp;·&nbsp; $16,777 revenue leakage</i></p>
</summary>

<br>

<img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white">
<img src="https://img.shields.io/badge/Azure%20SQL%20Edge-0078D4?style=flat-square&logo=microsoftazure&logoColor=white">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">

**The question:** where is Uber losing money and riders across its rides, payments, drivers and cities?

**What I built:** 10 structured SQL scripts covering cleaning, aggregation and reporting, running on SQL Server via Azure SQL Edge in Docker.

**What I found:**

| Metric | Result |
|---|---|
| Ride cancellation rate | **52.21%** — more rides cancelled than completed |
| Revenue leakage | **35.23%** — $16,777 lost to failed payments |
| Workload | Critical imbalance concentrated in North Michaelberg |

**Techniques:** reporting views · performance indexes · audit triggers · `CASE` categorisation · date functions for month-on-month trends

<a href="https://github.com/keeratcodes/analysis-of-ubers-operationaldata-sql-lab"><b>Open the repository →</b></a>

</details>

<details>
<summary>
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:0B3D91,100:1E88E5&height=80&section=header&text=AdventureWorks%20SQL%20Analysis&fontSize=30&fontColor=ffffff&fontAlignY=56" alt="">
  <p align="center"><i>Enterprise database querying</i></p>
</summary>

<br>

<img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white">
<img src="https://img.shields.io/badge/T--SQL-0078D4?style=flat-square&logo=microsoftsqlserver&logoColor=white">

**The database:** Microsoft's AdventureWorks2012 — a full enterprise sample schema covering sales, customers and products.

**What I wrote:** multi-table joins, aggregations and date-function queries spanning all three schemas.

**What it produces:** revenue totals, monthly sales trends, and customer lifetime value breakdowns that rank customers and products by contribution.

<a href="https://github.com/keeratcodes/adventureworks-sql-lab"><b>Open the repository →</b></a>

</details>

<details>
<summary>
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:4A148C,100:9C27B0&height=80&section=header&text=Relational%20Schema%20Design&fontSize=30&fontColor=ffffff&fontAlignY=56" alt="">
  <p align="center"><i>ER diagram to SQL Server DDL</i></p>
</summary>

<br>

<img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white">
<img src="https://img.shields.io/badge/Database%20Design-7D2A26?style=flat-square">

**The exercise:** take an ER diagram and turn it into a working, constraint-safe SQL Server database.

**The schema — 5 tables:**

| Table | Purpose |
|---|---|
| `role` | User role types — Admin, Editor, and so on |
| `user_account` | Login credentials |
| `status` | Status type definitions |
| `user_has_role` | Junction table linking users to roles, with timestamps |
| `user_has_status` | Junction table linking users to statuses, with timestamps |

**What it demonstrates:** primary and foreign key constraints across every relation, and referential integrity validated through constraint-ordered inserts and deletes.

<a href="https://github.com/keeratcodes/user-roles-sql"><b>Open the repository →</b></a>

</details>

<details>
<summary>
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:1B5E20,100:66BB6A&height=80&section=header&text=ECO-TWIN%20Punjab%20%7C%20SIH25009&fontSize=30&fontColor=ffffff&fontAlignY=56" alt="">
  <p align="center"><i>Private &nbsp;·&nbsp; in progress</i></p>
</summary>

<br>

<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black">
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
<img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white">

**The brief:** Smart India Hackathon problem statement SIH25009, set by the Government of Punjab under the Smart Education theme.

**The idea:** a gamified environmental decision-simulator built around the **Panj Tattva** — the five elements of Water, Air, Land, Energy and Biodiversity — where players see the downstream consequences of environmental choices.

**My role:** concept, domain research and product design within a 6-member team. I compiled Punjab-specific water, land and air data into a fully cited reference set, on the rule that no figure enters the product unless it can be sourced, and scoped Water as the flagship module.

**Status:** private repository, in active development.

</details>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:D97757,100:7D2A26&height=110&section=footer" alt="">
