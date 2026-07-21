<div align="center">
<img src="./assets/header.svg" alt="laiba(1) — General Commands Manual" width="100%"/>
</div>

<br/>

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1200&color=58A6FF&background=0D111700&center=true&vCenter=true&width=680&lines=turning+chaos+into+systems...;architecture+diagrams%2C+uninvited;documentation+in+the+same+PR+as+the+code;I+don%27t+chase+technologies.+I+chase+problems." alt="typing animation"/>
</div>

<br/>

<div align="center">
<img src="./assets/boot.svg" alt="boot sequence" width="100%"/>
</div>

<br/>

---

## `$ man laiba`

```
LAIBA(1)                    General Commands Manual                   LAIBA(1)

NAME
       laiba — backend and AI systems engineer

SYNOPSIS
       laiba [--backend] [--ai] [--architecture] [--linux]

DESCRIPTION
       Every project follows the same pattern. Too many questions in week
       one. An architecture diagram that nobody requested. Documentation
       next to the code instead of after it, or instead of never.
       By week two, the diagram is the thing the team points to in standup.

       Currently building production services for a delivery platform,
       an AI risk intelligence platform, and a legal AI product.
       Maintains an open source WebSocket framework. Reads more RFC-style
       writing than the job strictly requires.

OPTIONS
       --backend        fastapi · postgresql · redis · distributed systems
       --ai             rag · agentic workflows · bedrock · langgraph
       --architecture   diagrams before decisions, docs before requests
       --linux          daily driver, not a personality trait

EXIT STATUS
       0   ships, documents, moves to the next problem

SEE ALSO
       github.com/laibaShahab · linkedin.com/in/laiba-shahab

LAIBA(1)                                                               LAIBA(1)
```

```
$ cat ~/.identity
```

```
I don't chase technologies.
I chase problems.
The technologies usually follow.
```

---

## `$ neofetch`

<div align="center">
<img src="./assets/neofetch.svg" alt="system information" width="100%"/>
</div>

---

## `$ cat /proc/laiba/pipeline`

<div align="center">
<img src="./assets/architecture.svg" alt="engineering pipeline" width="100%"/>
</div>

---

## `$ lsmod && cat /proc/laiba/brain`

<div align="center">
<img src="./assets/brain.svg" alt="brain architecture" width="100%"/>
</div>

---

## `$ systemctl list-units --type=service`

<details>
<summary><code>● delivero.service</code> &nbsp;—&nbsp; active (running) &nbsp;·&nbsp; white-label delivery platform</summary>
<br/>

Multi-tenant, 5 user roles across web · Android · iOS. Backend owns the full order lifecycle — POS creation through automated driver assignment, live tracking, and completion. 40+ REST APIs, 10+ Socket.IO events, 15+ PostgreSQL tables. RBAC/PBAC auth, Redis caching, APScheduler jobs, Docker.

`fastapi · postgresql · redis · socket.io · docker · firebase`

</details>

<details>
<summary><code>● cadie.service</code> &nbsp;—&nbsp; active (running) &nbsp;·&nbsp; enterprise AI risk intelligence</summary>
<br/>

RAG pipelines and multi-agent workflows on AWS Bedrock. Aurora PostgreSQL + pgvector for retrieval. ECS deployment, SQS + EventBridge for event-driven processing, Cognito for tenant isolation. Also responsible for architecture docs, API docs, and the sequence diagrams the client roadmap runs on.

`fastapi · aurora postgresql · pgvector · bedrock · ecs · sqs · eventbridge · cognito`

</details>

<details>
<summary><code>● lexertia.service</code> &nbsp;—&nbsp; active (running) &nbsp;·&nbsp; enterprise legal AI</summary>
<br/>

Production backend maintenance, report generation, and motion drafting features for enterprise SaaS clients. Cognito-based auth, real-time communication, on-call for the issues that only surface once real clients are in the system.

`fastapi · aws cognito · real-time services`

</details>

<details>
<summary><code>○ backend-automation.service</code> &nbsp;—&nbsp; inactive (exited Feb–May 2026)</summary>
<br/>

Internal tooling and workflow automation in Retool. Shopify + WooCommerce over REST and GraphQL. PostgreSQL pipeline optimization for reporting and analytics across integrated platforms.

`retool · postgresql · shopify api · woocommerce graphql`

</details>

<details>
<summary><code>○ 10pearls-internship.service</code> &nbsp;—&nbsp; inactive (exited Jun–Sep 2025)</summary>
<br/>

XGBoost + LightGBM + CatBoost ensemble for air quality prediction — R² above 0.92. SHAP dashboards for non-technical stakeholders. Automated retraining via GitHub Actions: deployment time from several hours to under 10 minutes.

`xgboost · lightgbm · catboost · shap · github actions`

</details>

---

## `$ apt list --installed`

| package | version | description |
|---|---|---|
| `python` | 3.11 | primary runtime |
| `fastapi` | stable | async REST & WebSocket APIs |
| `postgresql` | 15 / aurora | primary datastore, usually with pgvector loaded |
| `redis` | stable | caching, queues, things that need to be fast |
| `docker` | stable | ships the thing, not just builds it |
| `aws` | bedrock/ecs/sqs/eventbridge/cognito | where production lives |
| `langgraph` | stable | agentic workflows, RAG orchestration |
| `linux` | daily-driver | not a personality trait, just true |
| `system-design` | always-loaded | cannot be unloaded, has been tried |
| `documentation` | always-loaded | see above |
| `overthinking` | optional · frequently active | patch in progress |

<sub>full manifest: Python · SQL · JavaScript/TypeScript · FastAPI · Django · Flask · SQLAlchemy · Alembic · Celery · REST · GraphQL · Socket.IO · WebSockets · JWT · OAuth2 · Cognito · RBAC/PBAC · PostgreSQL · Aurora · Redis · MongoDB · pgvector · AWS (Bedrock · ECS · S3 · SQS · EventBridge) · Docker · Nginx · GitHub Actions · React · Next.js · Tailwind · LLMs · RAG · AI Agents · Vector Search · YOLO · OpenPose · Real-ESRGAN</sub>

---

## `$ systemctl status projects/`

```
● smartml.service — SmartML (Final Year Project)
   Active:  running
   Docs:    smartml.tech
   Stack:   fastapi · next.js · postgresql · mongodb · s3
            scikit-learn · xgboost · lightgbm · shap

   No-code AutoML platform. Upload a dataset, train models,
   read SHAP explainability reports. No code required.
   5+ algorithms, automated hyperparameter tuning, deployed on AWS.
```

```
● doctor-agent.service — Doctor Appointment Agentic AI
   Active:  running (evaluation build)
   Stack:   fastapi · langgraph · openai api · faiss · rag

   LangGraph agentic workflow: scheduling, triage, RAG-backed
   patient Q&A over a FAISS vector store.
   Result: >90% intent recognition across 8 interaction flows.
```

---

## `$ apt-cache show socketspec`

```
Package:      socketspec
Version:      stable
License:      Apache-2.0
Description:  A FastAPI-flavored WebSocket framework.
              Decorator routing · dependency injection · middleware
              typed event validation · auth primitives · interactive docs
              For people who don't want to reinvent WebSocket auth again.

Homepage:     github.com/laibaShahab/socketspec
Registry:     pypi.org/project/socketspec
Docs:         socketspec.dev
```

[![GitHub](https://img.shields.io/badge/GitHub-socketspec-24292e?style=flat-square&logo=github&logoColor=white)](https://github.com/laibaShahab/socketspec)
[![PyPI](https://img.shields.io/badge/PyPI-socketspec-3775A9?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/socketspec)
[![License](https://img.shields.io/badge/license-Apache--2.0-D9534F?style=flat-square)](https://github.com/laibaShahab/socketspec/blob/main/LICENSE)

---

## `$ cat /etc/laiba/engineering.conf`

```ini
[core]
documentation           = true
architecture_first      = true
question_assumptions    = true
problem_driven_learning = true
technology_as_identity  = false

[design]
simplicity_over_cleverness = true
single_source_of_truth     = true
premature_optimization     = disabled

[behavior]
ships_without_docs = never
```

---

## `$ cat /var/log/known_bugs.log`

```
known_bugs:
  - documentation.service starts before anyone files the ticket
  - will produce an architecture diagram for a two-line change
  - can lose 40 minutes to a naming discussion, considers it time well spent
  - occasionally becomes the de facto team wiki without applying for the role
  - reads RFCs for fun — flagged, no fix scheduled

status: won't_fix
```

---

## `$ ls -la research/`

<details>
<summary><code>ai-cloud-security.pdf</code> — presented at STEM Conference, Kinnaird College 2025</summary>
<br/>

Surveys AI-driven cloud security automation alongside sustainable cloud computing practices — where the two goals reinforce each other and where they trade off.
</details>

<details>
<summary><code>patterson-gimlin-restoration.pdf</code> — ongoing</summary>
<br/>

Applying Real-ESRGAN, YOLOv8, and OpenPose to reconstruct visual clarity and gait patterns from degraded archival footage. A computer vision problem wearing a cryptid costume.
</details>

<details>
<summary><code>quantum-threat-pqc-survey.pdf</code> — ongoing</summary>
<br/>

Survey of lattice-based, hash-based, and code-based cryptography within the NIST PQC standardization and migration process.
</details>

---

## `$ journalctl -u laiba --since "2022-01-01"`

```
[SUCCESS]  gold medalist · dept rank #1 · cgpa 4.00/4.00
[SUCCESS]  selected — google asia-pacific generation scholar · top 3 women, apac
[SUCCESS]  employee of the quarter · ibtidah solutions
[SUCCESS]  runner-up · techathon 2025 + ucp olympiad 2024
[INFO]     research presented · stem conference, kinnaird college 2025
[INFO]     architecture diagram drawn, no one had requested one
[INFO]     documentation published, team stopped asking "how does this work"
[INFO]     production deployed, docs shipped in the same PR
[INFO]     root cause of "it's broken" traced to npm run dev, again
```

---

## `$ grafana --dashboard=github-stats`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=laibaShahab&show_icons=true&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=f0883e&text_color=c9d1d9&ring_color=30363d" height="165" alt="github stats"/>
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=laibaShahab&layout=compact&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" height="165" alt="top languages"/>

<br/>

<img src="https://github-readme-streak-stats.demolab.com?user=laibaShahab&hide_border=true&background=0D1117&ring=58A6FF&fire=F0883E&currStreakLabel=58A6FF&sideLabels=C9D1D9&dates=C9D1D9&sideNums=C9D1D9&currStreakNum=58A6FF" height="165" alt="streak stats"/>

</div>

---

## `$ connect laiba`

```
Email       its.laiba.shahab@gmail.com
GitHub      github.com/laibaShahab
LinkedIn    linkedin.com/in/laiba-shahab
Location    Lahore, Pakistan

Status      open to backend, AI infrastructure, and distributed
            systems problems — especially the kind that come with
            an architecture diagram someone already got wrong.
```

<div align="center">

[![Email](https://img.shields.io/badge/Gmail-its.laiba.shahab%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:its.laiba.shahab@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-laiba--shahab-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/laiba-shahab)
[![GitHub](https://img.shields.io/badge/GitHub-laibaShahab-24292e?style=flat-square&logo=github&logoColor=white)](https://github.com/laibaShahab)

</div>

---

## `$ shutdown now`

```
Stopping backend.service...              done
Stopping ai.service...                   done
Saving architecture diagrams...          done
Saving documentation...                  done (it was already saved)

System halted.
```

<div align="center">

<br/>

*I don't chase technologies.*
*I chase problems.*
*The technologies usually follow.*

<br/>

<sub>LAIBA(1)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;General Commands Manual&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;LAIBA(1)</sub>

</div>
