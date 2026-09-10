<!-- DESIGN B: VISUAL LAB NOTEBOOK -->

<div align="center">

LAB NOTEBOOK // SHOIAB

robust_ml / tabular_ai / calibration / reproducibility

<img src="https://readme-typing-svg.herokuapp.com?font=IBM+Plex+Mono&weight=600&size=17&duration=2400&pause=650&color=00C2FF&center=true&vCenter=true&width=900&lines=01+%2F+ask+the+question;02+%2F+stress+the+assumption;03+%2F+measure+the+failure;04+%2F+publish+the+evidence" alt="Research notebook animation"/>

</div>

ENTRY 001 — Published robustness study

Revisiting training-free tabular models: A robustness and efficiency study
Array · 2026 · 101049

Hypothesis
Training-free performance may not remain advantageous once realistic noise, missingness, data scarcity, and runtime constraints are introduced.

Experiment

17 datasets
15 random seeds
13 conditions
19,890 total evaluations

Observation
Classical and gradient-boosted baselines generally deliver stronger accuracy–runtime trade-offs. Tuned HyperFast retains a narrower advantage on selected difficult, highly imbalanced settings.

Artifacts
Paper · Code

ENTRY 002 — CCR

When Labels Lie and Classes Skew
Neural Networks · manuscript under review

Failure mode
Class imbalance and asymmetric label noise occur at the same time.

Mechanism

confidence-aware reweighting
+ detached sample weights
+ per-batch normalization
= robustness without hidden gradient-scale distortion

Evaluation

14 datasets
9 loss baselines
tree-ensemble comparisons
gradient attribution
ablation studies
architecture transfer

Artifact
Code

ENTRY 003 — FSVA

When More Features Hurt
Knowledge-Based Systems · manuscript under review

Question
Can automated feature synthesis increase the train–test generalization gap by amplifying perturbations, redundancy, estimator variance, and search complexity?

Configured experiment

25 datasets
5 seeds × 5 folds
14 conditions
7 pipelines
10 classifiers

Confirmatory evidence

22 substantially completed datasets
538,972 evaluation records

Observation
Unrestricted synthesis did not improve generalization in the completed evidence scope; constrained addition/subtraction synthesis remained much closer to capped raw-feature baselines.

Artifacts
Code · Manuscript

ENTRY 004 — Calibration Collapse

Problem
A global calibration metric can hide minority-class miscalibration.

Focus

per-class ECE
minority recall
resampling × calibration
severity sweeps
leakage-aware evaluation

Repository

BUILD LOG

Project

What it proves

AutoPrepML

I can build reproducible ML data infrastructure

SentinelTrack

I can integrate CV models into a multi-camera system

ZombieGuard

I can scope a defensive ML system conservatively

Nexus AutoML

I can build full-stack experiment infrastructure

AutoPrepML ·
SentinelTrack ·
ZombieGuard ·
Nexus

TOOLBOX

<div align="center">

<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,opencv,sklearn,fastapi,postgres,redis,docker,linux,githubactions,git,latex" alt="Tech stack"/>

</div>

current:
  research:
    - robust_machine_learning
    - tabular_learning
    - distribution_shift
    - calibration
  engineering:
    - research_infrastructure
    - machine_learning_systems
    - computer_vision
  open_to:
    - masters_research
    - research_assistant_roles
    - reproducibility_collaborations
