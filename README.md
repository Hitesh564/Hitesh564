<!-- =========================================================
                      H I T E S H   J I N D A L
                  AI • SYSTEMS • ENGINEERING
========================================================== -->

<div align="center">

<img width="100%"
src="https://capsule-render.vercel.app/api?type=waving&height=270&color=0:080808,35:111111,70:17130E,100:2A2115&text=HITESH%20JINDAL&fontColor=E8D7B0&fontSize=54&fontAlignY=37&desc=ENGINEERING%20INTELLIGENT%20SYSTEMS&descSize=15&descAlignY=57&animation=fadeIn"/>

<br/>

<img
src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=21&duration=2800&pause=900&color=C8A96B&center=true&vCenter=true&width=900&height=50&lines=Building+AI+systems+that+reason%2C+adapt%2C+and+ship.;Designing+agents+that+can+be+measured+%E2%80%94+not+just+demoed.;Turning+model+intelligence+into+production+systems.;AI+Engineering+%C3%97+Software+Systems+%C3%97+Product."
alt="Typing animation"
/>

<br/>

<sub>
AI SYSTEMS &nbsp;·&nbsp; AGENTIC INFRASTRUCTURE &nbsp;·&nbsp; REAL-TIME AI &nbsp;·&nbsp; SOFTWARE ENGINEERING
</sub>

<br/><br/>

<a href="https://veriq-flax.vercel.app">
<img src="https://img.shields.io/badge/VIEW%20VERIQ-LIVE-C8A96B?style=for-the-badge&labelColor=111111"/>
</a>
&nbsp;
<a href="https://www.linkedin.com/in/hitesh-jindal56/">
<img src="https://img.shields.io/badge/LINKEDIN-CONNECT-242424?style=for-the-badge&logo=linkedin&logoColor=E8D7B0&labelColor=111111"/>
</a>
&nbsp;
<a href="mailto:jindalhitesh564@gmail.com">
<img src="https://img.shields.io/badge/EMAIL-CONTACT-242424?style=for-the-badge&logo=gmail&logoColor=E8D7B0&labelColor=111111"/>
</a>

</div>

<br/>

---

# `01. PROFILE`

<div align="center">

### Building intelligent systems that survive beyond the demo.

</div>

<br/>

<table>
<tr>
<td width="50%" valign="top">

### ◈ ENGINEERING

I’m **Hitesh Jindal**, a Computer Science & Artificial Intelligence undergraduate at **Plaksha University**.

I enjoy building AI products where the difficult part is not simply calling a model API, but designing the surrounding system.

My work currently sits around:

- AI engineering
- agentic systems
- real-time AI
- backend architecture
- AI evaluation
- applied machine learning

</td>

<td width="50%" valign="top">

### ◈ SYSTEMS THINKING

The parts of AI systems I find most interesting are:

- state & memory
- orchestration
- retrieval
- evaluation
- latency
- observability
- reliability
- product experience

I like moving from:

**idea → architecture → implementation → evaluation → deployment**

</td>
</tr>
</table>

<br/>

<div align="center">

### `BUILD → MEASURE → UNDERSTAND → IMPROVE → SHIP`

</div>

<br/>

> **My goal is not just to make AI generate good outputs — it is to engineer systems that behave reliably, adapt to context, and create measurable value.**

---

# `02. CURRENT SIGNAL`

<div align="center">

<table>
<tr>

<td align="center" width="33%">

### `BUILDING`

**Adaptive AI Systems**

Stateful agents, contextual reasoning, real-time interaction.

</td>

<td align="center" width="33%">

### `MEASURING`

**AI Reliability**

Evaluation, failure diagnosis, benchmarking, evidence.

</td>

<td align="center" width="33%">

### `LEARNING`

**Systems at Scale**

Distributed systems, backend scalability, observability.

</td>

</tr>
</table>

</div>

---

# `03. SELECTED WORK`

<table>
<tr>

<td width="50%" valign="top">

## ◈ Veriq

### AI Interview Intelligence Platform

A real-time AI interviewer designed around **adaptive questioning, contextual follow-ups, voice interaction, evidence collection, and structured evaluation**.

Instead of following a static question bank, Veriq maintains interview state and decides how deeply to explore a topic based on candidate responses.

### Core Engineering

- Multi-stage interview orchestration
- Context-aware follow-ups
- Multi-turn claim verification
- Persistent interview state
- Evidence-grounded scoring
- Voice-first interaction
- Resume / JD / role-aware interviews

### Stack

`LangGraph` `FastAPI` `Next.js`  
`TypeScript` `PostgreSQL` `Supabase` `Gemini`

<br/>

<a href="https://github.com/Hitesh564/Veriq">
<img src="https://img.shields.io/badge/SOURCE-111111?style=for-the-badge&logo=github&logoColor=C8A96B"/>
</a>

<a href="https://veriq-flax.vercel.app">
<img src="https://img.shields.io/badge/LIVE-C8A96B?style=for-the-badge&logo=vercel&logoColor=111111"/>
</a>

</td>


<td width="50%" valign="top">

## ◈ AgentEval

### Failure Diagnosis for LLM Agents

An evaluation framework for understanding **why multi-step LLM-agent workflows fail**, rather than only reporting whether they succeeded.

AgentEval analyzes execution traces, node-level health signals, and dependency relationships to identify probable failure contributors.

### Core Engineering

- Trace-based evaluation
- Dependency-aware attribution
- Root-cause localization
- Failure remediation insights
- Automated benchmarking
- External benchmark validation

### Benchmark

**73.3% Accuracy**  
**76.2% Balanced Accuracy**

### Stack

`Python` `FastAPI` `LangChain`  
`PostgreSQL` `LiteLLM`

<br/>

<a href="https://github.com/Hitesh564/AgentEval">
<img src="https://img.shields.io/badge/SOURCE-111111?style=for-the-badge&logo=github&logoColor=C8A96B"/>
</a>

</td>

</tr>
</table>

---

# `04. RESEARCH × APPLIED ML`

## ◈ Explainable Retinal Age Gap

Built an explainable retinal-age estimation pipeline using **RETFound / Vision Transformers, vascular biomarkers, XGBoost, and SHAP**.

Worked across **23K+ retinal images** from ODIR-5K and BRSET.

```mermaid
%%{init: {'theme':'base','themeVariables': {
  'primaryColor':'#141414',
  'primaryTextColor':'#E8D7B0',
  'primaryBorderColor':'#C8A96B',
  'lineColor':'#C8A96B',
  'secondaryColor':'#191919',
  'tertiaryColor':'#111111',
  'background':'#0D0D0D',
  'fontFamily':'JetBrains Mono'
}}}%%
flowchart LR

    A["23K+ Retinal Images"] --> B["Preprocessing"]

    B --> C["RETFound / ViT"]
    B --> D["Vessel Analysis"]

    D --> E["Vascular Biomarkers"]

    C --> F["Representation"]
    E --> G["XGBoost"]

    F --> H["Retinal Age"]
    G --> H

    H --> I["Explainability / SHAP"]
```

`PyTorch` · `RETFound` · `OpenCV` · `XGBoost` · `SHAP`

---

# `05. ENGINEERING STACK`

<div align="center">

### INTELLIGENCE

<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,opencv&theme=dark"/>

<br/>

`LLMs` · `LangChain` · `LangGraph` · `RAG` · `Hugging Face` · `Gemini` · `Agentic AI`

<br/><br/>

### SYSTEMS & DATA

<img src="https://skillicons.dev/icons?i=fastapi,postgres,mongodb,supabase,docker&theme=dark"/>

<br/>

`REST APIs` · `WebSockets` · `SQLModel` · `SQLAlchemy` · `Vector Search`

<br/><br/>

### INTERFACE

<img src="https://skillicons.dev/icons?i=nextjs,react,typescript,js,html,css&theme=dark"/>

<br/><br/>

### ENGINEERING

<img src="https://skillicons.dev/icons?i=cpp,git,github,vscode,vercel&theme=dark"/>

</div>

---

# `06. HOW I BUILD`

<div align="center">

### From a problem to a system that can be measured.

</div>

```mermaid
%%{init: {'theme':'base','themeVariables': {
  'primaryColor':'#141414',
  'primaryTextColor':'#E8D7B0',
  'primaryBorderColor':'#C8A96B',
  'lineColor':'#C8A96B',
  'secondaryColor':'#191919',
  'tertiaryColor':'#111111',
  'background':'#0D0D0D',
  'fontFamily':'JetBrains Mono'
}}}%%
flowchart LR

    A["01 · Problem"] --> B["02 · Architecture"]
    B --> C["03 · Intelligence"]
    C --> D["04 · System"]
    D --> E["05 · Evaluation"]
    E --> F["06 · Deploy"]
    F --> G["07 · Observe"]
    G --> B
```

<br/>

<table>
<tr>

<td width="33%" valign="top">

### ◈ Intelligence Layer

- LLMs / models
- retrieval
- reasoning
- prompting
- agents
- context

</td>

<td width="33%" valign="top">

### ◈ Systems Layer

- APIs
- state
- memory
- databases
- orchestration
- reliability

</td>

<td width="33%" valign="top">

### ◈ Product Layer

- latency
- UX
- feedback loops
- observability
- evaluation
- real users

</td>

</tr>
</table>

<br/>

<div align="center">

### `MODEL ≠ PRODUCT`

A useful AI product is the combination of:

`INTELLIGENCE × SYSTEMS × EVALUATION × EXPERIENCE`

</div>

---

# `07. CURRENT EXPLORATIONS`

<table>

<tr>

<td width="50%" valign="top">

## ◈ NOW

### Systems I’m actively exploring

**Agent Evaluation & Reliability**  
Understanding why agent workflows fail and how to measure them.

**Adaptive AI Systems**  
Maintaining state, context, memory, and dynamic behavior over long-running interactions.

**Real-Time AI**  
Reducing latency across speech, inference, orchestration, and response pipelines.

**Context Engineering**  
Retrieval, memory, prompt construction, and information selection.

</td>

<td width="50%" valign="top">

## ◈ NEXT DEPTH

### Areas I’m going deeper into

**Distributed Systems**  
Coordination, consistency, scaling, and failure.

**Backend Scalability**  
Designing systems that survive increased load and complexity.

**AI Observability**  
Understanding what intelligent systems are doing internally.

**Agent Failure Analysis**  
Tracing failures across multi-step AI workflows.

**Evaluation Methodology**  
Moving beyond anecdotal quality toward measurable performance.

</td>

</tr>

</table>

<br/>

<div align="center">

```text
CURRENT MODE

BUILD SYSTEMS THAT CAN
THINK  ·  ADAPT  ·  FAIL  ·  BE MEASURED  ·  IMPROVE
```

</div>

---

# `08. ENGINEERING VIEW`

```mermaid
%%{init: {'theme':'base','themeVariables': {
  'primaryColor':'#141414',
  'primaryTextColor':'#E8D7B0',
  'primaryBorderColor':'#C8A96B',
  'lineColor':'#C8A96B',
  'secondaryColor':'#191919',
  'tertiaryColor':'#111111',
  'background':'#0D0D0D',
  'fontFamily':'JetBrains Mono'
}}}%%
flowchart TB

    A["AI PRODUCT"]

    A --> B["INTELLIGENCE"]
    A --> C["SYSTEM"]
    A --> D["EXPERIENCE"]

    B --> B1["Models"]
    B --> B2["Retrieval"]
    B --> B3["Reasoning"]

    C --> C1["State"]
    C --> C2["Memory"]
    C --> C3["APIs"]
    C --> C4["Data"]

    D --> D1["UX"]
    D --> D2["Latency"]
    D --> D3["Feedback"]
    D --> D4["Reliability"]

    B --> E["EVALUATION"]
    C --> E
    D --> E

    E --> F["OBSERVE"]
    F --> G["IMPROVE"]
    G --> A
```

<div align="center">

### The model is one component.

The system around it determines whether it becomes a **demo** or a **product**.

</div>

---

# `09. GITHUB`

<div align="center">

### Code tells one part of the story.

<br/>

<img
src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Hitesh564&theme=github_dark"
width="95%"
/>

<br/><br/>

<img
src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Hitesh564&theme=github_dark"
height="170"
/>

<img
src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Hitesh564&theme=github_dark"
height="170"
/>

<br/><br/>

<img
src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Hitesh564&theme=github_dark"
height="170"
/>

<img
src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Hitesh564&theme=github_dark&utcOffset=5.5"
height="170"
/>

</div>

<br/>

<div align="center">

<img
src="https://github-readme-activity-graph.vercel.app/graph?username=Hitesh564&bg_color=0D0D0D&color=C8A96B&line=C8A96B&point=F1DFB8&area=true&area_color=2A2115&hide_border=true"
width="96%"
/>

</div>

---

# `10. PRINCIPLES`

<div align="center">

## `BUILD SYSTEMS — NOT WRAPPERS.`

<br/>

<table>

<tr>

<td align="center" width="25%">

### MEASURE

what the AI  
actually does

</td>

<td align="center" width="25%">

### UNDERSTAND

how and why  
it fails

</td>

<td align="center" width="25%">

### DESIGN

for uncertainty  
and change

</td>

<td align="center" width="25%">

### SHIP

what people  
can actually use

</td>

</tr>

</table>

</div>

---

# `11. OPEN CHANNEL`

<div align="center">

### Interested in AI systems, agents, evaluation, ML engineering, or ambitious software?

<br/>

<a href="mailto:jindalhitesh564@gmail.com">
<img src="https://img.shields.io/badge/EMAIL-CONTACT-242424?style=for-the-badge&logo=gmail&logoColor=E8D7B0&labelColor=111111"/>
</a>

&nbsp;

<a href="https://www.linkedin.com/in/hitesh-jindal56/">
<img src="https://img.shields.io/badge/LINKEDIN-CONNECT-242424?style=for-the-badge&logo=linkedin&logoColor=E8D7B0&labelColor=111111"/>
</a>

&nbsp;

<a href="https://github.com/Hitesh564">
<img src="https://img.shields.io/badge/GITHUB-FOLLOW-242424?style=for-the-badge&logo=github&logoColor=E8D7B0&labelColor=111111"/>
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=Hitesh564&label=PROFILE+VISITORS&color=C8A96B&style=flat-square"/>

<br/><br/><br/>

`INTELLIGENCE × ENGINEERING × EXECUTION`

<br/><br/>

<i>Learning by building. Improving by measuring. Shipping by iterating.</i>

</div>

<br/>

<img width="100%"
src="https://capsule-render.vercel.app/api?type=waving&height=140&section=footer&color=0:2A2115,40:17130E,70:111111,100:080808"/>
