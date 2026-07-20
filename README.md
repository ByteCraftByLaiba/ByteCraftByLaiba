<div align="center">

![banner](https://capsule-render.vercel.app/api?type=waving&color=0d1117&height=200&section=header&text=Laiba%20Shahab&fontSize=48&fontColor=e6edf3&fontAlignY=55&fontAlign=50&desc=Backend%20%26%20AI%20Systems%20Engineer&descAlignY=75&descAlign=50&descColor=8b949e&descSize=16&animation=fadeIn)

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=14&duration=4000&pause=1000&color=888888&center=true&vCenter=true&width=600&lines=I+turn+chaos+into+systems.;I+don%27t+chase+technologies.+I+chase+problems.;The+technologies+usually+follow." alt="Typing SVG" />

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

I write architecture diagrams before I write code. I treat documentation as part of the engineering, not something that happens after it. I ask what problem we're actually solving before I ask what stack to use.

<br/>

---

<br/>

## Selected Work

<br/>

### SocketSpec &nbsp;·&nbsp; Open Source WebSocket Framework

> WebSocket development had no equivalent to FastAPI. I built one.

Published under Apache 2.0. Decorator-based routing, dependency injection, middleware, authentication primitives, typed event validation, and auto-generated interactive documentation — all designed around the same developer experience that made FastAPI the standard for REST.

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

End-to-end AutoML platform for non-technical users: upload a dataset, train across five or more algorithms, tune hyperparameters automatically, and explore SHAP-based explainability reports — without writing a single line of code.

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

**🐍 Languages**

![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=3776AB)
![TypeScript](https://img.shields.io/badge/TypeScript-0d1117?style=flat-square&logo=typescript&logoColor=3178C6)
![JavaScript](https://img.shields.io/badge/JavaScript-0d1117?style=flat-square&logo=javascript&logoColor=F7DF1E)
![SQL](https://img.shields.io/badge/SQL-0d1117?style=flat-square&logo=postgresql&logoColor=8b949e)

<br/>

**⚙️ Backend**

![FastAPI](https://img.shields.io/badge/FastAPI-0d1117?style=flat-square&logo=fastapi&logoColor=009688)
![Django](https://img.shields.io/badge/Django-0d1117?style=flat-square&logo=django&logoColor=092E20)
![Flask](https://img.shields.io/badge/Flask-0d1117?style=flat-square&logo=flask&logoColor=ffffff)
![Pydantic](https://img.shields.io/badge/Pydantic-0d1117?style=flat-square&logo=pydantic&logoColor=E92063)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-0d1117?style=flat-square&logo=sqlalchemy&logoColor=D71F00)
![Celery](https://img.shields.io/badge/Celery-0d1117?style=flat-square&logo=celery&logoColor=37814A)
![Socket.IO](https://img.shields.io/badge/Socket.IO-0d1117?style=flat-square&logo=socketdotio&logoColor=ffffff)
![GraphQL](https://img.shields.io/badge/GraphQL-0d1117?style=flat-square&logo=graphql&logoColor=E10098)

<br/>

**🤖 AI & ML**

![LangChain](https://img.shields.io/badge/LangChain-0d1117?style=flat-square&logo=langchain&logoColor=1C3C3C)
![AWS Bedrock](https://img.shields.io/badge/AWS_Bedrock-0d1117?style=flat-square&logo=amazonaws&logoColor=FF9900)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0d1117?style=flat-square&logo=scikitlearn&logoColor=F7931E)
![XGBoost](https://img.shields.io/badge/XGBoost-0d1117?style=flat-square&logo=xgboost&logoColor=189fdd)
![OpenAI](https://img.shields.io/badge/OpenAI-0d1117?style=flat-square&logo=openai&logoColor=ffffff)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-0d1117?style=flat-square&logo=huggingface&logoColor=FFD21E)
![YOLO](https://img.shields.io/badge/YOLO-0d1117?style=flat-square&logo=yolo&logoColor=00FFFF)

<br/>

**🗄️ Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=4169E1)
![MongoDB](https://img.shields.io/badge/MongoDB-0d1117?style=flat-square&logo=mongodb&logoColor=47A248)
![Redis](https://img.shields.io/badge/Redis-0d1117?style=flat-square&logo=redis&logoColor=FF4438)
![Aurora](https://img.shields.io/badge/Aurora_PostgreSQL-0d1117?style=flat-square&logo=amazonaws&logoColor=FF9900)

<br/>

**☁️ Cloud & Infrastructure**

![AWS](https://img.shields.io/badge/AWS-0d1117?style=flat-square&logo=amazonaws&logoColor=FF9900)
![Docker](https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=2496ED)
![Linux](https://img.shields.io/badge/Linux-0d1117?style=flat-square&logo=linux&logoColor=FCC624)
![Nginx](https://img.shields.io/badge/Nginx-0d1117?style=flat-square&logo=nginx&logoColor=009639)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0d1117?style=flat-square&logo=githubactions&logoColor=2088FF)
![Firebase](https://img.shields.io/badge/Firebase-0d1117?style=flat-square&logo=firebase&logoColor=FFCA28)

<br/>

**🔐 Auth**

![JWT](https://img.shields.io/badge/JWT-0d1117?style=flat-square&logo=jsonwebtokens&logoColor=ffffff)
![OAuth2](https://img.shields.io/badge/OAuth2-0d1117?style=flat-square&logo=oauth&logoColor=ffffff)
![Amazon Cognito](https://img.shields.io/badge/Amazon_Cognito-0d1117?style=flat-square&logo=amazonaws&logoColor=FF9900)

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
<td>🥇</td>
<td><strong>Gold Medalist</strong> &nbsp;·&nbsp; Department of Computer Science, University of Central Punjab</td>
</tr>
<tr>
<td>#1</td>
<td><strong>Department Rank 1</strong> &nbsp;·&nbsp; CGPA 4.00/4.00 &nbsp;·&nbsp; 100% Merit Scholarship throughout</td>
</tr>
<tr>
<td>🌏</td>
<td><strong>Google Asia-Pacific Generation Scholar 2024</strong> &nbsp;·&nbsp; Selected among top 3 women across the Asia-Pacific region</td>
</tr>
<tr>
<td>🏆</td>
<td><strong>Employee of the Quarter</strong> &nbsp;·&nbsp; Ibtidah Solutions</td>
</tr>
<tr>
<td>⚡</td>
<td><strong>Programming Competition Runner-up</strong> &nbsp;·&nbsp; Techathon 2025 · UCP Olympiad 2024</td>
</tr>
</table>

<br/>

---

<br/>

## GitHub Activity

<br/>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=laibaShahab&theme=dark&background=0d1117&border=30363d&ring=8b949e&fire=8b949e&currStreakLabel=8b949e&sideLabels=8b949e&dates=555555&currStreakNum=e6edf3&sideNums=e6edf3)](https://github.com/laibaShahab)

<br/>

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=laibaShahab&bg_color=0d1117&color=8b949e&line=30363d&point=8b949e&area=true&area_color=21262d&hide_border=true)](https://github.com/laibaShahab)

</div>

<br/>

---

<br/>

## Contact

<br/>

If you're building something hard and you want someone who will actually understand it before touching it, I'm interested in that conversation.

<br/>

[![Email](https://img.shields.io/badge/its.laiba.shahab%40gmail.com-0d1117?style=flat-square&logo=gmail&logoColor=EA4335)](mailto:its.laiba.shahab@gmail.com)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/laiba--shahab-0d1117?style=flat-square&logo=linkedin&logoColor=0A66C2)](https://linkedin.com/in/laiba-shahab)
&nbsp;
[![GitHub](https://img.shields.io/badge/laibaShahab-0d1117?style=flat-square&logo=github&logoColor=ffffff)](https://github.com/laibaShahab)

<br/>

---

<div align="center">
<br/>
<sub><code>I don't chase technologies. I chase problems. The technologies usually follow.</code></sub>
<br/><br/>

![footer](https://capsule-render.vercel.app/api?type=waving&color=0d1117&height=100&section=footer)

</div>
