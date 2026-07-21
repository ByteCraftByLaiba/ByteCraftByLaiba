<div align="center">

<img src="./assets/header.svg" width="100%" alt="Laiba Runtime"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=3500&pause=1200&color=58A6FF&center=true&vCenter=true&width=750&lines=Building+backend+systems...;Turning+chaos+into+structure...;Architecture+before+implementation...;Documentation+is+part+of+the+engineering.;There+has+to+be+a+better+way." />

</div>

---

```bash
$ ssh guest@laiba.dev
```

```text
The authenticity of host 'laiba.dev' can't be established.

ED25519 key fingerprint is:
SHA256:backend-ai-systems-documentation-diagrams

Are you sure you want to continue connecting (yes/no)?
```

```text
yes

Authenticating...

✔ Connected.

Welcome to Laiba Runtime v22.0 LTS

Last login: just now
```

---

```bash
guest@laiba:~$ help
```

```text
Available commands

whoami          Learn about the engineer
projects        Production & open source work
experience      Things I've built professionally
philosophy      How I think about software
brain           How I approach problems
skills          Technologies I work with
awards          Things that made my parents happy
contact         Start a conversation
exit            Disconnect safely
```

---

```bash
guest@laiba:~$ whoami
```

```text
NAME
    Laiba Shahab

ROLE
    Backend Engineer

SPECIALIZATION
    Backend Systems
    AI Systems
    Developer Tools

CURRENT STATUS
    Building enterprise AI platforms.
    Maintaining production systems.
    Creating open source software.

KNOWN BEHAVIOR
    • Draws architecture diagrams before writing code.
    • Documentation usually appears in the same PR.
    • Asks "Why?" before asking "How?"
    • Believes every system can be simplified.

CURRENT MISSION
    Build software that's easier to understand than it was yesterday.
```

---

```bash
guest@laiba:~$ neofetch
```

<div align="center">

<img src="./assets/neofetch.svg" width="100%" alt="neofetch"/>

</div>

---

```bash
guest@laiba:~$ uname -a
```

```text
Laiba Runtime 22.0

Kernel          Curiosity
Architecture    Backend
Shell           /bin/python
Editor          VS Code
Package Manager pip
Documentation   Enabled
Architecture    Enabled
Coffee          Required
```

---

```bash
guest@laiba:~$ cat /etc/philosophy.conf
```

```ini
understand_problem_before_solution = true

architecture_before_code = true

documentation_is_engineering = true

single_source_of_truth = true

simple_beats_clever = true

if_repeated_twice = automate_it

complexity = keep_it_in_the_right_place
```

---

```bash
guest@laiba:~$ ps aux
```

```text
PID     SERVICE                     STATUS

101     backend.service             running
102     ai.service                  running
103     architecture.service        always running
104     documentation.service       started before the ticket existed
105     curiosity.service           uptime: 22 years
```

---

```bash
guest@laiba:~$
```

---

```bash
guest@laiba:~$ systemctl --type=service --state=running
```

```text
UNIT                             LOAD      ACTIVE     DESCRIPTION

delivery-platform.service        loaded    active     White-label logistics backend
enterprise-ai.service            loaded    active     Multi-tenant AI risk platform
legal-ai.service                 loaded    active     Enterprise legal AI backend

3 loaded units
0 failed
```

---

```bash
guest@laiba:~$ systemctl status delivery-platform.service
```

```text
● delivery-platform.service

Status:
    Active (running)

Summary:
    Built the complete backend as the sole backend engineer.

Responsibilities:
    • REST APIs
    • Authentication & Authorization
    • PostgreSQL schema
    • Socket.IO
    • Background jobs
    • Docker deployment
    • Mobile + Web integration

Interesting part:
    A white-label platform isn't one application.
    It's one backend pretending to be many businesses.
```

<details>
<summary><strong>View architecture</strong></summary>

```text
                 Customer

                    │

                    ▼

              API Gateway

                    │

      ┌─────────────┼──────────────┐
      │             │              │

 Authentication   Orders      Real-time

      │             │              │

      └─────────────┼──────────────┘

                    │

               PostgreSQL

                    │

                 Redis

                    │

              Background Jobs
```

**Stack**

<img src="https://skillicons.dev/icons?i=py,fastapi,postgres,redis,docker,firebase&theme=dark"/>

</details>

---

```bash
guest@laiba:~$ systemctl status enterprise-ai.service
```

```text
● enterprise-ai.service

Status:
    Active (running)

Summary:
    Enterprise AI platform for regulated environments.

Interesting part:
    The difficult part isn't AI.

    It's permissions.

    Isolation.

    Auditability.

    Traceability.

    AI is easy compared to that.

Responsibilities:
    • Multi-tenant backend
    • RAG pipelines
    • Agentic workflows
    • AWS Bedrock
    • Architecture documentation
    • API documentation
```

<details>
<summary><strong>View architecture</strong></summary>

```text
User

 │

 ▼

FastAPI

 │

 ├──────────────┐

 ▼              ▼

RAG         Agent Workflow

 │              │

 ▼              ▼

Bedrock     EventBridge

 │              │

 └──────┬───────┘

        ▼

 Aurora PostgreSQL + pgvector
```

<img src="https://skillicons.dev/icons?i=py,fastapi,aws,postgres,docker&theme=dark"/>

</details>

---

```bash
guest@laiba:~$ systemctl status legal-ai.service
```

```text
● legal-ai.service

Status:
    Active (running)

Summary:
    Production maintenance for an enterprise legal AI platform.

Responsibilities:
    • Backend development
    • Bug fixing
    • New features
    • Production support
    • Client issues

Interesting part:
    Production software breaks.

    The goal isn't perfection.

    The goal is understanding failures quickly.
```

<img src="https://skillicons.dev/icons?i=py,fastapi,aws&theme=dark"/>

---

```bash
guest@laiba:~$ ls ~/opensource
```

```text
socketspec/
```

---

```bash
guest@laiba:~$ inspect socketspec
```

```text
Name
    SocketSpec

Status
    Public

License
    Apache 2.0

Reason it exists
    I kept wishing FastAPI existed for WebSockets.

    Eventually I stopped wishing.

Features
    • Decorator routing
    • Dependency Injection
    • Typed Events
    • Authentication
    • Interactive Documentation

Current Goal
    Make production WebSocket development feel boring.
```

<div align="center">

[![GitHub](https://img.shields.io/badge/source-socketspec-24292e?style=flat-square&logo=github&logoColor=white)](https://github.com/ByteCraftByLaiba/socketspec)
[![PyPI](https://img.shields.io/badge/PyPI-socketspec-3775A9?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/socketspec)

</div>

---

```bash
guest@laiba:~$ ls ~/projects
```

```text
smartml/

doctor-agent/

media-player-cpp/

compiler/
```

---

```bash
guest@laiba:~$ inspect smartml
```

```text
Project
    SmartML

Type
    Final Year Project

Summary
    End-to-end AutoML platform.

Motivation
    Machine learning shouldn't require
    knowing machine learning.

Features
    • Dataset management
    • Preprocessing
    • Training
    • Explainability
    • Deployment
    • AI Assistant

Personal Note
    This project taught me more than any course ever could.
```

<img src="https://skillicons.dev/icons?i=py,fastapi,nextjs,postgres,mongodb,aws&theme=dark"/>

---

---

```bash
guest@laiba:~$ cat /proc/laiba/brain
```

```text
PROCESSOR

    System Thinking

CLOCK SPEED

    Depends on coffee.

PRIMARY LANGUAGE

    Diagrams

SECONDARY LANGUAGE

    Python

OPERATING MODE

    "There has to be a better way."

MEMORY MANAGEMENT

    Deletes syntax.

    Keeps patterns.

FAULT HANDLER

    Why?

    Why?

    Why?

    ...okay now let's code.
```

---

```bash
guest@laiba:~$ tree ~/brain
```

```text
brain
├── architecture/
│   ├── sequence-diagrams
│   ├── deployment-diagrams
│   ├── erd
│   └── api-design
│
├── backend/
│   ├── fastapi
│   ├── async-python
│   ├── authentication
│   ├── authorization
│   ├── websocket
│   └── distributed-systems
│
├── ai/
│   ├── rag
│   ├── langgraph
│   ├── bedrock
│   ├── vector-search
│   └── llm-evaluation
│
├── cloud/
│   ├── aws
│   ├── docker
│   ├── ecs
│   ├── eventbridge
│   └── sqs
│
├── databases/
│   ├── postgres
│   ├── redis
│   ├── mongodb
│   └── pgvector
│
└── curiosity/
    └── unlimited
```

---

```bash
guest@laiba:~$ cat /etc/engineering.conf
```

```ini
# Loaded automatically at startup.

understand_the_problem=true

architecture_before_implementation=true

single_source_of_truth=true

documentation_is_part_of_engineering=true

code_should_be_easy_to_delete=true

if_it_needs_explaining_twice=document_it

if_it_happens_twice=automate_it

clever_code=false

boring_code=true
```

---

```bash
guest@laiba:~$ cat /var/log/known_issues.log
```

```text
[WARN]

Architecture diagrams appear before anyone asks.

May spend 30 minutes naming one function.

Treats documentation like production code.

Keeps reorganizing folders until they feel right.

Sometimes opens draw.io before VS Code.

Still believes every complex system
can become simple.
```

---

```bash
guest@laiba:~$ history | tail -15
```

```text
architecture.draw()

git checkout -b feature/new-idea

python main.py

python main.py

python main.py

why-is-this-not-working

fixed-a-typo

git commit

git push

draw-another-diagram

write-docs

ship-it
```

---

```bash
guest@laiba:~$ grep philosophy ~/.bashrc
```

```bash
export ENGINEERING_PHILOSOPHY="

Understand first.

Design second.

Code third.

Document while building.

Leave the system easier
than you found it.
"
```

---

```bash
guest@laiba:~$ htop
```

<div align="center">

```text
CPU

██████████████████████░░░░░░░ 72%

Current Task

███████████████████████████░░ 91%

Coffee

█████████████████████████████ 100%

Documentation

█████████████████████████████ 100%

Architecture

█████████████████████████████ 100%

Meetings

███░░░░░░░░░░░░░░░░░░░░░░░░░░ 9%
```

</div>

---

```bash
guest@laiba:~$ skills --grouped
```

<div align="center">

### Languages

<img src="https://skillicons.dev/icons?i=py,ts,js,cpp&theme=dark"/>

### Backend

<img src="https://skillicons.dev/icons?i=fastapi,django,flask,nodejs&theme=dark"/>

### AI

<img src="https://skillicons.dev/icons?i=pytorch,sklearn&theme=dark"/>

### Cloud

<img src="https://skillicons.dev/icons?i=aws,docker,linux,nginx&theme=dark"/>

### Database

<img src="https://skillicons.dev/icons?i=postgres,mongodb,redis&theme=dark"/>

### Frontend (Enough to be dangerous)

<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind&theme=dark"/>

</div>

---

```bash
guest@laiba:~$ echo $MOTTO
```

```text
Complexity belongs in the right place.

Software should be easier to understand
after I'm done with it.
```

---

---

```bash
guest@laiba:~$ achievements
```

```text
Loading accomplishments...

[SUCCESS] Gold Medalist
          Department of Computer Science

[SUCCESS] Rank #1
          CGPA 4.00 / 4.00

[SUCCESS] Google APAC Generation Scholar 2024
          Selected among the top women across Asia-Pacific

[SUCCESS] Employee of the Quarter
          First quarter at Ibtidah Solutions

[SUCCESS] Production systems deployed
          Still running.

Done.
```

---

```bash
guest@laiba:~$ uptime
```

```text
22 years, still curious.

Current interests

• Backend Architecture
• AI Systems
• Distributed Systems
• Open Source
• Building things that probably should exist
```

---

```bash
guest@laiba:~$ git log --author=laiba --oneline | head
```

```text
f8e2d1a  docs: architecture before implementation

91ac2d3  feat: built an open-source WebSocket framework

8ab91e2  feat: shipped SmartML

3dc1b7f  refactor: simplify before optimizing

1f92d81  docs: because future me deserves documentation too
```

---

```bash
guest@laiba:~$ cat /etc/motd
```

```text
──────────────────────────────────────────────────────────────

Most people start with technology.

I usually start with the problem.

Everything else tends to follow.

──────────────────────────────────────────────────────────────
```

---

```bash
guest@laiba:~$ tail -n 10 /var/log/laiba.log
```

```text
[INFO] Started another architecture diagram.

[INFO] Asked "Why?" before "How?"

[INFO] Found a simpler approach.

[INFO] Documentation committed.

[INFO] Feature deployed.

[INFO] Future engineer silently appreciated it.
```

---

```bash
guest@laiba:~$ contact
```

```text
Interested in backend engineering,
AI systems,
distributed systems,
or just want to nerd out about architecture?

Let's talk.
```

<div align="center">

[![Email](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:its.laiba.shahab@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/laiba-shahab)
[![GitHub](https://img.shields.io/badge/GitHub-24292e?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ByteCraftByLaiba)

</div>

---

<div align="center">

<img src="https://github-streak-stats.herokuapp.com?user=ByteCraftByLaiba&theme=github-dark-blue&hide_border=true" height="170"/>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ByteCraftByLaiba&bg_color=0d1117&color=58A6FF&line=58A6FF&point=FFFFFF&area=true&hide_border=true"/>

</div>

---

```bash
guest@laiba:~$ exit
```

```text
Saving architecture diagrams...           done

Saving documentation...                   already saved

Stopping backend.service...               done

Stopping ai.service...                    done

Stopping curiosity.service...             impossible

Broadcast message:

    "There has to be a better way."

Connection to laiba.dev closed.

logout
```

<div align="center">

### Thanks for stopping by.

⭐ If you found something interesting, feel free to explore the repositories.

</div>
