<h1 align="center">Ayesha Summaiyya</h1>
<h3 align="center">I find out when medical AI stops working.</h3>

<p align="center">
A model that scores <b>82%</b> in a notebook can fall to <b>41%</b> on a case it has never seen.<br>
In medicine, that gap is not a rounding error. I look for it before someone relies on it.
</p>

<p align="center">
<a href="https://doi.org/10.5281/zenodo.22976451">Preprint (first author)</a> ·
<a href="https://doi.org/10.55041/ISJEM06362">Journal paper (lead author)</a> ·
<a href="https://portfolio-clean-sigma.vercel.app/">Portfolio</a> ·
<a href="https://www.linkedin.com/in/mohammad-ayesha-summaiyya-b94351333">LinkedIn</a> ·
<a href="mailto:msumaiya03579@gmail.com">Email</a>
</p>

---

## Start here

| If you have 1 minute | Read |
|---|---|
| The finding | [**AMR-Project**](https://github.com/Ayesha037/AMR-Project): accuracy falls from 0.824 to 0.406 when "unseen" is defined honestly |
| The ambition | [**BioGenesis**](https://github.com/Ayesha037/biogenesis): biomedical AI that must show and verify its evidence |
| The human side | [**Mental health chatbot**](https://github.com/Ayesha037/MENTAL_HEALTH_SUPPORT): crisis escalation, built to be reviewed by counsellors |

---

## Research

| | |
|---|---|
| 🧫 **Apparent Performance of Antimicrobial Resistance Phenotype Prediction Depends on the Definition of an Unseen Observation** | Zenodo preprint · first author · 2026 · [DOI 10.5281/zenodo.22976451](https://doi.org/10.5281/zenodo.22976451) |
| 🫁 **ML-Based Prediction of Recurrence in Non-Small Cell Lung Cancer** | *International Scientific Journal of Engineering and Management* · lead author · April 2026 · [DOI 10.55041/ISJEM06362](https://doi.org/10.55041/ISJEM06362) |

**Research direction:** why biomedical ML results look better than they are, and how to build systems that stay honest about what they know. That means **evaluation design** (how "unseen" is defined) and **evidence-grounded generation** (an AI that shows, and has checked, its sources).

---

## Featured projects

### 🧫 AMR-Project · *does the accuracy survive?*
Four classifiers, four evaluation regimes, 801 BV-BRC observations.
**Result:** accuracy falls from **0.824** (random split) to **0.406** (leave-one-species-out).
**Setup:** [[ADD: the four regimes in one line each, the metric, and what "unseen" means]]
**Limits:** small dataset (41 genomes, 5 species). A methodological result, not a clinical claim.
→ [Repository](https://github.com/Ayesha037/AMR-Project) · [Preprint](https://doi.org/10.5281/zenodo.22976451)

### 🧬 BioGenesis · *can an AI show its evidence?*
```
Question → Planner → PubMed retrieval → Evidence scoring → Knowledge graph
        → Hypotheses that must cite papers → Critic → Citation-support check
```
Nine configurations (3 baselines, the full system, 5 ablations) on one code path and a 40-question benchmark, so every design choice can be measured.
**Status:** *research prototype.* [[UPDATE after rerun, e.g. "baselines and full system run; ablations in progress"]]
**Limits:** documented in the repo, including the failure modes.
→ [Repository](https://github.com/Ayesha037/biogenesis)

### 💬 Mental health support chatbot · *what if someone vulnerable is on the other end?*
Emotion-aware replies, crisis-keyword escalation to helplines, voice support. Built with faculty guidance.
**Status:** live prototype. Next: counsellor review of the crisis flow and feedback from real users.
→ [Repository](https://github.com/Ayesha037/MENTAL_HEALTH_SUPPORT)

### ⚙️ MediGuard AI · *engineering, end to end*
Failure prediction with XGBoost, LightGBM and SHAP behind a FastAPI service with Docker and CI, on public industrial datasets.
→ [Repository](https://github.com/Ayesha037/MediGuard-AI)

---

## Beyond code

- Selected for incubation at the **A.P.J. Abdul Kalam Center of Excellence and Innovation**; awarded **₹2.5 lakh** to develop an idea.
- **President, Innofy innovation club:** a week-long programme with a hackathon and a business simulation.

---

> **Every claim on this page links to proof.** If I can't show it, I don't say it.

📧 [msumaiya03579@gmail.com](mailto:msumaiya03579@gmail.com) · Open to research collaborations in healthcare AI, evaluation and reproducibility.
