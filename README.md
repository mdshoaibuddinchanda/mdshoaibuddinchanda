<!-- =========================================================
DESIGN 1 — NEON RESEARCH LAB
Visual: rich, colorful, dense, high-energy
Rule: HTML links inside HTML tables; no Markdown links in table cells
========================================================= -->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:020617,25:0E7490,52:4338CA,78:7C3AED,100:F59E0B&text=Md%20Shoaib%20Uddin%20Chanda&fontColor=F8FAFC&fontSize=38&fontAlignY=34&desc=Robust%20ML%20%E2%80%A2%20Tabular%20Learning%20%E2%80%A2%20Research%20Engineering&descAlignY=53&descSize=16&animation=fadeIn" alt="Profile banner"/>

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=18&duration=2800&pause=900&color=22D3EE&center=true&vCenter=true&width=920&lines=Published+research+%E2%86%92+reproducible+code;Robustness+%E2%80%A2+Calibration+%E2%80%A2+Distribution+Shift;Testing+the+assumptions+benchmarks+leave+untouched" alt="Research focus"/>

<br/>

<a href="https://doi.org/10.1016/j.array.2026.101049"><img src="https://img.shields.io/badge/Array%202026-Published-F59E0B?style=for-the-badge&logo=elsevier&logoColor=white" alt="Published in Array"/></a>
<a href="https://github.com/mdshoaibuddinchanda"><img src="https://img.shields.io/badge/GitHub-Research-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
<a href="https://linkedin.com/in/mdshoaibuddinchanda"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:mdshoaibuddinchanda@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

</div>

Research signal

<table>
<tr>
<td align="center" width="20%"><h3>01</h3><strong>Published paper</strong><br/><sub>Array · 2026</sub></td>
<td align="center" width="20%"><h3>19,890</h3><strong>Evaluations</strong><br/><sub>HyperFast study</sub></td>
<td align="center" width="20%"><h3>17</h3><strong>Datasets</strong><br/><sub>published study</sub></td>
<td align="center" width="20%"><h3>538,972</h3><strong>Records</strong><br/><sub>AutoFE scope</sub></td>
<td align="center" width="20%"><h3>14</h3><strong>Datasets</strong><br/><sub>CCR benchmark</sub></td>
</tr>
</table>

I study how machine-learning systems behave when clean benchmark assumptions fail.
My work connects robust ML, tabular learning, calibration, distribution shift, empirical evaluation, and reproducible research engineering.

Papers

<table>
<tr>
<td width="33%" valign="top">

<h3>01 · Published</h3>
<p><strong>Revisiting training-free tabular models: A robustness and efficiency study</strong></p>
<p><strong>Array · 31 (2026) · 101049</strong></p>

<p>Stress-tests training-free tabular classification against classical and gradient-boosted baselines under noisy, incomplete, scarce, and computationally constrained conditions.</p>

<p><strong>Scale</strong><br/>
17 datasets · 15 seeds · 13 conditions · 19,890 evaluations</p>

<p><strong>Finding</strong><br/>
Classical and gradient-boosted baselines generally offer stronger accuracy–runtime trade-offs, while tuned HyperFast shows narrower advantages on some difficult, highly imbalanced settings.</p>

<p>
<a href="https://doi.org/10.1016/j.array.2026.101049"><strong>Paper</strong></a>
&nbsp;·&nbsp;
<a href="https://github.com/mdshoaibuddinchanda/hyperfast-robustness-evaluation"><strong>Code</strong></a>
</p>

</td>
<td width="33%" valign="top">

<h3>02 · Under review</h3>
<p><strong>When Labels Lie and Classes Skew: Robust Tabular Deep Learning via Confidence-Calibrated Reweighting</strong></p>
<p><strong>Neural Networks · manuscript under review</strong></p>

<p>CCR studies the compound failure mode of class imbalance and asymmetric label noise using detached confidence-aware sample reweighting and per-batch weight normalization.</p>

<p><strong>Scope</strong><br/>
14 datasets · 9 loss baselines · tree ensembles · gradient attribution · ablations · architecture transfer</p>

<p><strong>Evidence</strong><br/>
Repository results report stronger minority-recall retention under severe asymmetric corruption with reduced corrupted-sample gradient mass and gradient-norm volatility.</p>

<p>
<a href="https://github.com/mdshoaibuddinchanda/CCR-Tabular"><strong>Code</strong></a>
</p>

</td>
<td width="33%" valign="top">

<h3>03 · Under review</h3>
<p><strong>When More Features Hurt: Feature-Synthesis Variance Amplification in Automated Feature Engineering</strong></p>
<p><strong>Knowledge-Based Systems · manuscript under review</strong></p>

<p>Introduces Feature-Synthesis Variance Amplification (FSVA) to study when automated arithmetic feature synthesis amplifies perturbations, redundancy, estimator variance, and cost.</p>

<p><strong>Configured design</strong><br/>
25 datasets · 5 seeds × 5 folds · 14 conditions · 7 pipelines · 10 classifiers</p>

<p><strong>Confirmatory scope</strong><br/>
22 substantially completed datasets · 538,972 evaluation records</p>

<p>
<a href="https://github.com/mdshoaibuddinchanda/AutoFE-ShiftBench"><strong>Code</strong></a>
&nbsp;·&nbsp;
<a href="https://github.com/mdshoaibuddinchanda/AutoFE-ShiftBench/blob/main/paper/manuscript.tex"><strong>Manuscript</strong></a>
</p>

</td>
</tr>
</table>

Research map

flowchart LR
    A["Benchmark assumption"] --> B["Controlled stress test"]
    B --> C["Robustness / calibration / shift"]
    C --> D["Statistical + mechanistic evidence"]
    D --> E["Reproducible artifact"]
    E --> F["Reliable ML system"]

    H["HyperFast"] --> D
    I["CCR"] --> C
    J["FSVA"] --> C
    K["Calibration Collapse"] --> C

Selected research & engineering

<table>
<tr>
<td width="50%" valign="top">
<h3>🎯 Calibration Collapse</h3>
<p>Studies how imbalance, resampling, and post-hoc calibration affect minority-class probability reliability, with emphasis on per-class ECE and calibration–recall trade-offs.</p>
<p><a href="https://github.com/mdshoaibuddinchanda/calibration-collapse"><strong>Repository</strong></a></p>
</td>
<td width="50%" valign="top">
<h3>🧬 AutoPrepML</h3>
<p>ML data-readiness framework for leakage-safe fitted preprocessing, contracts, validation, fingerprints, lineage, serializable artifacts, storage, and experiment integrations.</p>
<p><a href="https://github.com/mdshoaibuddinchanda/autoprepml"><strong>Repository</strong></a></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>🚘 SentinelTrack</h3>
<p>Multi-camera vehicle-intelligence pipeline spanning RTSP/HLS ingest, YOLO detection, ByteTrack, plate localization, OCR, target matching, and GIS route reconstruction.</p>
<p><a href="https://github.com/mdshoaibuddinchanda/sentineltrack"><strong>Repository</strong></a></p>
</td>
<td width="50%" valign="top">
<h3>🛡️ ZombieGuard</h3>
<p>Defensive ZIP structural-evasion scanner combining a bounded parser with LightGBM, reproducible evaluation, explicit limitations, data/model cards, and CI.</p>
<p><a href="https://github.com/mdshoaibuddinchanda/zombieguard"><strong>Repository</strong></a></p>
</td>
</tr>
</table>

Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,cpp,java,pytorch,tensorflow,opencv,sklearn,fastapi,postgres,redis,docker,linux,githubactions,git,latex" alt="Technical stack"/>

<br/><br/>

<img src="https://img.shields.io/badge/Robust%20ML-0E7490?style=flat-square"/>
<img src="https://img.shields.io/badge/Tabular%20Learning-4338CA?style=flat-square"/>
<img src="https://img.shields.io/badge/Distribution%20Shift-0F766E?style=flat-square"/>
<img src="https://img.shields.io/badge/Calibration-F59E0B?style=flat-square"/>
<img src="https://img.shields.io/badge/Reproducibility-059669?style=flat-square"/>
<img src="https://img.shields.io/badge/MLOps-7C3AED?style=flat-square"/>

</div>

GitHub activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=mdshoaibuddinchanda&show_icons=true&hide_border=true&theme=tokyonight&include_all_commits=true&count_private=true" alt="GitHub stats"/>

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mdshoaibuddinchanda&layout=compact&hide_border=true&theme=tokyonight" alt="Top languages"/>

</div>

<div align="center">

Connect

<a href="https://linkedin.com/in/mdshoaibuddinchanda"><img src="https://img.shields.io/badge/LinkedIn-Md%20Shoaib%20Uddin%20Chanda-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:mdshoaibuddinchanda@gmail.com"><img src="https://img.shields.io/badge/Email-mdshoaibuddinchanda%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>

Building reliable ML systems. Testing the assumptions benchmarks usually leave untouched.

</div>
