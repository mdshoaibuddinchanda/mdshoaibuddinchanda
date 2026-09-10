<!-- =========================================================
DESIGN 2 — RESEARCH TERMINAL
Visual: terminal / hacker-lab / compact
No HTML project tables. No custom assets.
========================================================= -->

<div align="center">

Md Shoaib Uddin Chanda

researcher@robust-ml:~$

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=18&duration=2200&pause=700&color=39FF14&center=true&vCenter=true&width=900&lines=whoami+%E2%86%92+Machine+Learning+Researcher;focus+%E2%86%92+robustness+%7C+tabular+ML+%7C+calibration;status+%E2%86%92+1+published+%7C+2+under+review;mode+%E2%86%92+research+%2B+engineering" alt="Terminal typing animation"/>






</div>

$ cat research_identity.txt

I study what happens when clean machine-learning assumptions break.

core/
├── robust_machine_learning
├── tabular_learning
├── distribution_shift
├── calibration_and_imbalance
├── empirical_evaluation
└── reproducible_research_engineering

papers/

01_published.array

Revisiting training-free tabular models: A robustness and efficiency study
Array 31 (2026) 101049

datasets     = 17
seeds        = 15
conditions   = 13
evaluations  = 19,890

stressors    = Gaussian noise
               MCAR missingness
               data scarcity
               runtime constraints

The study evaluates whether a training-free tabular classifier remains competitive once the benchmark is no longer clean. Classical and gradient-boosted baselines generally provide stronger accuracy–runtime trade-offs; tuned HyperFast shows narrower advantages in some difficult, highly imbalanced settings.

PAPER · CODE

02_under_review.ccr

When Labels Lie and Classes Skew: Robust Tabular Deep Learning via Confidence-Calibrated Reweighting
Neural Networks — manuscript under review

problem      = class imbalance + asymmetric label noise
method       = confidence-aware detached reweighting
stability    = per-batch normalized sample weights
benchmark    = 10 core + 2 multiclass + 2 clinical datasets
comparators  = 9 losses + tree ensembles
evidence     = ablations + gradient attribution + architecture transfer

CCR is designed to suppress corrupted learning signal without confusing per-sample reweighting with global gradient-scale changes.

CODE

03_under_review.fsva

When More Features Hurt: Feature-Synthesis Variance Amplification in Automated Feature Engineering
Knowledge-Based Systems — manuscript under review

configured   = 25 datasets
seeds/folds  = 5 x 5
conditions   = 14
pipelines    = 7
classifiers  = 10

confirmatory = 22 substantially completed datasets
records      = 538,972

The manuscript formulates Feature-Synthesis Variance Amplification (FSVA): feature synthesis can increase perturbation sensitivity, redundancy, estimator variance, and cost. In the completed evidence scope, unrestricted synthesis does not improve generalization; constrained addition/subtraction synthesis stays much closer to capped raw-feature baselines.

CODE · MANUSCRIPT

research_projects/

<details>
<summary><b>Calibration Collapse</b> — minority calibration under imbalance</summary>

<br/>

Studies when global calibration metrics hide class-conditional failure. Focus: per-class ECE, minority recall, resampling/calibration interaction, synthetic severity sweeps, and leakage-aware evaluation.

OPEN REPOSITORY

</details>

<details>
<summary><b>AutoPrepML</b> — ML data-readiness infrastructure</summary>

<br/>

Leakage-safe fitted preprocessing, data contracts, validation, fingerprints, lineage, serializable artifacts, storage abstractions, and experiment integrations.

OPEN REPOSITORY

</details>

<details>
<summary><b>SentinelTrack</b> — multi-camera vehicle intelligence</summary>

<br/>

RTSP/HLS → YOLO → ByteTrack → plate detection → OCR → target matching → PostGIS route reconstruction.

OPEN REPOSITORY

</details>

<details>
<summary><b>ZombieGuard</b> — structural ZIP evasion scanner</summary>

<br/>

Bounded ZIP parsing + LightGBM + reproducible evaluation + data/model cards + explicit limitations.

OPEN REPOSITORY

</details>

toolchain/

ML          Python · PyTorch · scikit-learn · XGBoost · LightGBM · OpenCV
Research    OpenML · experimental design · Wilcoxon · benchmarking · LaTeX
Systems     FastAPI · PostgreSQL · Redis · Docker · Linux · GitHub Actions

<div align="center">

<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,opencv,sklearn,fastapi,postgres,redis,docker,linux,githubactions,git,latex" alt="Technical stack"/>

</div>

currently_open_to/

masters_research: true
research_assistant_roles: true
robust_ml_collaboration: true
reproducibility_projects: true
research_engineering: true

<div align="center">

evidence > hype · reproducibility > screenshots · failure analysis > leaderboard chasing

</div>
