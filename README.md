<!--
  Md Shoaib Uddin Chanda — GitHub Profile README
  Direction: Editorial Research Profile
  Visual system: Deep navy + cyan + amber + emerald accents
-->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=venom&height=210&color=0:020617,28:0F172A,58:0E7490,82:312E81,100:F59E0B&text=Md%20Shoaib%20Uddin%20Chanda&fontColor=F8FAFC&fontSize=38&fontAlignY=42&desc=Machine%20Learning%20Research%20%E2%80%A2%20Robustness%20%E2%80%A2%20Research%20Engineering&descAlignY=63&descSize=16&animation=fadeIn"/>

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=18&duration=2800&pause=900&color=22D3EE&center=true&vCenter=true&width=940&lines=I+study+what+happens+when+clean+ML+assumptions+break.;Robustness+%E2%80%A2+Distribution+Shift+%E2%80%A2+Calibration;Published+Research+%E2%86%92+Reproducible+Code+%E2%86%92+Reliable+Systems" alt="Research focus"/>

<br/>

<a href="https://doi.org/10.1016/j.array.2026.101049">
  <img src="https://img.shields.io/badge/Published%20in%20Array-2026-F59E0B?style=flat-square&logo=elsevier&logoColor=white"/>
</a>
<a href="https://linkedin.com/in/mdshoaibuddinchanda">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:mdshoaibuddinchanda@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white"/>
</a>
<a href="https://github.com/mdshoaibuddinchanda">
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>
</a>

</div>

<br/>

Research, not just projects

I work at the intersection of robust machine learning, tabular learning, distribution shift, calibration, and research engineering.

My central question is simple:

How reliable is a machine-learning system once the clean assumptions behind the benchmark stop being true?

I approach that question through large-scale empirical evaluation, reproducible experimentation, leakage-safe pipelines, statistical analysis, and software systems that make research easier to inspect and reproduce.

<br/>

<div align="center">

<table>
<tr>
<td align="center" width="25%">
<b>17</b><br/>
<sub>datasets in published study</sub>
</td>
<td align="center" width="25%">
<b>19,890</b><br/>
<sub>model evaluations</sub>
</td>
<td align="center" width="25%">
<b>15</b><br/>
<sub>random seeds</sub>
</td>
<td align="center" width="25%">
<b>13</b><br/>
<sub>robustness conditions</sub>
</td>
</tr>
</table>

</div>

Published research

Revisiting training-free tabular models: A robustness and efficiency study

Array, 2026

A large-scale empirical evaluation of training-free tabular classification under realistic degradation: feature noise, missingness, data scarcity, and computational constraints.

Core contribution: testing whether strong clean-benchmark performance remains reliable under non-ideal deployment conditions.

Read the paper
  •  
Reproduce the experiments

<details>
<summary><b>Study design</b></summary>

<br/>

17 public tabular datasets

6 model configurations

15 random seeds

13 robustness conditions per dataset

19,890 total evaluations

Gaussian feature noise

MCAR missingness

reduced-data conditions

runtime and statistical comparisons

</details>

Current research

<table>
<tr>
<td width="50%" valign="top">

Confidence-Calibrated Reweighting

Robust tabular learning under class imbalance and asymmetric label noise

A research framework studying confidence-aware sample reweighting, gradient-scale invariance, minority recall, and corruption robustness.

Focus

dynamic sample weighting

noisy-label robustness

class imbalance

gradient behavior

architecture transfer

View research code →

</td>
<td width="50%" valign="top">

AutoFE-ShiftBench

When feature engineering meets distribution shift

A benchmark studying whether automated feature engineering continues to help when test-time data is corrupted or shifted.

Protocol

25 datasets

10 models

fold-local AutoFE

multiple shift families

statistical comparisons

View benchmark →

</td>
</tr>
<tr>
<td width="50%" valign="top">

Calibration Collapse

When global calibration hides minority-class failure

A study of probability calibration under imbalance, resampling, and post-hoc calibration.

Focus

per-class ECE

minority reliability

confidence drift

calibration-recall trade-offs

synthetic stress testing

View project →

</td>
<td width="50%" valign="top">

HyperFast Robustness

Reproducibility repository for my published Array paper

The full experimental pipeline, dataset logic, benchmark conditions, model wrappers, validation checks, and paper-figure generation.

Scale

17 datasets

15 seeds

19,890 evaluations

end-to-end reproducibility

View reproducibility code →

</td>
</tr>
</table>

Research engineering

Research is stronger when the software around it is inspectable, testable, and reproducible.

<table>
<tr>
<td width="33%" valign="top">

AutoPrepML

ML data-readiness framework

Leakage-safe preprocessing, contracts, validation, fingerprints, lineage, serializable artifacts, storage integrations, and experiment tracking.

Engineering signal

PyPI release

cross-platform CI

typed core

property testing

branch-aware coverage

Repository →

</td>
<td width="33%" valign="top">

SentinelTrack

Multi-camera vehicle intelligence

A production-oriented computer-vision system spanning stream ingestion, detection, tracking, plate localization, OCR, matching, and route reconstruction.

Stack

YOLO

ByteTrack

OCR

PostGIS

FastAPI

Repository →

</td>
<td width="33%" valign="top">

ZombieGuard

Defensive ZIP evasion scanner

A bounded structural parser plus ML model for detecting contradictions between ZIP metadata and payload behavior.

Includes

reproducible evaluation

data card

model card

CI

explicit limitations

Repository →

</td>
</tr>
</table>

Research interests

<div align="center">

<img src="https://img.shields.io/badge/Robust%20Machine%20Learning-0E7490?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Tabular%20AI-312E81?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Distribution%20Shift-0F766E?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Calibration-F59E0B?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Reproducibility-059669?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Research%20Engineering-7C3AED?style=for-the-badge"/>

</div>

Experience

<table>
<tr>
<td width="22%"><b>Sep 2025 – Mar 2026</b></td>
<td width="28%"><b>AI & Software Engineering Intern</b></td>
<td width="25%">Delloyd R&D, Malaysia</td>
<td>Computer vision · ANPR · OCR · GPU workflows</td>
</tr>
<tr>
<td><b>Apr 2026 – May 2026</b></td>
<td><b>Research & Data Analysis Intern</b></td>
<td>Hyderabad City Police project</td>
<td>Operational analytics · reporting · process evaluation</td>
</tr>
<tr>
<td><b>2024 – 2026</b></td>
<td><b>Technical Head</b></td>
<td>ACM Student Chapter</td>
<td>Technical leadership · workshops · mentoring</td>
</tr>
<tr>
<td><b>2023</b></td>
<td><b>AI / ML Intern</b></td>
<td>RAM INFOTECH</td>
<td>Computer vision · XGBoost · feature engineering</td>
</tr>
</table>

Technical stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,cpp,java,pytorch,tensorflow,opencv,sklearn,fastapi,postgres,redis,docker,linux,githubactions,git,latex"/>

<br/><br/>

<img src="https://img.shields.io/badge/XGBoost-006600?style=flat-square"/>
<img src="https://img.shields.io/badge/LightGBM-02569B?style=flat-square"/>
<img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square"/>
<img src="https://img.shields.io/badge/OpenML-222222?style=flat-square"/>
<img src="https://img.shields.io/badge/Experimental%20Design-334155?style=flat-square"/>
<img src="https://img.shields.io/badge/Statistical%20Testing-334155?style=flat-square"/>

</div>

Current direction

RESEARCH
├── robust machine learning
├── tabular learning
├── distribution shift
├── calibration
└── reproducible evaluation

ENGINEERING
├── research infrastructure
├── ML systems
├── computer vision
└── MLOps

OPEN TO
├── Master's research
├── research assistant roles
├── reproducibility collaborations
└── robust-ML projects

GitHub activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=mdshoaibuddinchanda&show_icons=true&hide_border=true&bg_color=0D1117&title_color=22D3EE&text_color=CBD5E1&icon_color=F59E0B&ring_color=8B5CF6&include_all_commits=true&count_private=true"/>

<img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=mdshoaibuddinchanda&hide_border=true&background=0D1117&stroke=334155&ring=8B5CF6&fire=F59E0B&currStreakNum=F8FAFC&sideNums=F8FAFC&currStreakLabel=22D3EE&sideLabels=94A3B8&dates=64748B"/>

</div>

<details>
<summary><b>Contribution graph</b></summary>

<br/>

<div align="center">
<img width="96%" src="https://github-readme-activity-graph.vercel.app/graph?username=mdshoaibuddinchanda&bg_color=0D1117&color=CBD5E1&line=22D3EE&point=F59E0B&area=true&hide_border=true"/>
</div>

</details>

<div align="center">

Connect

<a href="https://linkedin.com/in/mdshoaibuddinchanda">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:mdshoaibuddinchanda@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://github.com/mdshoaibuddinchanda">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br/><br/>

Building reliable ML systems. Testing the assumptions that benchmarks usually leave untouched.

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=115&color=0:020617,30:0F172A,55:0E7490,78:312E81,100:F59E0B"/>

</div>
