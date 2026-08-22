<div align="center">
  <img src="./assets/header.svg" width="100%" alt="Antriksh Arya — Applied AI engineer building systems that survive contact with reality" />
</div>

<div align="center">
  <a href="https://antrskarya.vercel.app"><img src="https://img.shields.io/badge/portfolio-0d1117?style=for-the-badge&logo=vercel&logoColor=7ee787" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/antriksharya"><img src="./assets/linkedin-badge.svg" height="28" alt="LinkedIn" /></a>
  <a href="https://x.com/antrskarya"><img src="./assets/x-badge.svg" height="28" alt="X — @antrskarya" /></a>
  <a href="https://kaggle.com/antriksharya"><img src="https://img.shields.io/badge/kaggle-0d1117?style=for-the-badge&logo=kaggle&logoColor=58a6ff" alt="Kaggle" /></a>
  <a href="mailto:antriksh0704@gmail.com"><img src="https://img.shields.io/badge/say_hi-0d1117?style=for-the-badge&logo=gmail&logoColor=f85149" alt="Email Antriksh" /></a>
</div>

<br />

I turn messy data and workflows into **data + AI systems people can actually use**. My sweet spot is the layer between raw signals and a dependable product: pipelines, retrieval, evaluation, structured extraction, automation, and the backend glue that makes it all work.

> Currently building data systems as a **Data Engineering Intern** at [**New Engen**](https://www.newengen.com) ↗

```text
previously  → Data Science and Applied AI Intern @ CMN Labs
building_with  → data pipelines · LLM products · retrieval · automation
operating_from → India (UTC+5:30)
```

## `> shipped_work`

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>🔮 AURA</h3>
      <p>A grounded research companion that answers from retrieved paper evidence—not just model memory.</p>
      <p><code>Next.js</code> <code>Qdrant</code> <code>Gemini</code> <code>RAG</code></p>
      <a href="https://github.com/vdhkcheems/AURA"><b>source ↗</b></a> · <a href="https://aura-aa.vercel.app"><b>live ↗</b></a>
    </td>
    <td width="33%" valign="top">
      <h3>⚖️ Objection!</h3>
      <p>A courtroom strategy game where LLM dialogue is constrained by a locked, testable case-state engine.</p>
      <p><code>FastAPI</code> <code>Next.js</code> <code>Pydantic</code> <code>LLMs</code></p>
      <a href="https://github.com/vdhkcheems/objection"><b>active build ↗</b></a>
    </td>
    <td width="33%" valign="top">
      <h3>✍️ Essay Scorer</h3>
      <p>A fine-tuned DeBERTa-v3-large scoring pipeline exposed as a real-time inference API.</p>
      <p><code>PyTorch</code> <code>Transformers</code> <code>FastAPI</code> <code>NLP</code></p>
      <a href="https://github.com/vdhkcheems/Automated-Essay-Scorer"><b>source ↗</b></a>
    </td>
  </tr>
</table>

## `> systems_i_reach_for`

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,fastapi,nextjs,ts,postgres,docker,linux,git&theme=dark&perline=11" alt="Python, PyTorch, TensorFlow, scikit-learn, FastAPI, Next.js, TypeScript, PostgreSQL, Docker, Linux, and Git" />
</div>

<br />

## `> the_systems_map`

```mermaid
flowchart TB
    subgraph SIGNALS["01 · RAW SIGNALS"]
        direction LR
        A1["APIs"]
        A2["Product events"]
        A3["Documents + web"]
        A4["Batch files"]
    end

    subgraph DATA["02 · TRUSTED DATA PLANE"]
        direction LR
        B1["INGEST<br/>batch · stream · CDC"] --> B2["CONTRACTS<br/>schema · quality · lineage"]
        B2 --> B3["TRANSFORM<br/>SQL · Python · Spark"]
        B3 --> B4["STORE<br/>warehouse · lakehouse"]
    end

    subgraph INTELLIGENCE["03 · INTELLIGENCE LAYER"]
        direction LR
        C1["INDEX<br/>dense · sparse · metadata"] --> C2["RETRIEVE<br/>hybrid search · rerank"]
        C2 --> C3["REASON<br/>ML · LLM · rules"]
        C3 --> C4["EVALUATE<br/>gates · traces · drift"]
    end

    subgraph DELIVERY["04 · DELIVERY + FEEDBACK"]
        direction LR
        D1["SERVE<br/>APIs · data products"] --> D2["ACT<br/>agents · automations"]
        D2 --> D3["OBSERVE<br/>latency · cost · quality"]
        D3 --> D4["LEARN<br/>feedback · iteration"]
    end

    A1 --> B1
    A2 --> B1
    A3 --> B1
    A4 --> B1
    B4 --> C1
    C4 --> D1
    D4 -. "close the loop" .-> B2

    classDef source fill:#161b22,stroke:#58a6ff,color:#c9d1d9,stroke-width:1px;
    classDef pipeline fill:#0d1117,stroke:#7ee787,color:#c9d1d9,stroke-width:2px;
    classDef intelligence fill:#0d1117,stroke:#d2a8ff,color:#c9d1d9,stroke-width:2px;
    classDef delivery fill:#0d1117,stroke:#ffa657,color:#c9d1d9,stroke-width:2px;
    class A1,A2,A3,A4 source;
    class B1,B2,B3,B4 pipeline;
    class C1,C2,C3,C4 intelligence;
    class D1,D2,D3,D4 delivery;
```

## `> contribution_arcade`

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/vdhkcheems/vdhkcheems/output/github-contribution-grid-snake-dark.svg?v=blue" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/vdhkcheems/vdhkcheems/output/github-contribution-grid-snake.svg?v=blue" />
    <img alt="Animated blue snake eating Antriksh's GitHub contributions" src="https://raw.githubusercontent.com/vdhkcheems/vdhkcheems/output/github-contribution-grid-snake.svg?v=blue" />
  </picture>
</div>

<details>
  <summary><b>off the clock</b></summary>
  <br />
  Anime, video games, and occasionally rebuilding a neural network from scratch just to make sure the abstractions still make sense.
</details>
