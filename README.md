[![Header Banner](https://raw.githubusercontent.com/AbdelrahmanAboegela/AbdelrahmanAboegela/main/Banner.gif)](https://www.linkedin.com/in/leby/)

<h1 align="center">Abdelrahman Alshames</h1>

<p align="center">
  <strong>AI Research & Systems Engineering</strong><br>
  Arabic language systems · Robust ML evaluation · Retrieval & agents
</p>

<p align="center">
  <a href="https://github.com/AbdelrahmanAboegela?tab=repositories"><img alt="GitHub repositories" src="https://img.shields.io/badge/REPOSITORIES-18181B?style=for-the-badge&logo=github&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/leby/"><img alt="LinkedIn" src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:abdelrahman.aboegela@gmail.com"><img alt="Email" src="https://img.shields.io/badge/EMAIL-334155?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

<p align="center">
  <img alt="Arabic NLP" src="https://img.shields.io/badge/ARABIC_NLP-0F766E?style=flat-square">
  <img alt="Text to SQL" src="https://img.shields.io/badge/TEXT--TO--SQL-0F766E?style=flat-square">
  <img alt="LLM Safety" src="https://img.shields.io/badge/LLM_SAFETY-0F766E?style=flat-square">
  <img alt="Robustness" src="https://img.shields.io/badge/ROBUST_EVALUATION-0F766E?style=flat-square">
  <img alt="Retrieval Systems" src="https://img.shields.io/badge/RETRIEVAL_SYSTEMS-0F766E?style=flat-square">
</p>

I work on Arabic-language AI systems and the questions that make their results difficult to trust: **ambiguous database schemas, unreliable retrieval, distribution shifts, adversarial input, and evaluation shortcuts**. I care about building the whole system, but especially about knowing what the result *actually demonstrates*.

B.Sc. Computer Science (Artificial Intelligence & Data Science), **E-JUST**, 2026.

---

## Selected results

<table>
  <tr>
    <td align="center" width="34%">
      <h3>8,375 + 1,469</h3>
      <b>AraBIRD examples</b><br>
      <sub>Training + development splits in the Arabic BIRD adaptation</sub>
    </td>
    <td align="center" width="33%">
      <h3>73.6%</h3>
      <b>CCER-SQL execution accuracy</b><br>
      <sub>1,467 development questions across 11 databases</sub>
    </td>
    <td align="center" width="33%">
      <h3>24,601</h3>
      <b>Documents indexed</b><br>
      <sub>Fatwas in Tibyan's Arabic retrieval corpus</sub>
    </td>
  </tr>
</table>

<sub>These are dataset and project-specific figures, not general-purpose model benchmarks. CCER-SQL also reported 96.43% table Recall@5 in its development evaluation.</sub>

---

## Research / papers & reproducibility

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/AbdelrahmanAboegela/AraBIRD">AraBIRD</a></h3>
      <img alt="Accepted at NILES 2026" src="https://img.shields.io/badge/NILES_2026-ACCEPTED-0F766E?style=flat-square"><br><br>
      Modern Standard Arabic adaptation of BIRD for Text-to-SQL over English schemas. SQL-aware translation, consistency checks, and human review make the benchmark useful beyond a direct machine translation.
      <br><br><sub>Public dataset / research artifact</sub>
    </td>
    <td width="50%" valign="top">
      <h3>ShadowVeil</h3>
      <img alt="JAC-ECC 2026 conditionally accepted" src="https://img.shields.io/badge/JAC--ECC_2026-CONDITIONAL_ACCEPTANCE-64748B?style=flat-square"><br><br>
      Prospective counterfactual revocation for Mamba inference state. Investigates a state-level question in sequence-model behavior rather than treating inference as a stateless black box.
      <br><br><sub>Research repository planned for public release</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Beyond the Calibration Range</h3>
      <img alt="JAC-ECC 2026 conditionally accepted" src="https://img.shields.io/badge/JAC--ECC_2026-CONDITIONAL_ACCEPTANCE-64748B?style=flat-square"><br><br>
      Variable-selection robustness in Raman-based olive-oil adulteration quantification. Focuses on what survives when test conditions extend beyond the calibration range.
      <br><br><sub>Research repository planned for public release</sub>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/AbdelrahmanAboegela/D-Mask">D-Mask</a></h3>
      <img alt="Public reproducibility artifact" src="https://img.shields.io/badge/REPRODUCIBILITY-PUBLIC-0F766E?style=flat-square"><br><br>
      A reproducibility artifact examining a sparse, base-letter-invariant Arabic diacritic attack against LLM safety guards. A concrete example of why small input changes deserve serious evaluation.
      <br><br><sub>Public code / Arabic NLP / safety evaluation</sub>
    </td>
  </tr>
</table>

<sub>Conference statuses follow the current CV: AraBIRD is accepted at NILES 2026 (indexing pending); ShadowVeil and the Raman manuscript are conditionally accepted at JAC-ECC 2026. Links for the latter two can be added after their repositories are cleared for release.</sub>

---

## Systems / built and evaluated

| Project | What mattered technically | Source |
| :--- | :--- | :---: |
| **CCER-SQL** | Arabic Text-to-SQL pipeline with multilingual schema retrieval, foreign-key expansion, database profiling, execution-based ranking, and error-specific SQL refinement. | Private |
| **Tibyan** | Arabic RAG over 24,601 fatwas; hybrid BM25/RRF + vector retrieval, reranking, Neo4j expansion, citation checks, SSE streaming, and evaluation traces. | Private |
| **Dukkan** | Bilingual business assistant with voice/text tools, least-privilege actions, approval gates, idempotent writes, rollback, and post-action verification. | Private |
| **[GraphRAG Multi-View](https://github.com/AbdelrahmanAboegela/graphrag-multiview)** | Hybrid vector and graph search, with intent-aware selection of retrieval context. | Public |
| **[BandBridge](https://github.com/AbdelrahmanAboegela/BandBridge-Public)** | Experimental HONOR Band 6 to iPhone music-control bridge; a systems problem outside the usual ML stack. | Public |
| **[Azure Data Engineering Pipeline](https://github.com/AbdelrahmanAboegela/DEPI-Final-Data-Engineering-Task)** | Cloud data ingestion, transformation, and storage. | Public |

**What connects the work:** retrieval should be inspectable; model evaluation should survive stronger tests; tools that change state should be constrained and verifiable.

---

## Toolkit

**Modeling / evaluation**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=111827)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)

**Language systems / storage**

![LangGraph](https://img.shields.io/badge/LangGraph-101010?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-475569?style=flat-square)
![RAG](https://img.shields.io/badge/Hybrid_Retrieval-0F766E?style=flat-square)

**Application / infrastructure**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-111111?style=flat-square&logo=nextdotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square)

---

## GitHub activity

<p align="center">
  <img height="178" alt="GitHub repository and contribution statistics" src="https://github-readme-stats.vercel.app/api?username=AbdelrahmanAboegela&show_icons=true&hide_border=true&rank_icon=github&theme=transparent&cache_seconds=21600" />
  <img height="178" alt="GitHub contribution streak statistics" src="https://streak-stats.demolab.com/?user=AbdelrahmanAboegela&theme=transparent&hide_border=true" />
</p>

<p align="center">
  <img width="98%" alt="GitHub activity graph" src="https://github-readme-activity-graph.vercel.app/graph?username=AbdelrahmanAboegela&theme=github-compact&hide_border=true&area=true" />
</p>

<sub>GitHub widgets display what their public data sources can access; a substantial part of my work is in private repositories and is not fully represented here.</sub>

---

<p align="center">
  <strong>Interested in a research collaboration or a technically demanding build?</strong><br>
  <a href="mailto:abdelrahman.aboegela@gmail.com">Email</a> · <a href="https://www.linkedin.com/in/leby/">LinkedIn</a> · <a href="https://github.com/AbdelrahmanAboegela?tab=repositories">Explore public code</a>
</p>
