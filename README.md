<div align="center">

# ⚡ ADETYA JAMWAL

### `AI ENGINEER` // `INTELLIGENT SYSTEMS`

**GenAI · Agentic Systems · RAG · ML Engineering**

*Building systems that retrieve, reason, and act — with engineering boundaries that make AI more reliable.*

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-AdetyaJamwal04-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AdetyaJamwal04)
[![Python](https://img.shields.io/badge/Python-3.11%20%7C%203.12%20%7C%203.13-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-Backend-009688?style=flat-square&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org)
[![LangGraph](https://img.shields.io/badge/LangGraph-Agentic%20Systems-1C3C3C?style=flat-square&logo=langchain&logoColor=white)](https://langchain-ai.github.io/langgraph/)

</div>

---

## 🌐 THE SYSTEMS I BUILD

```mermaid
flowchart TD

    A[Complex Query] --> B[Decompose & Structure]

    B --> C[Retrieval / Search / RAG]
    B --> D[Reasoning / NLI / LLMs]

    C --> E[Validate & Reflect]
    D --> E

    E -->|Gaps / Conflicts| B
    E -->|Grounded| F[Grounded Output + Evidence]

    classDef input fill:#dbeafe,stroke:#2563eb,stroke-width:2px,color:#1e3a8a
    classDef process fill:#fef3c7,stroke:#d97706,stroke-width:2px,color:#78350f
    classDef validate fill:#f3e8ff,stroke:#9333ea,stroke-width:2px,color:#581c87
    classDef output fill:#d1fae5,stroke:#059669,stroke-width:2px,color:#064e3b

    class A input
    class B,C,D process
    class E validate
    class F output

    linkStyle 5 stroke:#dc2626,stroke-width:2px
    linkStyle 6 stroke:#059669,stroke-width:2px
```

---

## ⚡ WHAT I BUILD

<table>
<tr>
<td width="50%" valign="top">

### 🔎 Retrieval & Evidence

* **Claim decomposition** — breaking complex propositions into verifiable units
* **Hybrid retrieval** — multi-provider search and content extraction
* **Neural reranking** — passage-level cross-encoder scoring
* **NLI verification** — stance and contradiction detection

</td>

<td width="50%" valign="top">

### 🧠 Agentic Systems

* **Stateful workflows** — graph-based execution with LangGraph
* **Query decomposition** — breaking complex research into parallel paths
* **Reflection loops** — identifying evidence gaps and iterating
* **Structured execution** — typed schemas and controlled tool flows

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 📈 ML Systems

* **Feature engineering** — high-dimensional time-series representations
* **Anomaly detection** — Autoencoders, Isolation Forest, One-Class SVM
* **Sequence modeling** — PyTorch LSTM for RUL prediction
* **Decision systems** — reinforcement-learning-based intervention policies

</td>

<td width="50%" valign="top">

### ⚙️ AI Infrastructure

* **Async APIs** — FastAPI services and streaming endpoints
* **Data systems** — PostgreSQL, pgvector, Alembic
* **Caching** — Redis-based multi-tier caching
* **Engineering discipline** — Docker, testing, evaluation and security controls

</td>
</tr>
</table>

---

## 🧬 FEATURED SYSTEMS

### `01` — TATHVYN

#### **Evidence Intelligence & Claim Verification Engine**

An evidence-driven claim verification system combining atomic decomposition, multi-source retrieval, neural reranking, NLI-based stance detection, and grounded verdict generation.

```text
CLAIM
  │
  ▼
DECOMPOSE ──────────────► Atomic sub-claims
  │
  ▼
RETRIEVE ───────────────► Tavily + Brave
  │
  ▼
RERANK ─────────────────► Cross-Encoder
  │
  ▼
VERIFY ─────────────────► DeBERTa / DistilRoBERTa NLI
  │
  ▼
VALIDATE ───────────────► Temporal + Numeric + Conflict Checks
  │
  ├──── gaps ───────────► Reflection / Retrieval
  │
  ▼
VERDICT ────────────────► Evidence + Grounded Synthesis
```

|                 |                                                                          |
| --------------- | ------------------------------------------------------------------------ |
| **Engineering** | `FastAPI` · `LangGraph` · `PostgreSQL` · `pgvector` · `Redis` · `Docker` |
| **Quality**     | 143 tests · ~90% coverage · evaluation harness                           |
| **Security**    | prompt isolation · input sanitization · SSRF defenses                    |

*Tathvyn represents the architectural evolution of an earlier claim-verification prototype, [VeriFact](https://github.com/AdetyaJamwal04/VeriFact---Retrieval-Augmented-Neural-Claim-Verification-System).*

**→ [Explore Tathvyn](https://github.com/AdetyaJamwal04/Tathvyn-Evidence-Intelligence-Claim-Verification-Engine)**

<br/>

### `02` — DEEPSEARCH

#### **Agentic Research & Evidence Synthesis System**

A stateful research pipeline that decomposes complex questions, gathers evidence, identifies knowledge gaps, and iteratively refines its search through reflection.

```text
USER QUERY
    │
    ├──► QUERY SYNTHESIS
    │
    ├──► SUB-QUESTION GENERATION
    │
    ├──► SEARCH & RETRIEVAL
    │
    ├──► EVIDENCE EXTRACTION
    │
    ├──► KNOWLEDGE STORE
    │
    └──► REFLECTION
             │
        gaps detected?
             │
             └──────────► iterate
                           │
                           ▼
                    REPORT SYNTHESIS
```

|                  |                                                                           |
| ---------------- | ------------------------------------------------------------------------- |
| **Engineering**  | `LangGraph` · `LangChain` · `Gemini` · `Tavily` · `FastAPI` · `Streamlit` |
| **Architecture** | stateful graph · cyclic reflection · structured schemas · streaming API   |

**→ [Explore DeepSearch](https://github.com/AdetyaJamwal04/DeepSearch-Agentic-System)**

<br/>

### `03` — C-MAPSS

#### **Spacecraft Predictive Maintenance System**

End-to-end ML pipeline for anomaly detection, remaining-useful-life prediction, and decision support using NASA C-MAPSS turbofan telemetry.

```text
NASA TELEMETRY
      │
      ▼
FEATURE ENGINEERING
17 sensors ──────────► 188 engineered features
      │
      ▼
ANOMALY DETECTION
Autoencoder · Isolation Forest · One-Class SVM
      │
      ▼
RUL PREDICTION
PyTorch LSTM
      │
      ▼
RISK / DECISION ENGINE
      │
      ▼
Q-LEARNING
Intervention timing
```

|                     |                                                                                   |
| ------------------- | --------------------------------------------------------------------------------- |
| **Engineering**     | `PyTorch` · `scikit-learn` · `LSTM` · `Autoencoders` · `Q-Learning` · `Streamlit` |
| **Verified result** | `15.17 RMSE · R² = 0.87` on FD001                                                 |

**→ [Explore C-MAPSS](https://github.com/AdetyaJamwal04/C-MAPSS-Spacecraft-Predictive-Maintenance-System)**

---

## 📊 ENGINEERING SIGNALS

| Metric              |    Value | Project |
| ------------------- | -------: | ------- |
| Tests               |  **143** | Tathvyn |
| Coverage            | **~90%** | Tathvyn |
| Engineered Features |  **188** | C-MAPSS |
| Architecture Docs   |   **26** | Tathvyn |

---

## 🛠️ TECHNICAL ARSENAL

| Capability                   | Stack                                                                                    |
| ---------------------------- | ---------------------------------------------------------------------------------------- |
| **GenAI & Agents**           | `LangGraph` · `LangChain` · `Google Gemini` · `Groq`                                     |
| **Retrieval & NLP**          | `Cross-Encoders` · `DeBERTa NLI` · `Sentence Transformers` · `Tavily` · `Brave`          |
| **ML / Deep Learning**       | `PyTorch` · `scikit-learn` · `TensorFlow` · `LSTM` · `Autoencoders` · `NumPy` · `Pandas` |
| **Backend & Data**           | `FastAPI` · `Pydantic` · `PostgreSQL` · `pgvector` · `Redis` · `SQLAlchemy` · `Alembic`  |
| **Infrastructure & Quality** | `Docker` · `Docker Compose` · `pytest` · `ruff` · `mypy` · `uv` · `Render`               |

---

## 💡 HOW I THINK

```text
┌──────────────────────────────────────────────────────────────────────┐
│                                                                      │
│  01 / MODELS ARE COMPONENTS, NOT SYSTEMS.                            │
│      Reliability emerges from orchestration, boundaries,             │
│      validation, and failure handling.                               │
│                                                                      │
│  02 / RETRIEVAL IS PART OF REASONING.                                │
│      An intelligent system is only as grounded as the                │
│      information it can discover, filter, and verify.                │
│                                                                      │
│  03 / SYSTEMS REQUIRE EVALUATION, NOT VIBES.                         │
│      Fluency is not correctness. AI systems need measurable          │
│      behavior, regression testing, and adversarial evaluation.       │
│                                                                      │
│  04 / GROUNDING PRECEDES GENERATION.                                 │
│      Useful intelligence needs traceable evidence and                │
│      explicit boundaries around uncertainty.                         │
│                                                                      │
└──────────────────────────────────────────────────────────────────────┘
```

---

## 🧭 EXPLORING NEXT

```text
◉ Agentic Tool Use & Multi-Agent Systems
◉ LLM Evaluation & Regression Testing
◉ Advanced RAG & Knowledge Graph Retrieval
◉ Production MLOps & AI Observability
◉ Reliable AI System Architecture
```

---

<div align="center">

### `BUILD → MEASURE → VERIFY → ITERATE`

*We build machines to reason — while remaining fascinated by the questions,*
*poetry, and philosophy that resist computation.*

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-%40AdetyaJamwal04-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AdetyaJamwal04)

<!-- Add your professional links here -->

<!-- LinkedIn -->

<!-- Email -->

</div>
