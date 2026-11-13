# Shilpa Musale

### AI / ML Engineer · LLM Evaluation · Healthcare Data

[<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />](https://linkedin.com/in/shilpamusale)
[<img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />](mailto:shilpa.musale02@gmail.com)
[<img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" />](https://orcid.org/0009-0001-6334-0614)

📍 Chicago, IL · Open to AI/ML Engineer roles

---

I build and evaluate ML and LLM systems, with healthcare claims and clinical data as the proving ground.

- **10 years at R1 RCM**: progressed from software developer to Technology Lead and owned the Denials & Follow-up product across all client health systems, including human-in-the-loop review by denial specialists.
- **Evaluation first**: gold sets, multi-trial scoring, error analysis and CI regression gates. On a clinical LLM agent, error analysis raised the pass rate from **75% to 92%**.
- **Research**: co-author of peer-reviewed work on predicting readmissions from Community Health Worker data.

---

## Selected Projects

| Project | Description | Key Technologies |
|---|---|---|
| **[vertex-care](https://github.com/shilpamusale/vertex-care)** | Clinical LLM agent that drafts Community Health Worker intervention plans, built on my peer-reviewed readmission research. Its evaluation harness uses a 30-case gold set, 3 trials per case and a record-and-replay CI gate; error analysis raised the pass rate from 75% to 92%. | `Gemini API`, `ReAct`, `FastAPI`, `GCP Cloud Run`, `Vertex AI`, `GitHub Actions` |
| **[priorauth-ai](https://github.com/shilpamusale/priorauth-ai)** | Agentic prior-authorization workflow. Takes FHIR R4 bundles through policy retrieval and criteria matching, then routes each request to submission, documentation follow-up or human review. Decisions are computed in code from cited evidence, with an audit trail and a gold-set CI gate. | `Claude API`, `Pydantic`, `ChromaDB`, `Pytest`, `GitHub Actions` |
| **[claim-triage-ai](https://github.com/shilpamusale/claim-triage-ai)** | Denial prediction, denial-reason clustering and rule-based A/R work routing on simulated claims, served through FastAPI. | `XGBoost`, `LightGBM`, `Sentence-BERT`, `UMAP`, `HDBSCAN`, `FastAPI`, `Docker` |
| **[scholar-agent](https://github.com/shilpamusale/scholar-agent)** | Multi-agent research assistant that routes each question to Neo4j graph queries or vector search, with bounded retries and a routing policy unit-tested without a model. | `LangGraph`, `LangChain`, `Gemini API`, `Neo4j`, `ChromaDB` |
| **Cross-Site Otoscopy Domain Adaptation** | Cross-site deep-learning study with Northwestern Feinberg and Rosalind Franklin University. Benchmarked three domain-adaptation methods (DANN, MCC, CORAL) on a ResNet50 classifier and used occlusion analysis to test robustness vs. shortcut learning. *(co-first author; submitted for publication)* | `PyTorch`, `ResNet50`, `Domain Adaptation` |

---

## Publications

- [Leveraging Community Health Workers for Predicting Emergency Department Readmissions](https://www.worldscientific.com/doi/abs/10.1142/S1793351X24420030) — *International Journal of Semantic Computing*, Vol. 18, No. 01, April 2024
- [Harnessing Machine Learning to Optimize Community Health Worker Interventions for High-Risk Patients](https://doi.org/10.1007/978-3-032-29003-8_5) — *Computers and Their Applications*, Springer Nature Switzerland, 2026
- **Cross-Site Generalization in Otoscopy Deep Learning** — *Submitted for publication* (co-first author)

---

## Skills & Tools

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" alt="scikit-learn"/>
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude API"/>
  <img src="https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini API"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain"/>
  <img src="https://img.shields.io/badge/LangGraph-000000?style=flat-square&logo=langgraph&logoColor=white" alt="LangGraph"/>
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white" alt="Pydantic"/>
  <img src="https://img.shields.io/badge/Vertex_AI-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="Vertex AI"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/GitHub--Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" alt="MLflow"/>
  <img src="https://img.shields.io/badge/Weights_&_Biases-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black" alt="Weights & Biases"/>
  <img src="https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white" alt="Neo4j"/>
</p>

**Evaluation:** gold sets · multi-trial scoring · error analysis · CI regression gates · record-and-replay

**Healthcare:** Epic · HL7 v2 · FHIR R4 · EDI 837/835 · ICD-10 · CPT · denials · prior authorization · HIPAA/PHI
