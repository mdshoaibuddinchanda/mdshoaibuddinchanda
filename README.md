<!--
PROFILE DIRECTION: RESEARCH + SYSTEMS SIGNATURE
No local/custom image files required.
External banners/badges can be removed independently if a service is unavailable.
-->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=180&color=0:0B1220,45:102A43,72:0E7490,100:F59E0B&text=Md%20Shoaib%20Uddin%20Chanda&fontColor=F8FAFC&fontSize=38&fontAlignY=40&desc=Research%20that%20survives%20real-world%20conditions.%20Systems%20that%20survive%20real-world%20use.&descAlignY=67&descSize=15"/>

<br/>

<a href="https://doi.org/10.1016/j.array.2026.101049">
<img src="https://img.shields.io/badge/PUBLISHED-ARRAY%202026-F59E0B?style=for-the-badge&logo=elsevier&logoColor=white" alt="Published in Array 2026"/>
</a>
<a href="https://github.com/mdshoaibuddinchanda/sentineltrack">
<img src="https://img.shields.io/badge/GUJARAT%20CCTV-SENTINELTRACK-0E7490?style=for-the-badge&logo=opencv&logoColor=white" alt="SentinelTrack Gujarat CCTV"/>
</a>
<a href="https://github.com/mdshoaibuddinchanda/Nexus-AutoML-Platform">
<img src="https://img.shields.io/badge/AUTOML-NEXUS-4338CA?style=for-the-badge&logo=fastapi&logoColor=white" alt="Nexus AutoML"/>
</a>

<br/><br/>

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=17&duration=2800&pause=900&color=22D3EE&center=true&vCenter=true&width=940&lines=Robust+Machine+Learning+%C2%B7+Tabular+AI+%C2%B7+Computer+Vision;Published+Research+%C2%B7+Government-scale+Vision+Systems+%C2%B7+AutoML;Evidence+%E2%86%92+Reproducibility+%E2%86%92+Engineering" alt="Research and engineering focus"/>

</div>

What I build

I work across robust machine learning, tabular AI, computer vision, and research engineering.

My work is easiest to understand through three pieces of evidence:

<table>
<tr>
<td align="center" width="33%">
<h3>Research</h3>
<strong>1 published journal paper</strong><br/>
<sub>robustness + efficiency of tabular ML</sub>
</td>
<td align="center" width="33%">
<h3>Vision Systems</h3>
<strong>SentinelTrack</strong><br/>
<sub>Gujarat multi-camera CCTV intelligence</sub>
</td>
<td align="center" width="33%">
<h3>ML Platforms</h3>
<strong>Nexus AutoML</strong><br/>
<sub>secure reproducible experimentation</sub>
</td>
</tr>
</table>

01 — Published Research

Revisiting training-free tabular models: A robustness and efficiency study

Array · Volume 31 · September 2026 · Article 101049

Training-free models look attractive when benchmark conditions are clean.
I tested what happens when those conditions stop being clean.

<table>
<tr>
<td align="center" width="25%"><h3>17</h3><strong>Datasets</strong></td>
<td align="center" width="25%"><h3>6</h3><strong>Model configurations</strong></td>
<td align="center" width="25%"><h3>15</h3><strong>Random seeds</strong></td>
<td align="center" width="25%"><h3>19,890</h3><strong>Evaluations</strong></td>
</tr>
</table>

The study evaluates HyperFast against Logistic Regression, LightGBM, XGBoost, and Random Forest under Gaussian feature noise, MCAR missingness, limited labelled data, and computational constraints.

The main result is deliberately practical: across the evaluated conditions, classical and gradient-boosted methods generally provide stronger accuracy–runtime trade-offs. Tuned HyperFast offers benefits only in a more limited set of difficult scenarios.

<div align="center">

<a href="https://doi.org/10.1016/j.array.2026.101049">
<img src="https://img.shields.io/badge/READ-PAPER-F59E0B?style=for-the-badge&logo=elsevier&logoColor=white" alt="Read published paper"/>
</a>
<a href="https://github.com/mdshoaibuddinchanda/hyperfast-robustness-evaluation">
<img src="https://img.shields.io/badge/VIEW-CODE-181717?style=for-the-badge&logo=github&logoColor=white" alt="View reproducibility code"/>
</a>

</div>

02 — SentinelTrack

Multi-camera vehicle intelligence for the Sentinel Gujarat CCTV integration challenge

SentinelTrack is not just an object-detection demo. It is a camera-to-route intelligence pipeline designed around municipal CCTV streams.

RTSP / HLS
    ↓
YOLO11 vehicle detection
    ↓
ByteTrack per-camera tracking
    ↓
license-plate detection
    ↓
PP-OCRv5 recognition
    ↓
watchlist / target matching
    ↓
PostGIS sightings + route reconstruction

<table>
<tr>
<td width="50%" valign="top">

<h3>Computer Vision</h3>

YOLO11
ByteTrack
Plate Detection
PP-OCRv5
Multi-frame Consensus

</td>
<td width="50%" valign="top">

<h3>System Intelligence</h3>

RTSP / HLS Resolver
100k+ Watchlist Retrieval
PostGIS
GeoJSON
Spatio-temporal Route Engine

</td>
</tr>
</table>

The system includes stream-health handling, per-camera track isolation, Indian plate normalization, multi-frame OCR voting, target-registration matching, historical sightings, geospatial search, and physically constrained cross-camera route reconstruction.

<div align="center">

<a href="https://github.com/mdshoaibuddinchanda/sentineltrack">
<img src="https://img.shields.io/badge/OPEN-SENTINELTRACK-0E7490?style=for-the-badge&logo=github&logoColor=white" alt="Open SentinelTrack repository"/>
</a>

</div>

03 — Nexus AutoML

Secure, full-stack machine-learning experimentation workspace

Nexus turns a tabular CSV into a versioned, reproducible experiment workflow instead of a one-off notebook.

React / TypeScript
        ↓
      FastAPI
        ↓
Workspace → Project → Dataset → Immutable Version
        ↓
Celery / Redis Worker
        ↓
Model Training + Cross-Validation
        ↓
Metrics + Timelines + Model Artifacts

<table>
<tr>
<td align="center" width="25%"><h3>12</h3><strong>Classifiers</strong></td>
<td align="center" width="25%"><h3>SHA-256</h3><strong>Dataset storage</strong></td>
<td align="center" width="25%"><h3>Typed</h3><strong>React frontend</strong></td>
<td align="center" width="25%"><h3>Server-side</h3><strong>Ownership controls</strong></td>
</tr>
</table>

Implemented stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,fastapi,postgres,redis,docker,react,typescript,githubactions" alt="Nexus technology stack"/>

</div>

Nexus includes immutable dataset versions, schema/quality profiling, deterministic experiment seeds, numeric/categorical preprocessing, stratified cross-validation, optional MLflow mirroring, artifact downloads, session security, CI, and a shared API/UI model catalog.

<div align="center">

<a href="https://github.com/mdshoaibuddinchanda/Nexus-AutoML-Platform">
<img src="https://img.shields.io/badge/OPEN-NEXUS%20AUTOML-4338CA?style=for-the-badge&logo=github&logoColor=white" alt="Open Nexus AutoML repository"/>
</a>

</div>

Research in progress

<table>
<tr>
<td width="50%" valign="top">

<h3>Confidence-Calibrated Reweighting</h3>

Robust tabular deep learning under class imbalance + asymmetric label noise.

<strong>Status:</strong> manuscript under review at <strong>Neural Networks</strong>.

<p><a href="https://github.com/mdshoaibuddinchanda/CCR-Tabular"><strong>CCR-Tabular</strong></a></p>

</td>
<td width="50%" valign="top">

<h3>Feature-Synthesis Variance Amplification</h3>

When automated feature synthesis increases perturbation sensitivity, variance, redundancy, and computational cost.

<strong>Status:</strong> manuscript under review at <strong>Knowledge-Based Systems</strong>.

<p><a href="https://github.com/mdshoaibuddinchanda/AutoFE-ShiftBench"><strong>AutoFE-ShiftBench</strong></a></p>

</td>
</tr>
</table>

Core toolkit

<div align="center">

<img src="https://skillicons.dev/icons?i=python,cpp,java,pytorch,tensorflow,opencv,sklearn,fastapi,postgres,redis,docker,linux,githubactions,git,latex" alt="Core technical toolkit"/>

<br/><br/>

<img src="https://img.shields.io/badge/ROBUST%20ML-0E7490?style=flat-square"/>
<img src="https://img.shields.io/badge/TABULAR%20AI-4338CA?style=flat-square"/>
<img src="https://img.shields.io/badge/COMPUTER%20VISION-7C3AED?style=flat-square"/>
<img src="https://img.shields.io/badge/DISTRIBUTION%20SHIFT-0F766E?style=flat-square"/>
<img src="https://img.shields.io/badge/CALIBRATION-F59E0B?style=flat-square"/>
<img src="https://img.shields.io/badge/REPRODUCIBILITY-059669?style=flat-square"/>
<img src="https://img.shields.io/badge/RESEARCH%20ENGINEERING-334155?style=flat-square"/>

</div>

Current direction

<table>
<tr>
<td width="33%" align="center" valign="top">

Research

Robust ML
Tabular learning
Calibration
Distribution shift
Empirical evaluation

</td>
<td width="33%" align="center" valign="top">

Systems

Computer vision
ML infrastructure
Backend systems
MLOps
Reproducibility

</td>
<td width="33%" align="center" valign="top">

Open to

Master's research
Research assistant roles
Robust-ML collaborations
Research engineering

</td>
</tr>
</table>

<div align="center">

Connect

<a href="https://linkedin.com/in/mdshoaibuddinchanda">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:mdshoaibuddinchanda@gmail.com">
<img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://github.com/mdshoaibuddinchanda">
<img src="https://img.shields.io/badge/GitHub-mdshoaibuddinchanda-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br/><br/>

Research that survives real-world conditions. Systems that survive real-world use.

</div>
