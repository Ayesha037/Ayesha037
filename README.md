# Hi, I'm Ayesha 👋

### I build AI for health, and I test whether it deserves to be trusted.

A model that scores 82% in a notebook can fall to about 41% on a case it has never seen. In medicine, that gap is not a rounding error. **I look for that gap before someone relies on it.**

[Portfolio](https://portfolio-clean-sigma.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/mohammad-ayesha-summaiyya-b94351333) · [msumaiya03579@gmail.com](mailto:msumaiya03579@gmail.com)

---

## The thread running through my work

**Medical AI should come with evidence that it works, and with honest limits.**
My projects ask the uncomfortable question: *does it still hold when the data changes, when the sources are weak, when a vulnerable person is on the other end?*

---

## Research

| | |
|---|---|
| 🧫 **Apparent Performance of Antimicrobial Resistance Phenotype Prediction Depends on the Definition of an Unseen Observation** | Zenodo preprint · first author · 2026 · [DOI 10.5281/zenodo.22976451](https://doi.org/10.5281/zenodo.22976451) |
| 🫁 **ML-Based Prediction of Recurrence in Non-Small Cell Lung Cancer** | *International Scientific Journal of Engineering and Management* · lead author · April 2026 · [DOI 10.55041/ISJEM06362](https://doi.org/10.55041/ISJEM06362) |

---

## Selected work

### 🧫 When antimicrobial-resistance models look better than they are
[`AMR-Project`](https://github.com/Ayesha037/AMR-Project)
Antimicrobial resistance is a major public-health threat in Europe and worldwide. I compared four classifiers under four evaluation regimes on 801 BV-BRC observations. Accuracy falls from 0.824 under a random split to 0.406 under leave-one-species-out. Leakage-aware evaluation, not a bigger model, exposed the gap.
*Limits:* small dataset, so this is a methodological demonstration, not a clinical claim.

### 🧬 BioGenesis: can evidence structure make biomedical AI more trustworthy?
[`biogenesis`](https://github.com/Ayesha037/biogenesis) · *research in progress*
A multi-agent system that retrieves PubMed papers, scores evidence, builds a knowledge graph, and must cite papers for every hypothesis, then checks whether each citation really supports the claim. Nine configurations (3 baselines, the full system, 5 ablations) on a 40-question benchmark. Baselines and the full system have run; the ablations and a clean re-run are under way. I publish failure modes next to results, including the ones that don't flatter the system.

### 💬 Mental health support chatbot, live and open to anyone
[`MENTAL_HEALTH_SUPPORT`](https://github.com/Ayesha037/MENTAL_HEALTH_SUPPORT) · prototype
Emotion analysis, supportive dialogue, crisis-keyword detection with helpline escalation, and voice support, built with faculty guidance. It is a prototype, not a clinical tool. Next: counsellor review of the crisis flow and feedback from real users.

### ⚙️ MediGuard AI: predictive-maintenance pipeline
[`MediGuard-AI`](https://github.com/Ayesha037/MediGuard-AI)
End-to-end failure prediction (XGBoost, LightGBM, Isolation Forest, SHAP explanations, FastAPI, Docker, CI) on **public industrial machine datasets** (Azure Predictive Maintenance, AI4I). It demonstrates data-engineering and MLOps practice, not hospital data.

*Smaller experiments:* RAG document assistant, lead scoring, GraphShield, safety monitor.

---

## Building, not just studying

- Selected for incubation at the **A.P.J. Abdul Kalam Center of Excellence and Innovation** and awarded **₹2.5 lakh** to develop an idea.
- Led the innovation club **Innofy** as president and organised a week-long programme with a hackathon and a business simulation.

---

## Tools

Python · scikit-learn · XGBoost · SHAP · PyTorch · NLP · RAG (LangChain, FAISS, Chroma) · NetworkX · FastAPI/Flask · SQL · Docker · GitHub Actions

---

## How I work

Question → evidence → build → **evaluate honestly** → explain → ship.
I test under the strictest split I can defend and report the number that survives. Every serious repo has a "Known limitations" section.

## Right now

Finishing the BioGenesis ablations on one clean code version. Open to research collaborations in healthcare AI, evaluation and reproducibility.
