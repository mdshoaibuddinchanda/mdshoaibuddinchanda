<!-- =========================================================
DESIGN 3 — ACADEMIC MAGAZINE
Visual: editorial / journal / professor-facing
No custom assets. Minimal external visuals, but still colorful.
========================================================= -->

<div align="center">

Md Shoaib Uddin Chanda

Machine Learning Researcher · Research Engineer

Robust ML · Tabular Learning · Distribution Shift · Calibration · Reproducibility

<br/>

<a href="https://doi.org/10.1016/j.array.2026.101049"><img src="https://img.shields.io/badge/PUBLISHED-Array%202026-F59E0B?style=for-the-badge&logo=elsevier&logoColor=white"/></a>
<a href="https://github.com/mdshoaibuddinchanda"><img src="https://img.shields.io/badge/CODE-GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://linkedin.com/in/mdshoaibuddinchanda"><img src="https://img.shields.io/badge/PROFILE-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>

</div>

Research statement

I am interested in reliable empirical machine learning: not only whether a model performs well on a clean benchmark, but whether the conclusion survives noise, missingness, imbalance, distribution shift, calibration analysis, computational constraints, and reproducibility checks.

Research themes

Robustness

Reliability

Evaluation

Engineering

Noise, missingness, scarcity

Calibration, minority behavior

Statistics, ablations, stress tests

Reproducible pipelines, ML systems

Selected publications & manuscripts

I. Revisiting training-free tabular models: A robustness and efficiency study

Array · Volume 31 · 2026 · Article 101049 · Published

This study evaluates HyperFast against classical and gradient-boosted baselines under clean and degraded tabular-data conditions. The goal is not simply to report a clean-test leaderboard, but to measure robustness and computational trade-offs.

Experimental scale: 17 datasets · 15 random seeds · 13 conditions · 19,890 evaluations

Result in one sentence: classical and gradient-boosted models generally provide stronger accuracy–runtime trade-offs, while tuned HyperFast retains a narrower advantage on some difficult and highly imbalanced settings.

Paper: https://doi.org/10.1016/j.array.2026.101049
Code: https://github.com/mdshoaibuddinchanda/hyperfast-robustness-evaluation

II. When Labels Lie and Classes Skew

Robust Tabular Deep Learning via Confidence-Calibrated Reweighting

Neural Networks · Manuscript under review

CCR studies a setting where class imbalance and asymmetric label noise occur together. It combines confidence-aware detached sample reweighting with per-batch normalization to investigate robust learning without conflating directional reweighting with global optimization-scale changes.

Evaluation scope: 14 datasets in a 10 + 2 + 2 structure, 9 loss baselines, tree-ensemble comparisons, gradient attribution, ablations, optimizer studies, and architecture transfer.

Code: https://github.com/mdshoaibuddinchanda/CCR-Tabular

III. When More Features Hurt

Feature-Synthesis Variance Amplification in Automated Feature Engineering

Knowledge-Based Systems · Manuscript under review

The work studies a common AutoML assumption: that a larger synthesized feature space should improve predictive performance. It proposes Feature-Synthesis Variance Amplification (FSVA) as a mechanism by which feature generation can instead increase perturbation sensitivity, redundancy, estimator variance, and computational cost.

Configured benchmark: 25 datasets · 5 seeds × 5 folds · 14 conditions · 7 pipelines · 10 classifiers
Confirmatory scope: 22 substantially completed datasets · 538,972 evaluation records

The bounded conclusion is that unrestricted synthesis did not improve generalization in the completed benchmark scope; constrained addition/subtraction synthesis stayed much closer to capped raw-feature baselines. The manuscript does not claim that AutoFE is universally harmful.

Code: https://github.com/mdshoaibuddinchanda/AutoFE-ShiftBench
Manuscript: https://github.com/mdshoaibuddinchanda/AutoFE-ShiftBench/blob/main/paper/manuscript.tex

Research program

flowchart LR
    A["Robustness"] --> X["Reliable empirical ML"]
    B["Calibration"] --> X
    C["Distribution shift"] --> X
    D["Reproducibility"] --> X
    X --> E["Better evaluation"]
    X --> F["Research engineering"]

Supporting research

Calibration Collapse — class-conditional calibration under imbalance, resampling, and post-hoc calibration.
Repository: https://github.com/mdshoaibuddinchanda/calibration-collapse

Research engineering portfolio

<table>
<tr>
<td width="50%" valign="top">

<h3>AutoPrepML</h3>
<p><strong>ML data-readiness framework</strong></p>
<p>Leakage-safe fitted preprocessing, contracts, validation, fingerprints, lineage, serializable artifacts, storage abstractions, CLI workflows, and experiment integrations.</p>
<p><a href="https://github.com/mdshoaibuddinchanda/autoprepml"><strong>Open project</strong></a></p>

</td>
<td width="50%" valign="top">

<h3>SentinelTrack</h3>
<p><strong>Multi-camera vehicle intelligence</strong></p>
<p>RTSP/HLS ingest, YOLO vehicle detection, ByteTrack, plate localization, OCR, target matching, and GIS-backed route reconstruction.</p>
<p><a href="https://github.com/mdshoaibuddinchanda/sentineltrack"><strong>Open project</strong></a></p>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3>ZombieGuard</h3>
<p><strong>Defensive structural-evasion scanner</strong></p>
<p>Bounded ZIP parsing, LightGBM classification, reproducible evaluation, confidence intervals, data/model cards, explicit limitations, and CI.</p>
<p><a href="https://github.com/mdshoaibuddinchanda/zombieguard"><strong>Open project</strong></a></p>

</td>
<td width="50%" valign="top">

<h3>Nexus AutoML Platform</h3>
<p><strong>Reproducible ML experimentation workspace</strong></p>
<p>FastAPI, PostgreSQL, Redis, Celery, React/TypeScript, immutable dataset versions, experiment artifacts, worker execution, and ownership boundaries.</p>
<p><a href="https://github.com/mdshoaibuddinchanda/Nexus-AutoML-Platform"><strong>Open project</strong></a></p>

</td>
</tr>
</table>

Technical toolkit

<div align="center">

Machine learning

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/>
<img src="https://img.shields.io/badge/XGBoost-166534?style=for-the-badge"/>
<img src="https://img.shields.io/badge/LightGBM-0369A1?style=for-the-badge"/>

Systems

<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>

</div>

Experience

Role

Organisation

Period

Focus

AI & Software Engineering Intern

Delloyd R&D, Malaysia

Sep 2025 – Mar 2026

Computer vision, ANPR/OCR, synthetic data, GPU workflows

Research & Data Analysis Intern

Hyderabad City Police / HCSC project

Apr 2026 – May 2026

Operational analytics, reporting, process evaluation

Technical Head

ACM Student Chapter

2024 – 2026

Workshops, mentoring, technical leadership

AI / ML Intern

RAM INFOTECH

2023

Computer vision, XGBoost, feature engineering

<div align="center">

Current direction

Master's research · Research assistant roles · Robust ML collaborations · Reproducibility · Research engineering

<br/>

LinkedIn · GitHub · Email

<br/>

Evidence over claims. Reproducibility over decoration. Reliability beyond clean benchmarks.

</div>
