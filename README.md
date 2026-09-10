<div align="center">

<img src="./assets/profile-hero.gif" width="100%" alt="Md Shoaib Uddin Chanda — Machine Learning Researcher and Research Engineer"/>

<br/>

<a href="https://doi.org/10.1016/j.array.2026.101049"><b>Published Paper</b></a>
  ·  
<a href="https://github.com/mdshoaibuddinchanda"><b>GitHub</b></a>
  ·  
<a href="https://linkedin.com/in/mdshoaibuddinchanda"><b>LinkedIn</b></a>
  ·  
<a href="mailto:mdshoaibuddinchanda@gmail.com"><b>Email</b></a>

<br/><br/>

<img src="./assets/research-flow.gif" width="100%" alt="Research flow: question to experiment to evidence to system"/>

</div>

Research identity

I study what happens when the assumptions behind clean machine-learning benchmarks stop being true.

My work centers on robust machine learning, tabular learning, distribution shift, calibration, and reproducible experimentation. Alongside the research, I build the software infrastructure needed to make experiments inspectable, repeatable, and useful outside a notebook.

<table>
<tr>
<td align="center" width="25%"><b>ROBUSTNESS</b><br/><sub>noise · missingness · scarcity</sub></td>
<td align="center" width="25%"><b>RELIABILITY</b><br/><sub>calibration · imbalance · uncertainty</sub></td>
<td align="center" width="25%"><b>EVALUATION</b><br/><sub>controlled experiments · statistics</sub></td>
<td align="center" width="25%"><b>ENGINEERING</b><br/><sub>reproducibility · ML systems</sub></td>
</tr>
</table>

Research papers

<table>
<tr>
<td width="33%" valign="top">

01 · Published

Revisiting training-free tabular models: A robustness and efficiency study

Array · 31 (2026) · 101049

A systematic stress test of training-free tabular classification. The study compares HyperFast with classical and gradient-boosted baselines across degraded-data and computational conditions rather than judging models only on clean benchmarks.

Evidence

17 binary-classification datasets

15 random seeds

13 conditions per dataset

19,890 model evaluations

noise, MCAR missingness, data scarcity

separate accuracy and runtime analysis

Main result: classical and gradient-boosted baselines generally provided stronger accuracy–runtime trade-offs; tuned HyperFast showed a narrower advantage on some difficult, highly imbalanced settings.

Paper / DOI
Reproducibility code

</td>
<td width="33%" valign="top">

02 · Under review

Confidence-Calibrated Reweighting (CCR)

Neural Networks · manuscript under review

A robust tabular-learning method for the joint problem of class imbalance and asymmetric label noise. CCR uses detached confidence-aware sample weighting together with per-batch normalization so that the direction of reweighting can be studied separately from global gradient-scale changes.

Research scope

structured 10 + 2 + 2 benchmark

14 datasets

9 loss-function baselines

tree-ensemble comparisons

gradient attribution and ablations

architecture-transfer experiments

Reported repository evidence: under severe 40% asymmetric noise, CCR preserves minority recall better than cross-entropy in the evaluated benchmark while reducing corrupted-sample gradient mass and gradient-norm volatility.

Research code

</td>
<td width="33%" valign="top">

03 · Under review

When More Features Hurt: Feature-Synthesis Variance Amplification in Automated Feature Engineering

Knowledge-Based Systems · manuscript under review

This study asks whether automated arithmetic feature synthesis improves robust generalization or instead amplifies perturbations, redundancy, variance, and computational cost. It formulates the mechanism as Feature-Synthesis Variance Amplification (FSVA).

Configured design

25 OpenML datasets

5 seeds × 5 folds

14 training-data conditions

7 feature pipelines

10 classifiers

Confirmatory scope: 22 datasets with substantial completed coverage and 538,972 evaluation records. In this evidence scope, unrestricted synthesis did not improve generalization; constrained addition/subtraction synthesis remained much closer to capped raw-feature baselines. The manuscript explicitly does not claim that AutoFE is universally harmful.

Research code
Manuscript source

</td>
</tr>
</table>

The common thread

<table>
<tr>
<td width="33%" valign="top" align="center">

Stress the assumption

Clean benchmarks can hide failure.

noise · missingness · imbalance
shift · limited data

</td>
<td width="33%" valign="top" align="center">

Measure the failure

Evaluation should expose mechanism, not only a leaderboard rank.

paired comparisons · ablation
calibration · gradient evidence

</td>
<td width="33%" valign="top" align="center">

Make it reproducible

The result should be inspectable beyond the manuscript.

code · configs · seeds
artifacts · validation

</td>
</tr>
</table>

Additional research

<table>
<tr>
<td width="50%" valign="top">

Calibration Collapse Under Class Imbalance

A research framework studying how imbalance, resampling, and post-hoc calibration change minority-class probability reliability.

The project is built around the observation that a global calibration score can remain deceptively small when the minority class contributes only a small fraction of the samples. It therefore emphasizes per-class ECE, minority recall, calibration–recall trade-offs, controlled synthetic severity sweeps, and leakage-aware experimental structure.

Current repository scope: real tabular datasets plus controlled synthetic stress tests, with experiment tracking, calibration methods, resampling strategies, and reproducibility checks.

Explore calibration-collapse →

</td>
<td width="50%" valign="top">

Why these projects belong together

My research is not organized around one model family.

It is organized around a recurring question:

What does the evaluation hide?

HyperFast tests whether “training-free” remains advantageous under degradation and deployment-time cost.

CCR tests what happens when imbalance and asymmetric label noise interact.

AutoFE-ShiftBench tests whether larger synthesized feature spaces remain useful under controlled corruption.

Calibration Collapse tests whether aggregate calibration metrics hide minority-class failure.

That common evaluation perspective is the research direction I want to deepen.

</td>
</tr>
</table>

Research engineering

<table>
<tr>
<td width="50%" valign="top">

AutoPrepML

ML data-readiness framework

A released Python framework for turning raw data into validated, reproducible ML-ready transformations.

The project centers on train-only fitted preprocessing, data contracts, schema validation, dataset fingerprints, transformation lineage, serializable preprocessing artifacts, CLI workflows, storage abstractions, and experiment integrations.

Engineering emphasis

leakage-safe fit/transform · contracts · fingerprints
lineage · artifact integrity · cross-platform CI

Explore AutoPrepML →

</td>
<td width="50%" valign="top">

SentinelTrack

Multi-camera vehicle intelligence and ANPR

A production-oriented computer-vision pipeline that connects stream ingestion to cross-camera vehicle reasoning.

System path

RTSP / HLS ingest → YOLO vehicle detection → ByteTrack
→ plate localization → OCR → target matching
→ PostGIS-backed route reconstruction

The project combines model inference with tracking state, plate-quality handling, multi-frame OCR consensus, watchlist matching, and spatio-temporal trajectory logic.

Explore SentinelTrack →

</td>
</tr>
<tr>
<td width="50%" valign="top">

ZombieGuard

Defensive scanner for structural metadata evasion in ZIP archives

ZombieGuard checks contradictions between ZIP local-file headers, central-directory records, and payload characteristics. It combines a bounded structural parser with a small LightGBM model.

The project deliberately does not claim malware detection. Its scope is structural archive-evasion signals, with explicit unscannable states, reproducible evaluation, data/model cards, integrity metadata, and documented limitations.

Explore ZombieGuard →

</td>
<td width="50%" valign="top">

Nexus AutoML Platform

Reproducible full-stack ML experimentation workspace

A portfolio-scale platform for immutable dataset versions, supervised classification experiments, worker execution, experiment artifacts, and server-enforced ownership boundaries.

System components

FastAPI · PostgreSQL · Redis · Celery
React / TypeScript · Docker · MLflow integration

The repository documents the difference between implemented software and the external operational controls required for a real SaaS deployment.

Explore Nexus →

</td>
</tr>
</table>

Experience

<table>
<tr>
<td width="50%" valign="top">

AI & Software Engineering Intern

Delloyd R&D · Malaysia · Sep 2025 – Mar 2026

Computer vision, ANPR/OCR workflows, synthetic-data generation, and GPU-oriented model engineering.

</td>
<td width="50%" valign="top">

Research & Data Analysis Intern

Hyderabad City Security Council / Hyderabad City Police project · Apr 2026 – May 2026

Operational analytics, data-driven reporting, documentation, and process evaluation in a public-safety context.

</td>
</tr>
<tr>
<td width="50%" valign="top">

Technical Head

ACM Student Chapter · 2024 – 2026

Technical workshops, student mentoring, project guidance, and open-source/AI community activity.

</td>
<td width="50%" valign="top">

AI / Machine Learning Intern

RAM INFOTECH · 2023

Machine-learning and computer-vision work including XGBoost, feature engineering, and facial-expression/stress-related workflows.

</td>
</tr>
</table>

Technical toolkit

<table>
<tr>
<td width="33%" valign="top" align="center">

Machine learning

Python
PyTorch
scikit-learn
XGBoost
LightGBM
OpenCV

</td>
<td width="33%" valign="top" align="center">

Research

Experimental design
Robustness evaluation
Statistical testing
Benchmarking
Reproducibility
LaTeX

</td>
<td width="33%" valign="top" align="center">

Systems

FastAPI
PostgreSQL
Redis
Docker
Linux
GitHub Actions

</td>
</tr>
</table>

Current direction

<table>
<tr>
<td width="50%" valign="top">

Research I want to deepen

robust and trustworthy machine learning

tabular learning

distribution shift

calibration and uncertainty

empirical evaluation methodology

reproducible ML research

</td>
<td width="50%" valign="top">

Open to

Master's research opportunities

research assistant roles

reproducibility collaborations

robust-ML / reliable-AI projects

research-engineering collaborations

</td>
</tr>
</table>

<div align="center">

Contact

Research · Graduate study · Research engineering

LinkedIn
  ·  
GitHub
  ·  
Email

<br/>

Building reliable ML systems — and testing the assumptions benchmarks usually leave untouched.

</div>
