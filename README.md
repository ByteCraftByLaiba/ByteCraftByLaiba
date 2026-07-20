<div align="center">

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=12&duration=0&pause=0&color=555555&center=true&vCenter=true&repeat=false&width=420&lines=Backend+%26+AI+Systems+Engineer+%E2%80%94+Lahore%2C+Pakistan" />
  <source media="(prefers-color-scheme: light)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=12&duration=0&pause=0&color=999999&center=true&vCenter=true&repeat=false&width=420&lines=Backend+%26+AI+Systems+Engineer+%E2%80%94+Lahore%2C+Pakistan" />
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=12&duration=0&pause=0&color=555555&center=true&vCenter=true&repeat=false&width=420&lines=Backend+%26+AI+Systems+Engineer+%E2%80%94+Lahore%2C+Pakistan" alt="role" />
</picture>

<br/><br/>

# Laiba Shahab

<br/>

*I turn chaos into systems.*

<br/><br/>

<table border="0" cellspacing="0" cellpadding="0">
<tr>
<td align="center" width="180">
<code>4.00 / 4.00</code><br/>
<sub>CGPA · Gold Medalist</sub>
</td>
<td align="center" width="20"><sub>·</sub></td>
<td align="center" width="180">
<code>Rank #1</code><br/>
<sub>Department of CS · UCP</sub>
</td>
<td align="center" width="20"><sub>·</sub></td>
<td align="center" width="180">
<code>Top 3</code><br/>
<sub>Google APAC Scholar · Asia-Pacific</sub>
</td>
</tr>
</table>

<br/><br/>

</div>

---

<br/>

I build backend systems and AI infrastructure that other engineers don't have to think twice about. Not because they're simple, but because the complexity is handled in the right place.

The pattern across every project I've worked on: someone hands me something tangled, a codebase, a workflow, a vague problem, and I find the structure underneath it. Then I build something that makes that structure legible to everyone else.

That's not a methodology. It's just how I approach work.

I wrote architecture diagrams before I wrote code. I treat documentation as part of the engineering, not something that happens after it. I ask what problem we're actually solving before I ask what stack to use.

<br/>

---

<br/>

## Selected Work

<br/>

### SocketSpec &nbsp;·&nbsp; Open Source WebSocket Framework

> WebSocket development had no equivalent to FastAPI. I built one.

Published under Apache 2.0. Decorator-based routing, dependency injection, middleware, authentication primitives, typed event validation, and auto-generated interactive documentation, all designed around the same developer experience that made FastAPI the standard for REST.

The goal was to make building production-grade WebSocket APIs feel as structured and testable as building REST APIs.

**Stack:** Python · WebSockets · Pydantic

[![PyPI](https://img.shields.io/pypi/v/socketspec?style=flat-square&colorA=0d1117&colorB=30363d&label=PyPI)](https://pypi.org/project/socketspec/)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-socketspec-30363d?style=flat-square&colorA=0d1117)](https://github.com/laibaShahab/socketspec)

<br/>

---

<br/>

### SmartML &nbsp;·&nbsp; No-Code AutoML Platform

> Most ML platforms assume you already know ML. SmartML doesn't.

End-to-end AutoML platform for non-technical users: upload a dataset, train across five or more algorithms, tune hyperparameters automatically, and explore SHAP-based explainability reports, without writing a single line of code.

**What it covers:** Authentication · Dataset Management · Preprocessing · Model Training · Explainability · Deployment · AI Assistant · Collaboration · Subscriptions

**The engineering challenge:** SHAP explanations are only useful if non-technical stakeholders understand them. The platform had to be opinionated enough to guide users through a correct ML workflow while staying honest about model limitations instead of hiding them behind confidence scores.

**Stack:** FastAPI · Next.js · PostgreSQL · MongoDB · AWS (EC2, S3, RDS) · scikit-learn · XGBoost · LightGBM · SHAP

[![Live](https://img.shields.io/badge/Live-smartml.tech-30363d?style=flat-square&colorA=0d1117)](https://smartml.tech)

<br/>

---

<br/>

### AI Risk Intelligence Platform &nbsp;·&nbsp; Multi-Tenant Enterprise SaaS

> Enterprise AI adoption fails when there's no infrastructure for accountability. This is what that infrastructure looks like.

Designing and building backend services for a production multi-tenant enterprise risk platform. The hard part isn't the AI, it's the isolation: every tenant gets their own data boundaries, access controls, and audit surface, without duplicating the infrastructure.

**What I own:** RAG pipeline architecture · Multi-agent AI workflows on AWS Bedrock · Tenant isolation via Amazon Cognito · Event-driven processing with SQS and EventBridge · Architecture documentation · Sequence diagrams · API documentation · Requirements collaboration with international clients

**Stack:** FastAPI · Aurora PostgreSQL · pgvector · AWS Bedrock · Amazon ECS · Amazon SQS · EventBridge · Amazon Cognito

<br/>

---

<br/>

### White-Label Delivery Platform &nbsp;·&nbsp; Full Backend as Sole Engineer

> A white-label product means the same codebase has to behave differently for every operator. That complexity has to live somewhere.

Architected and built the complete backend for a multi-tenant delivery platform supporting five distinct user roles across web, Android, and iOS clients: System Admin, Business Admin, Business User, Driver, and POS User.

**Numbers:**
```
40+   REST APIs
10+   Socket.IO events for real-time tracking and driver assignment
15+   PostgreSQL tables spanning the full order lifecycle
 5    user roles with RBAC + PBAC authorization
```

**Stack:** FastAPI · PostgreSQL · Redis · Socket.IO · Docker · APScheduler · Firebase · Resend

<br/>

---

<br/>

### Doctor Appointment Agentic AI System

> LLMs are not reliable by themselves. LangGraph gives you the structure to make them reliable.

LangGraph-based agentic workflow for patient-facing appointment management: scheduling, triage, and RAG-powered contextual responses backed by a FAISS vector database.

**Result:** Above 90% intent recognition accuracy across 8 distinct patient interaction flows during evaluation.

**Stack:** FastAPI · LangGraph · OpenAI API · FAISS · RAG · Hugging Face

[![GitHub](https://img.shields.io/badge/GitHub-repo-30363d?style=flat-square&colorA=0d1117)](https://github.com/laibaShahab)

<br/>

---

<br/>

## Engineering Philosophy

<br/>

```
Understand the system before optimizing it.
```

Most bad rewrites happen because no one read the original carefully. The most useful thing I do in the first week of a new codebase is read it.

<br/>

```
Documentation is part of engineering.
```

If a system is too complex to document, the system has a problem. I write architecture diagrams before I write code because drawing forces precision before you're committed to anything.

<br/>

```
Good software is understandable.
```

Clever is a liability. The most important reader of any code is the engineer fixing it at 2am. Write for them.

<br/>

```
Question the early assumptions.
```

Requirements often describe solutions to problems that were never fully defined. The best time to catch that is before the sprint starts.

<br/>

---

<br/>

## Tech Stack

<br/>

<table>
<tr>
<td valign="top" width="50%">

**Backend**
```
Python · FastAPI · Django · Flask
SQLAlchemy · Alembic · Pydantic
Celery · APScheduler · Async Python
REST · GraphQL · WebSockets · Socket.IO
```

**AI & ML**
```
LangChain · LangGraph · AWS Bedrock
RAG · AI Agents · Vector Search
scikit-learn · XGBoost · LightGBM · SHAP
YOLO · OpenPose · Real-ESRGAN
```

</td>
<td valign="top" width="50%">

**Infrastructure**
```
AWS (Bedrock, ECS, SQS, S3, EventBridge)
Amazon Cognito · Aurora PostgreSQL
Docker · Nginx · GitHub Actions · Linux
```

**Databases**
```
PostgreSQL · pgvector · Redis
MongoDB · Aurora PostgreSQL
```

**Auth**
```
JWT · OAuth2 · AWS Cognito · RBAC · PBAC
```

</td>
</tr>
</table>

<br/>

---

<br/>

## Research

<br/>

**AI & Deep Learning for Sustainable Cloud Security** &nbsp;·&nbsp; *Presented, STEM Conference, Kinnaird College 2025*

Survey of AI-driven cloud security automation and sustainable cloud computing practices.

<br/>

**Enhancing Patterson-Gimlin Footage using Deep Learning & Computer Vision** &nbsp;·&nbsp; *Ongoing*

Applying Real-ESRGAN, YOLOv8, and OpenPose to reconstruct visual clarity and gait patterns from degraded archival footage. Yes, that footage.

<br/>

**The Quantum Threat: A Survey of Post-Quantum Cryptography** &nbsp;·&nbsp; *Ongoing*

Surveying lattice-based, hash-based, and code-based cryptography within the NIST PQC standardization process.

<br/>

---

<br/>

## Recognition

<br/>

<table>
<tr>
<td width="30"><sub>🥇</sub></td>
<td><strong>Gold Medalist</strong> &nbsp;·&nbsp; Department of Computer Science, University of Central Punjab</td>
</tr>
<tr>
<td><sub>#1</sub></td>
<td><strong>Department Rank 1</strong> &nbsp;·&nbsp; CGPA 4.00/4.00 &nbsp;·&nbsp; 100% Merit Scholarship throughout</td>
</tr>
<tr>
<td><sub>🌏</sub></td>
<td><strong>Google Asia-Pacific Generation Scholar 2024</strong> &nbsp;·&nbsp; Selected among top 3 women across the Asia-Pacific region</td>
</tr>
<tr>
<td><sub>🏆</sub></td>
<td><strong>Employee of the Quarter</strong> &nbsp;·&nbsp; Ibtidah Solutions</td>
</tr>
<tr>
<td><sub>⚡</sub></td>
<td><strong>Programming Competition Runner-up</strong> &nbsp;·&nbsp; Techathon 2025 · UCP Olympiad 2024</td>
</tr>
</table>

<br/>

---

<br/>

## GitHub Activity

<br/>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=laibaShahab&show_icons=true&theme=dark&bg_color=0d1117&border_color=30363d&icon_color=666666&title_color=e6edf3&text_color=8b949e&count_private=true&include_all_commits=true" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=laibaShahab&show_icons=true&theme=default&bg_color=ffffff&border_color=d0d7de&icon_color=888888&title_color=1f2328&text_color=636c76&count_private=true&include_all_commits=true" />
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=laibaShahab&show_icons=true&theme=dark&bg_color=0d1117&border_color=30363d&icon_color=666666&title_color=e6edf3&text_color=8b949e&count_private=true&include_all_commits=true" alt="GitHub Stats" />
</picture>

&nbsp;&nbsp;

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=laibaShahab&layout=compact&theme=dark&bg_color=0d1117&border_color=30363d&title_color=e6edf3&text_color=8b949e&langs_count=6&hide=html,css" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=laibaShahab&layout=compact&theme=default&bg_color=ffffff&border_color=d0d7de&title_color=1f2328&text_color=636c76&langs_count=6&hide=html,css" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=laibaShahab&layout=compact&theme=dark&bg_color=0d1117&border_color=30363d&title_color=e6edf3&text_color=8b949e&langs_count=6&hide=html,css" alt="Top Languages" />
</picture>

</div>

<br/>

---

<br/>

## Contact

<br/>

If you're building something hard and you want someone who will actually understand it before touching it, I'm interested in that conversation.

<br/>

`✉` &nbsp;[its.laiba.shahab@gmail.com](mailto:its.laiba.shahab@gmail.com) &nbsp;&nbsp;·&nbsp;&nbsp; `in` &nbsp;[linkedin.com/in/laiba-shahab](https://linkedin.com/in/laiba-shahab) &nbsp;&nbsp;·&nbsp;&nbsp; `⚙` &nbsp;[github.com/laibaShahab](https://github.com/laibaShahab)

<br/>

---

<div align="center">
<br/>
<sub><code>I don't chase technologies. I chase problems. The technologies usually follow.</code></sub>
<br/><br/>
</div>
