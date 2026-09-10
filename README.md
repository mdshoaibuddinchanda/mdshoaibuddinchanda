<!--
  Md Shoaib Uddin Chanda — GitHub Profile
  Theme: Research Aurora
  Goal: research-first, visually distinctive, professor/recruiter friendly
-->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:0F172A,28:312E81,55:0E7490,78:059669,100:F59E0B&text=Md%20Shoaib%20Uddin%20Chanda&fontColor=F8FAFC&fontSize=38&fontAlignY=34&desc=Robust%20Machine%20Learning%20%E2%80%A2%20Research%20Engineering%20%E2%80%A2%20Reliable%20AI%20Systems&descAlignY=53&descSize=16&animation=fadeIn"/>

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=19&duration=3000&pause=900&color=22D3EE&center=true&vCenter=true&width=900&lines=Published+ML+Research+%E2%86%92+Reproducible+Code;Robustness+%E2%80%A2+Distribution+Shift+%E2%80%A2+Calibration;Research+Ideas+%E2%86%92+Auditable+Experiments+%E2%86%92+Systems" alt="Research focus animation"/>

<br/>

<a href="https://doi.org/10.1016/j.array.2026.101049">
  <img src="https://img.shields.io/badge/Array%202026-Published%20Research-F59E0B?style=for-the-badge&logo=elsevier&logoColor=white"/>
</a>
<a href="https://orcid.org/0009-0003-0066-1423">
  <img src="https://img.shields.io/badge/ORCID-0009--0003--0066--1423-A6CE39?style=for-the-badge&logo=orcid&logoColor=white"/>
</a>
<a href="https://linkedin.com/in/mdshoaibuddinchanda">
  <img src="https://img.shields.io/badge/LinkedIn-Research%20Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:mdshoaibuddinchanda@gmail.com">
  <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</div>

01 / Research identity

I study how machine-learning systems behave when clean benchmark assumptions fail.

My work focuses on robust machine learning, tabular learning, distribution shift, calibration, reproducibility, and research engineering. I build empirical studies and the software infrastructure needed to make their results auditable and reproducible.

<table>
<tr>
<td width="50%" valign="top">

🔬 Research

Robust & trustworthy ML

Tabular learning

Distribution shift

Calibration & imbalance

Evaluation methodology

Reproducible experimentation

</td>
<td width="50%" valign="top">

📄 Published work

Array (Elsevier), 2026

Revisiting training-free tabular models: A robustness and efficiency study

17 datasets · 15 seeds · 13 conditions
19,890 model evaluations

Paper · Reproducibility code

</td>
</tr>
<tr>
<td width="50%" valign="top">

⚙️ Research engineering

I build the infrastructure behind experiments:

leakage-safe pipelines

experiment tracking

dataset/version provenance

automated validation

CI and reproducible releases

benchmark tooling

</td>
<td width="50%" valign="top">

🌍 Applied systems

Research is strongest when it survives contact with real systems.

My engineering work spans:

computer vision / ANPR

ML infrastructure

cybersecurity ML

backend & MLOps systems

</td>
</tr>
</table>

02 / Publications & research

Work

Status

Theme

Evidence

Revisiting training-free tabular models: A robustness and efficiency study

Published — Array, 2026

Robustness · Tabular ML · Meta-learning

Paper · Code

Confidence-Calibrated Reweighting with Invariant Batch Normalization

Manuscript under review

Label noise · Imbalance · Robust DL

Research code

Calibration Collapse Under Class Imbalance

Research project

Calibration · Minority reliability

Repository

AutoFE-ShiftBench

Research benchmark

Distribution shift · AutoFE robustness

Repository

<details>
<summary><b>📚 Published paper — experiment snapshot</b></summary>
<br/>

The Array study stress-tests training-free tabular classification beyond clean benchmarks.

17 public tabular datasets

6 model configurations

15 random seeds

13 robustness conditions per dataset

19,890 total model evaluations

Gaussian feature noise, MCAR missingness, and reduced-data conditions

runtime and statistical comparisons against classical and gradient-boosted baselines

The complete experimental code, configuration, result pipeline, and analysis scripts are public in the associated repository.

</details>

03 / Selected research

<table>
<tr>
<td width="50%" valign="top">

🧠 CCR-Tabular

Confidence-Calibrated Reweighting

A robust-learning framework studying dynamic sample reweighting under concurrent class imbalance and asymmetric label noise.

Research: gradient behavior, minority recall, label-noise robustness, architecture transfer

Stack: PyTorch · OpenML · statistical testing

Explore CCR →

</td>
<td width="50%" valign="top">

📈 AutoFE-ShiftBench

Feature engineering under distribution shift

A large-scale benchmark asking whether automated feature engineering remains useful when deployment data is corrupted or shifted.

Protocol: 25 datasets · 10 models · fold-local AutoFE · multiple shift families

Focus: robustness, leakage-safe evaluation, statistical comparison

Explore ShiftBench →

</td>
</tr>

<tr>
<td width="50%" valign="top">

🎯 Calibration Collapse

When global calibration metrics hide minority failure

Research framework studying per-class calibration under imbalance, resampling, and post-hoc calibration.

Focus: ECE, minority calibration, confidence drift, synthetic stress testing

Explore Calibration Collapse →

</td>
<td width="50%" valign="top">

⚡ HyperFast Robustness

Code for my published Array study

A reproducible stress-test of training-free tabular classification against classical and gradient-boosted baselines.

Scale: 19,890 evaluations across 17 datasets

Evidence: paper ↔ code ↔ configs ↔ results

Explore reproducibility code →

</td>
</tr>
</table>

04 / Research engineering

<table>
<tr>
<td width="33%" valign="top">

🧬 AutoPrepML

ML data-readiness framework

Leakage-safe fitted preprocessing, contracts, validation, fingerprints, lineage, reproducible artifacts, storage and experiment integrations.

Released: v1.5 on PyPI
Quality: cross-platform CI · branch-aware coverage · typed core

Repository →

</td>
<td width="33%" valign="top">

🚘 SentinelTrack

Multi-camera vehicle intelligence

CCTV ingest → detection → tracking → plate localization → OCR → target matching → cross-camera route reconstruction.

Stack: YOLO · ByteTrack · OCR · PostGIS · FastAPI

Repository →

</td>
<td width="33%" valign="top">

🛡️ ZombieGuard

Defensive ZIP evasion scanner

A bounded structural parser plus LightGBM model for detecting contradictions in ZIP metadata and payload structure.

Includes: reproducible evaluation · model card · data card · CI

Repository →

</td>
</tr>
</table>

05 / Experience

Period

Role

Organisation / context

Focus

Sep 2025 – Mar 2026

AI & Software Engineering Intern

Delloyd R&D, Malaysia

Computer vision · ANPR · OCR · GPU workflows

Apr 2026 – May 2026

Research & Data Analysis Intern

Hyderabad City Security Council / Hyderabad City Police project

Operational analytics · reporting · process evaluation

2024 – 2026

Technical Head

ACM Student Chapter

Technical leadership · workshops · mentoring

2023

AI / ML Intern

RAM INFOTECH

Computer vision · XGBoost · feature engineering

06 / Stack

<div align="center">

Research & ML

<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
<img src="https://img.shields.io/badge/XGBoost-006600?style=flat-square"/>
<img src="https://img.shields.io/badge/LightGBM-02569B?style=flat-square"/>
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>
<img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white"/>

Systems

<img src="https://skillicons.dev/icons?i=python,cpp,java,fastapi,postgres,redis,docker,linux,githubactions,git,latex"/>

</div>

07 / Research console

research:
  core:
    - robust_machine_learning
    - tabular_learning
    - distribution_shift
    - calibration
  principles:
    - reproducibility_first
    - evidence_over_claims
    - leakage_safe_evaluation
    - explicit_limitations

engineering:
  - research_infrastructure
  - machine_learning_systems
  - computer_vision
  - mlops

currently_open_to:
  - masters_research
  - research_assistant_roles
  - reproducibility_collaborations
  - robust_ml_projects

08 / GitHub activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=mdshoaibuddinchanda&show_icons=true&hide_border=true&bg_color=0D1117&title_color=22D3EE&text_color=CBD5E1&icon_color=F59E0B&ring_color=8B5CF6&include_all_commits=true&count_private=true"/>

<img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=mdshoaibuddinchanda&hide_border=true&background=0D1117&stroke=334155&ring=8B5CF6&fire=F59E0B&currStreakNum=F8FAFC&sideNums=F8FAFC&currStreakLabel=22D3EE&sideLabels=94A3B8&dates=64748B"/>

</div>

<details>
<summary><b>📊 Contribution activity</b></summary>
<br/>

<div align="center">
<img width="96%" src="https://github-readme-activity-graph.vercel.app/graph?username=mdshoaibuddinchanda&bg_color=0D1117&color=CBD5E1&line=22D3EE&point=F59E0B&area=true&hide_border=true"/>
</div>

</details>

09 / Connect

<div align="center">

Research collaboration · graduate research · ML engineering

<a href="https://linkedin.com/in/mdshoaibuddinchanda">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:mdshoaibuddinchanda@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://orcid.org/0009-0003-0066-1423">
  <img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white"/>
</a>

<br/><br/>

Building reliable ML systems. Testing the assumptions that benchmarks usually leave untouched.

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=130&color=0:0F172A,28:312E81,55:0E7490,78:059669,100:F59E0B"/>

</div>
