<h1 align="center">Hi, I'm Heet</h1>
<p align="center">I build systems: distributed backends, infra tooling, and the occasional analytics platform, then make sure they actually run in production.</p>

<p align="center">
  <a href="https://www.linkedin.com/in/heet-mehta-41b862225"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:mehtaheet5@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-mehtaheet5%40gmail.com-6d28d9?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://heet852003.github.io/My-Portfolio/"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-Visit-16a34a?style=for-the-badge&logo=googlechrome&logoColor=white"></a>
</p>

I like taking a system apart to understand exactly how it fails, then
building the version that doesn't: queues that survive a crashed worker,
dashboards that update in real time instead of on refresh, infra that
tells you what's actually wrong instead of just that something is.
Most of what's below started as "I wonder how that actually works
under the hood."

---

## Skills & Stack

**Languages**

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-CB171E?style=for-the-badge&logo=yaml&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)

**Infrastructure & platforms**

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![Bazel](https://img.shields.io/badge/Bazel-43A047?style=for-the-badge&logo=bazel&logoColor=white)
![Google Cloud](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Heroku](https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white)

**Observability**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![VictoriaMetrics](https://img.shields.io/badge/VictoriaMetrics-621773?style=for-the-badge&logo=victoriametrics&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

**Web & data**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FCA121?style=for-the-badge&logo=gitlab&logoColor=white)

---

## Featured projects

<table>
<tr>
<td width="15%" align="center" valign="middle">
<img src="https://raw.githubusercontent.com/Heet852003/aegis/main/docs/assets/logo.svg" width="56" alt="Aegis logo" />
</td>
<td width="85%" valign="top">

**[Aegis](https://github.com/Heet852003/aegis)**: distributed job queue and DAG workflow engine

A from-scratch Celery/Temporal alternative: atomic job leasing, retries
with backoff and jitter, dead-letter queues, a reactive DAG engine, and
Postgres-advisory-lock leader election for HA. Go engine, React
dashboard, Go + Python worker SDKs, one binary.

![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Postgres](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

</td>
</tr>
<tr>
<td width="15%" align="center" valign="middle">
<img src="https://raw.githubusercontent.com/Heet852003/InsightBoard/master/frontend/dashboard/public/logo.svg" width="56" alt="InsightBoard logo" />
</td>
<td width="85%" valign="top">

**[InsightBoard](https://github.com/Heet852003/InsightBoard)**: self-hosted product analytics

A Mixpanel-style stack: a tracking SDK, a FastAPI ingestion API, a Kafka
to ClickHouse pipeline for event aggregation, and a React dashboard for
funnels, heatmaps, and custom boards.

![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Kafka](https://img.shields.io/badge/-Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![ClickHouse](https://img.shields.io/badge/-ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)

</td>
</tr>
<tr>
<td width="15%" align="center" valign="middle">
<img src="https://raw.githubusercontent.com/Heet852003/SentryFlow/main/docs/logo.svg" width="56" alt="SentryFlow logo" />
</td>
<td width="85%" valign="top">

**[SentryFlow](https://github.com/Heet852003/SentryFlow)**: API gateway with rate limiting and analytics

Sits in front of an API: authenticates by key, enforces sliding-window
and token-bucket rate limits, and streams request logs through Kafka
into ClickHouse for usage analytics.

![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

</td>
</tr>
<tr>
<td width="15%" align="center" valign="middle">
<img src="https://raw.githubusercontent.com/Heet852003/ethvault/main/public/ethvault-logo.svg" width="56" alt="ETHVault logo" />
</td>
<td width="85%" valign="top">

**[ETHVault](https://github.com/Heet852003/ethvault)**: Ethereum staking and governance platform

Deposit ETH for a receipt token, stake it for a second token, earn
rewards, and vote on governance proposals, four Solidity contracts
behind a Next.js frontend.

![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Solidity](https://img.shields.io/badge/-Solidity-363636?style=flat-square&logo=solidity&logoColor=white)

</td>
</tr>
<tr>
<td width="15%" align="center" valign="middle">
<img src="https://raw.githubusercontent.com/Heet852003/sift/main/docs/assets/logo.svg" width="56" alt="Sift logo" />
</td>
<td width="85%" valign="top">

**[Sift](https://github.com/Heet852003/sift)**: self-hosted, multi-repository code search engine

A trigram index (the technique behind Google Code Search and Zoekt)
derived from arbitrary regex patterns via Go's own AST parser, plus
per-language symbol extraction so definitions rank above incidental
text matches. Fuzz-tested against the invariant that it never misses
a true match.

![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

</td>
</tr>
</table>

More on my [GitHub profile](https://github.com/Heet852003?tab=repositories):
a symbolic-music scaling-laws experiment, an HTLC atomic-swap protocol
simulator with a short paper, an Ethereum auction house, and a diabetic
retinopathy screening app among them.

---

Full contribution history and activity graph are on this profile page,
right below this README.
