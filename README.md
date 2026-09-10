<!-- DESIGN A: RESEARCH DOSSIER -->

<div align="center">

Md Shoaib Uddin Chanda

Machine Learning Research · Robustness · Research Engineering

Published Paper ·
GitHub ·
LinkedIn ·
Email

</div>

Profile

I work on reliable empirical machine learning: robustness, tabular learning, calibration, distribution shift, class imbalance, and reproducible evaluation.

My central question is:

What happens when the assumptions behind a clean ML benchmark stop being true?

Research dossier

Published

Revisiting training-free tabular models: A robustness and efficiency study
Array, 31 (2026), 101049

Question. Does training-free tabular classification remain competitive under realistic degradation and computational constraints?

Protocol. 17 datasets · 15 seeds · 13 conditions · 19,890 evaluations.

Result. Classical and gradient-boosted baselines generally provide stronger accuracy–runtime trade-offs; tuned HyperFast retains a narrower advantage on some difficult, highly imbalanced settings.

Links: Paper · Code

Under review — Neural Networks

When Labels Lie and Classes Skew: Robust Tabular Deep Learning via Confidence-Calibrated Reweighting

Question. Can a tabular neural network remain robust when class imbalance and asymmetric label noise occur together?

Method. Confidence-aware detached sample reweighting + per-batch normalized weights.

Protocol. 14 datasets in a 10 + 2 + 2 structure · 9 loss baselines · tree ensembles · gradient attribution · ablations · architecture transfer.

Links: Code

Under review — Knowledge-Based Systems

When More Features Hurt: Feature-Synthesis Variance Amplification in Automated Feature Engineering

Question. When does automated arithmetic feature synthesis improve generalization, and when does it amplify variance and cost?

Mechanism. Feature-Synthesis Variance Amplification (FSVA).

Configured design. 25 datasets · 5 seeds × 5 folds · 14 conditions · 7 pipelines · 10 classifiers.

Confirmatory scope. 22 substantially completed datasets · 538,972 evaluation records.

Links: Code · Manuscript

Research projects

Calibration Collapse Under Class Imbalance
Minority-class probability reliability under imbalance, resampling, and post-hoc calibration.
Repository

AutoPrepML
Leakage-safe fitted preprocessing, contracts, schema validation, fingerprints, lineage, artifacts, and experiment integrations.
Repository

SentinelTrack
RTSP/HLS ingest → YOLO → ByteTrack → plate localization → OCR → target matching → PostGIS route reconstruction.
Repository

ZombieGuard
Defensive ZIP structural-evasion scanner with bounded parsing, LightGBM, model/data cards, CI, and explicit limitations.
Repository

Research stack

Python · PyTorch · scikit-learn · XGBoost · LightGBM · OpenCV · OpenML · FastAPI · PostgreSQL · Redis · Docker · Linux · GitHub Actions · LaTeX

Current direction

Research: robust ML · tabular learning · distribution shift · calibration · evaluation methodology
Engineering: research infrastructure · ML systems · CV · MLOps
Open to: Master's research · RA roles · robust-ML collaborations · reproducibility projects

<div align="center">

Evidence over claims. Reproducibility over decoration. Reliability beyond clean benchmarks.

</div>
