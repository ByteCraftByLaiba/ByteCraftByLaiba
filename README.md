<div align="center">

```
$ whoami
```

# laiba shahab
### backend engineer · AI infrastructure · distributed systems

*Gold Medalist · CGPA 4.00/4.00 · Google APAC Scholar (Top 3)*

[![Email](https://img.shields.io/badge/email-its.laiba.shahab%40gmail.com-58a6ff?style=flat-square&logo=gmail&logoColor=white)](mailto:its.laiba.shahab@gmail.com)
[![LinkedIn](https://img.shields.io/badge/linkedin-laiba--shahab-58a6ff?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/laiba-shahab)
[![PyPI](https://img.shields.io/badge/pypi-socketspec-f0883e?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/socketspec)

</div>

---

```python
class Laiba:
    role     = "Backend & AI Infrastructure Engineer"
    location = "Lahore, Pakistan 🇵🇰"
    now      = ["delivery platform", "AI risk intelligence", "legal AI — all in production"]
    mantra   = "I don't chase technologies. I chase problems."
    known_bugs = [
        "draws architecture diagrams before anyone asks",
        "documentation ships in the same PR as the code",
        "cannot leave a naming inconsistency alone",
        "reads RFCs for fun — no fix scheduled",
    ]
```

---

## `$ systemctl list-units --running`

| service | stack | status |
|---|---|---|
| **Delivero** · white-label delivery platform | FastAPI · PostgreSQL · Redis · Socket.IO | 🟢 running |
| **Cadie** · enterprise AI risk platform | Bedrock · Aurora+pgvector · ECS · SQS | 🟢 running |
| **Lexertia** · enterprise legal AI | FastAPI · Cognito · real-time services | 🟢 running |

<details>
<summary><code>→ expand Delivero</code></summary>
<br/>

Multi-tenant, 5 user roles (System Admin → POS User), runs across web + Android + iOS. I own the backend end-to-end: 40+ REST APIs, 10+ Socket.IO events, full order lifecycle from POS creation through driver assignment and live tracking. RBAC/PBAC, Redis caching, APScheduler, Docker.

</details>

<details>
<summary><code>→ expand Cadie</code></summary>
<br/>

RAG pipelines + multi-agent workflows on AWS Bedrock. Aurora PostgreSQL with pgvector for retrieval. ECS deployment, SQS + EventBridge for event-driven processing, Cognito for tenant isolation. Also responsible for the architecture docs and sequence diagrams the client roadmap runs on.

</details>

---

## `$ apt-cache show socketspec`

> An open source WebSocket framework with a FastAPI-inspired DX — decorator routing, typed event validation, dependency injection, middleware, auth primitives, and interactive docs. Because nobody should have to reinvent WebSocket auth a third time.

```python
@app.on("order.updated")
async def handle(data: OrderSchema, conn: Connection):
    await conn.emit("driver.notified", {"order_id": data.id})
```

[**→ github**](https://github.com/laibaShahab/socketspec) · [**→ pypi**](https://pypi.org/project/socketspec) · [**→ docs**](https://socketspec.dev) · `Apache-2.0`

---

## `$ ls projects/`

**[SmartML](https://smartml.tech)** — no-code AutoML platform *(FYP)*
Upload a dataset. Train models. Read SHAP explainability reports. No code required.
`FastAPI · Next.js · PostgreSQL · AWS · scikit-learn · XGBoost`

**[Doctor Appointment Agent](https://github.com/laibaShahab)** — LangGraph agentic AI
Scheduling, triage, RAG-backed Q&A over FAISS. >90% intent accuracy across 8 flows.
`FastAPI · LangGraph · OpenAI · FAISS · RAG`

---

## `$ lsmod`

```
Languages    Python · SQL · TypeScript
Backend      FastAPI · Django · Flask · SQLAlchemy · Celery · WebSockets · GraphQL
Databases    PostgreSQL · Aurora · Redis · MongoDB · pgvector
Cloud        AWS Bedrock · ECS · S3 · SQS · EventBridge · Cognito
AI           LLMs · RAG · LangGraph · AI Agents · XGBoost · YOLO · Real-ESRGAN
Auth         JWT · OAuth2 · Cognito · RBAC · PBAC
DevOps       Docker · GitHub Actions · Nginx · Linux
```

---

## `$ journalctl --highlights`

```
[SUCCESS]  gold medal · dept rank #1 · cgpa 4.00/4.00
[SUCCESS]  google asia-pacific generation scholar 2024 — top 3 women, apac
[SUCCESS]  employee of the quarter · ibtidah solutions
[SUCCESS]  runner-up · techathon 2025 + ucp olympiad 2024
[INFO]     research presented · stem conference, kinnaird college 2025
[INFO]     ongoing: post-quantum cryptography survey (nist pqc)
[INFO]     ongoing: restoring degraded archival footage with real-esrgan + yolov8
             (it's a computer vision problem wearing a cryptid costume)
```

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=laibaShahab&show_icons=true&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=f0883e&text_color=c9d1d9" height="150"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=laibaShahab&layout=compact&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" height="150"/>

<br/><br/>

*I don't chase technologies. I chase problems.*
*The technologies usually follow.*

</div>
