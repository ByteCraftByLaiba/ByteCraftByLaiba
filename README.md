<div align="center">
<img src="./assets/header.svg" alt="laiba(1) — General Commands Manual" width="100%"/>
</div>

<br/>

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1200&color=58A6FF&background=0D111700&center=true&vCenter=true&width=700&lines=turning+chaos+into+systems...;documentation.service%3A+always-on;architecture+diagrams%2C+uninvited;I+don't+chase+technologies.+I+chase+problems." alt="typing animation"/>
</div>

<br/>

<div align="center">
<img src="./assets/boot.svg" alt="boot sequence" width="100%"/>
</div>

<br/>

## SYNOPSIS

```
$ neofetch
```

<div align="center">
<img src="./assets/neofetch.svg" alt="system information" width="100%"/>
</div>

<br/>

## DESCRIPTION

```
$ whoami
```

Every project I join follows the same pattern. I ask a few too many questions in the first week. An architecture diagram appears that nobody explicitly asked for. Documentation shows up next to the code instead of after it, or instead of never. By the second week, the diagram is the thing the team points to in stand-up.

I don't set out to do this. It's just what happens when I try to understand a system well enough to change it safely.

I'm a backend and AI systems engineer working across FastAPI, PostgreSQL, and AWS, currently building production services for a delivery platform, an AI risk intelligence platform, and a legal AI product. I also maintain an open source WebSocket framework and read more RFC-style writing than is strictly necessary for the job.

```
$ cat ~/.identity
```

```
I don't chase technologies.
I chase problems.
The technologies usually follow.
```

<br/>

## SYSTEM ARCHITECTURE

```
$ cat /proc/laiba/pipeline
```

<div align="center">
<img src="./assets/architecture.svg" alt="engineering pipeline" width="100%"/>
</div>

<br/>

## LSMOD — LOADED MODULES

```
$ cat /proc/laiba/brain
```

<div align="center">
<img src="./assets/brain.svg" alt="brain architecture" width="100%"/>
</div>

<br/>

## PACKAGE MANAGEMENT

```
$ apt list --installed
```

| package | version | description |
|---|---|---|
| `python` | 3.11 | primary runtime |
| `fastapi` | stable | async REST & WebSocket APIs |
| `postgresql` | 15 / aurora | primary datastore, usually with pgvector loaded |
| `redis` | stable | caching, queues, things that need to be fast |
| `docker` | stable | ships the thing, not just builds it |
| `aws` | bedrock/ecs/sqs/eventbridge/cognito | where production actually lives |
| `langgraph` | stable | agentic workflows, RAG orchestration |
| `linux` | daily-driver | not a personality trait, just true |
| `system-design` | always-loaded | cannot be unloaded, has been tried |
| `documentation` | always-loaded | see above |
| `overthinking` | optional, frequently active | working on a patch |

<sub>full manifest: Python, SQL, JavaScript/TypeScript · FastAPI, Django, Flask, SQLAlchemy, Celery · REST, GraphQL, Socket.IO, WebSockets · JWT, OAuth2, Cognito, RBAC/PBAC · PostgreSQL, Aurora, Redis, MongoDB, pgvector · AWS (Bedrock, ECS, S3, SQS, EventBridge), Docker, Nginx, GitHub Actions · React, Next.js, Tailwind · LLMs, RAG, AI Agents, Vector Search, YOLO, OpenPose, Real-ESRGAN</sub>

<br/>

## RUNNING SERVICES

```
$ systemctl list-units --type=service
```

<details>
<summary><code>● delivero.service</code> — loaded, active (running)</summary>
<br/>

```
Loaded:   yes
Status:   running (production)
Purpose:  white-label, multi-tenant delivery platform
Clients:  web · android (kotlin) · ios (swift)
Roles:    system-admin · business-admin · business-user · driver · pos-user
```

Owns the backend end to end: order lifecycle from POS creation through automated driver assignment, live tracking, and completion. 40+ REST APIs, 10+ Socket.IO events, 15+ PostgreSQL tables. RBAC/PBAC authorization, Redis caching, APScheduler jobs, containerized with Docker, notifications via Resend and Firebase.

`stack: fastapi · postgresql · redis · docker · socket.io`

</details>

<details>
<summary><code>● cadie.service</code> — loaded, active (running)</summary>
<br/>

```
Loaded:   yes
Status:   running (production)
Purpose:  multi-tenant enterprise AI risk intelligence platform
```

RAG pipelines and multi-agent workflows on AWS Bedrock, deployed on ECS with SQS and EventBridge handling event-driven processing. Aurora PostgreSQL with pgvector for retrieval. Tenant isolation via Cognito. Also responsible for architecture docs, API docs, and the sequence diagrams the client roadmap runs on.

`stack: fastapi · aurora postgresql · pgvector · bedrock · ecs · sqs · eventbridge · cognito`

</details>

<details>
<summary><code>● lexertia.service</code> — loaded, active (running)</summary>
<br/>

```
Loaded:   yes
Status:   running (production)
Purpose:  enterprise legal AI platform
```

Maintaining and extending production backend services, including Cognito-based auth. Shipped report generation and motion drafting features. On call for the issues that only show up once real clients are using the thing.

`stack: fastapi · aws cognito · real-time services`

</details>

<details>
<summary><code>● backend-automation.service</code> — loaded, inactive (exited, Feb–May 2026)</summary>
<br/>

```
Loaded:   yes
Status:   exited (0)
Purpose:  internal tooling & workflow automation
```

Designed internal business applications in Retool, wired into Shopify and WooCommerce over REST and GraphQL. Optimized PostgreSQL pipelines for reporting and analytics, automated recurring inventory and customer workflows.

`stack: retool · postgresql · shopify api · woocommerce api`

</details>

<details>
<summary><code>● 10pearls-internship.service</code> — loaded, inactive (exited, Jun–Sep 2025)</summary>
<br/>

```
Loaded:   yes
Status:   exited (0)
Purpose:  air quality prediction
```

Ensemble of XGBoost, LightGBM, and CatBoost, R² above 0.92. Built SHAP dashboards so non-technical stakeholders could see why the model believed what it believed. Automated retraining and deployment through GitHub Actions, cutting deploy time from hours to under 10 minutes.

`stack: xgboost · lightgbm · catboost · shap · github actions`

</details>

<br/>

## PROJECT REGISTRY

```
$ systemctl status smartml.service
```

```
● smartml.service — SmartML (Final Year Project)
   Loaded: yes
   Active: running
   Docs:   smartml.tech

   Purpose: no-code AutoML platform. Upload a dataset, train a model,
            read a SHAP explainability report. No code required.

   Modules:
     ✓ auth              ✓ dataset management     ✓ training
     ✓ explainability     ✓ ai assistant           ✓ deployment
     ✓ collaboration      ✓ subscriptions

   Stack: fastapi · next.js · postgresql · mongodb · s3
          scikit-learn · xgboost · lightgbm · shap

   Notes: 5+ algorithms, automated hyperparameter tuning,
          deployed on EC2/S3/RDS.
```

```
$ systemctl status doctor-agent.service
```

```
● doctor-agent.service — Doctor Appointment Agentic AI
   Loaded: yes
   Active: running (evaluation build)

   Purpose: LangGraph agentic workflow for scheduling, triage,
            and RAG-backed patient Q&A over a FAISS vector store.

   Result: >90% intent recognition across 8 interaction flows.

   Stack: fastapi · langgraph · openai api · faiss · rag
```

<br/>

## OPEN SOURCE

```
$ apt-cache show socketspec
```

```
Package:      socketspec
Version:      stable
License:      Apache-2.0
Description:  a FastAPI-flavored WebSocket framework — decorator
              routing, dependency injection, middleware, typed
              event validation, and docs generation for people who
              don't want to reinvent auth for the third time.

Homepage:     github.com/laibaShahab/socketspec
Registry:     pypi.org/project/socketspec
```

<br/>

## ENGINEERING PRINCIPLES

```
$ cat /etc/laiba/engineering.conf
```

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

<br/>

## KNOWN BUGS

```
$ cat /var/log/known_bugs.log
```

```
known_bugs:
  - documentation.service starts before anyone files the ticket
  - will produce an architecture diagram for a two-line change
  - can lose 40 minutes to a naming discussion and consider it time well spent
  - occasionally becomes the de facto team wiki without applying for the role
  - reads RFCs for fun, this has been flagged, no fix scheduled

status: won't_fix
```

<br/>

## SYSTEM LOGS

```
$ journalctl -u laiba --since "2022-01-01"
```

```
[INFO]    joined project, asked more questions than expected
[INFO]    architecture diagram drawn, no one had requested one
[INFO]    documentation published, team stopped asking "how does this work"
[SUCCESS] gold medalist, dept rank #1, cgpa 4.00/4.00
[SUCCESS] selected — google asia-pacific generation scholar, top 3 (women), apac
[SUCCESS] employee of the quarter, ibtidah solutions
[INFO]    research presented, stem conference, kinnaird college
[SUCCESS] runner-up, techathon 2025 and ucp olympiad 2024
[INFO]    root cause of "it's broken" traced to npm run dev, again
[SUCCESS] production deployed, docs shipped in the same PR
```

<br/>

## RESEARCH

```
$ ls -la research/
```

<details>
<summary><code>ai-deep-learning-sustainable-cloud-security.pdf</code></summary>
<br/>

Presented at the STEM Conference, Kinnaird College. Surveys AI-driven cloud security automation alongside sustainable cloud computing practices, looking at where the two goals reinforce each other and where they trade off.
</details>

<details>
<summary><code>patterson-gimlin-footage-restoration.pdf</code> <sub>(ongoing)</sub></summary>
<br/>

Applying Real-ESRGAN, YOLOv8, and OpenPose to reconstruct visual clarity and gait patterns from degraded archival footage. A computer vision problem wearing a cryptid costume.
</details>

<details>
<summary><code>quantum-threat-pqc-survey.pdf</code> <sub>(ongoing)</sub></summary>
<br/>

A survey of lattice-based, hash-based, and code-based cryptography within the NIST PQC standardization and migration process.
</details>

<br/>

## ACHIEVEMENTS

```
$ cat /var/log/achievements.log
```

```
[GOLD MEDAL]     Dept. of Computer Science, University of Central Punjab
[RANK #1]        Department Rank #1 — CGPA 4.00 / 4.00
[SCHOLARSHIP]    100% Merit Scholarship, full undergraduate duration
[SCHOLAR]        Google Asia-Pacific Generation Scholar, 2024
                 (Top 3 women, Asia-Pacific region)
[AWARD]          Employee of the Quarter, Ibtidah Solutions
[COMPETITION]    Runner-up, Techathon 2025
[COMPETITION]    Runner-up, UCP Olympiad 2024
[PRESENTER]      STEM Conference, Kinnaird College, 2025
```

<br/>

## MONITORING DASHBOARD

```
$ grafana --dashboard=github-stats
```

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=laibaShahab&show_icons=true&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=f0883e&text_color=c9d1d9&ring_color=30363d" alt="github stats" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=laibaShahab&layout=compact&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" alt="top languages" height="165"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=laibaShahab&hide_border=true&background=0D1117&ring=58A6FF&fire=F0883E&currStreakLabel=58A6FF" alt="streak stats" height="165"/>

</div>

<br/>

## CONNECT

```
$ connect laiba
```

```
Email       its.laiba.shahab@gmail.com
GitHub      github.com/laibaShahab
LinkedIn    linkedin.com/in/laiba-shahab

Status      open to backend, AI infrastructure, and system design
            problems, especially the kind that come with an
            architecture diagram someone already got wrong.
```

<br/>

## SHUTDOWN

```
$ shutdown now
```

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

<sub>LAIBA(1)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;LAIBA(1)</sub>

</div>
