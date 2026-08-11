<p align="center">
  <img src="./assets/header.svg" width="100%" alt="Ihsan — Computer Vision, NLP, Edge AI" />
</p>

<h4 align="center">
  Computer Science undergraduate · Indonesia · UTC+7<br />
  I engineer hardware-software systems at the intersection of Computer Vision, NLP, and Edge AI.
</h4>

<div align="center">
  <img src="https://img.shields.io/badge/Python-0A0E1F?style=for-the-badge&logo=python&logoColor=4ECDC4" alt="Python" />
  <img src="https://img.shields.io/badge/PyTorch-0A0E1F?style=for-the-badge&logo=pytorch&logoColor=A78BFA" alt="PyTorch" />
  <img src="https://img.shields.io/badge/TensorFlow-0A0E1F?style=for-the-badge&logo=tensorflow&logoColor=38BDF8" alt="TensorFlow" />
  <img src="https://img.shields.io/badge/OpenCV-0A0E1F?style=for-the-badge&logo=opencv&logoColor=4ECDC4" alt="OpenCV" />
  <img src="https://img.shields.io/badge/ONNX-0A0E1F?style=for-the-badge&logo=onnx&logoColor=4ECDC4" alt="ONNX" />
</div>

<div align="center">
  <img src="https://img.shields.io/badge/Flutter-0A0E1F?style=for-the-badge&logo=flutter&logoColor=38BDF8" alt="Flutter" />
  <img src="https://img.shields.io/badge/Dart-0A0E1F?style=for-the-badge&logo=dart&logoColor=4ECDC4" alt="Dart" />
  <img src="https://img.shields.io/badge/TypeScript-0A0E1F?style=for-the-badge&logo=typescript&logoColor=4ECDC4" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-0A0E1F?style=for-the-badge&logo=javascript&logoColor=4ECDC4" alt="JavaScript" />
</div>

<div align="center">
  <img src="https://img.shields.io/badge/FastAPI-0A0E1F?style=for-the-badge&logo=fastapi&logoColor=4ECDC4" alt="FastAPI" />
  <img src="https://img.shields.io/badge/PostgreSQL-0A0E1F?style=for-the-badge&logo=postgresql&logoColor=38BDF8" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Ollama-0A0E1F?style=for-the-badge&logo=ollama&logoColor=E2E8F0" alt="Ollama" />
  <img src="https://img.shields.io/badge/Hugging%20Face-0A0E1F?style=for-the-badge&logo=huggingface&logoColor=A78BFA" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/Raspberry%20Pi-0A0E1F?style=for-the-badge&logo=raspberrypi&logoColor=38BDF8" alt="Raspberry Pi" />
  <img src="https://img.shields.io/badge/Qt-0A0E1F?style=for-the-badge&logo=qt&logoColor=4ECDC4" alt="Qt" />
</div>

<br />

<div align="center">
  <img src="https://img.shields.io/badge/Open%20to-Internships-0A0E1F?style=flat-square&labelColor=0A0E1F&color=4ECDC4" alt="Open to internships" />
  <img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2FIhsan-p1&query=%24.public_repos&label=Public%20Repos&style=flat-square&labelColor=0A0E1F&color=4ECDC4" alt="Public Repos" />
  <img src="https://img.shields.io/github/followers/Ihsan-p1?style=flat-square&labelColor=0A0E1F&color=4ECDC4" alt="Followers" />
  <img src="https://komarev.com/ghpvc/?username=Ihsan-p1&label=Profile%20Views&color=4ECDC4&style=flat-square" alt="Profile Views" />
</div>

<br />

I build systems that run where the data is, not where the GPU is — hybrid edge-cloud assistants, local-first RAG, and on-device inference. Alongside that I bridge ML with creative tools through mobile development, computational photography, and audio engineering.

I also try hard not to fool myself. In **[MediSight-AI](https://github.com/Ihsan-p1/MediSight-AI)** I found that my own `random_split` had leaked near-duplicate video frames across train and test, so I withdrew the published numbers, rebuilt the pipeline, and re-measured. In **[Sentra](https://github.com/Ihsan-p1/Sentra)** every answer is scored twice — trained model against a rule-based baseline, side by side — so the cost of the simple heuristic stays visible instead of being assumed away.

- 🔭 Currently exploring on-device LLM efficiency and multimodal edge AI.
- 🤝 Open to internships and collaborations in Edge AI / MLOps.
- 📫 [huftrash@gmail.com](mailto:huftrash@gmail.com)

<!--
  Two details worth adding once you want them public — a recruiter filters on both:
    1. University: change the line at the top to
       "Computer Science undergraduate at <University>, Indonesia · UTC+7"
    2. Availability: extend the internships bullet with
       "— available <month year> to <month year>"
  Also adjust UTC+7 if you are in WITA (UTC+8) or WIT (UTC+9).
-->


<h2 align="center">Featured Projects</h2>

<table>
<tr>
<td width="50%" valign="top">

### [Echo](https://github.com/Ihsan-p1/Echo)

Context-aware interactive robot assistant on a hybrid laptop–RPi architecture — CUDA inference on the laptop, a Raspberry Pi 4 driving camera, audio I/O and hardware control. Fuses voice, vision, and gesture into one multimodal brain.

![Python](https://img.shields.io/badge/Python-0A0E1F?style=flat-square&logo=python&logoColor=4ECDC4)
![PyTorch](https://img.shields.io/badge/PyTorch-0A0E1F?style=flat-square&logo=pytorch&logoColor=A78BFA)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-0A0E1F?style=flat-square&logo=raspberrypi&logoColor=38BDF8)

</td>
<td width="50%" valign="top">

### [Sentra](https://github.com/Ihsan-p1/Sentra)

RAG chatbot for media-framing analysis of Indonesian English-language news. Runs fully local — a 3B LLM on Ollama, local embeddings, PostgreSQL, no external API at inference. Every answer is scored twice and compared against a rule-based baseline.

![Python](https://img.shields.io/badge/Python-0A0E1F?style=flat-square&logo=python&logoColor=4ECDC4)
![Ollama](https://img.shields.io/badge/Ollama-0A0E1F?style=flat-square&logo=ollama&logoColor=E2E8F0)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0A0E1F?style=flat-square&logo=postgresql&logoColor=38BDF8)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [InfraSight](https://github.com/Ihsan-p1/InfraSight)

Pothole volumetric analysis for road maintenance. Combines monocular depth estimation with instance segmentation to measure pothole volume from a single camera.

![Python](https://img.shields.io/badge/Python-0A0E1F?style=flat-square&logo=python&logoColor=4ECDC4)
![OpenCV](https://img.shields.io/badge/OpenCV-0A0E1F?style=flat-square&logo=opencv&logoColor=4ECDC4)
![PyTorch](https://img.shields.io/badge/PyTorch-0A0E1F?style=flat-square&logo=pytorch&logoColor=A78BFA)

</td>
<td width="50%" valign="top">

### [EchoKeeper](https://github.com/Ihsan-p1/Echokeeper)

High-performance local translation engine built on Meta's NLLB-200 — 200 languages, executed entirely on your own hardware. No data leaves the machine.

![Python](https://img.shields.io/badge/Python-0A0E1F?style=flat-square&logo=python&logoColor=4ECDC4)
![Transformers](https://img.shields.io/badge/Transformers-0A0E1F?style=flat-square&logo=huggingface&logoColor=A78BFA)
![ONNX](https://img.shields.io/badge/ONNX-0A0E1F?style=flat-square&logo=onnx&logoColor=4ECDC4)

</td>
</tr>
</table>

<h2 align="center">Profile Analysis</h2>

<!--
  Cards below are generated daily by .github/workflows/profile-cards.yml and
  committed to the `cards` branch, then served from raw.githubusercontent.com.
  Nothing here depends on a third-party host at page-load time, which is what
  used to break the old github-readme-stats cards.
-->

<!--
  Each cell is pinned to half the table and each image to the full cell, so the
  four cards form an even grid. Without this the cards fall back to their own
  natural widths, which differ per card and leave the columns ragged.
-->

<table align="center" width="100%">
<tr>
<td width="50%" valign="top"><img width="100%" src="https://raw.githubusercontent.com/Ihsan-p1/Ihsan-p1/cards/profile-summary-card-output/github_dark/3-stats.svg" alt="Stats" /></td>
<td width="50%" valign="top"><img width="100%" src="https://raw.githubusercontent.com/Ihsan-p1/Ihsan-p1/cards/profile-summary-card-output/github_dark/1-repos-per-language.svg" alt="Top languages by repo" /></td>
</tr>
<tr>
<td width="50%" valign="top"><img width="100%" src="https://raw.githubusercontent.com/Ihsan-p1/Ihsan-p1/cards/profile-summary-card-output/github_dark/2-most-commit-language.svg" alt="Top languages by commit" /></td>
<td width="50%" valign="top"><img width="100%" src="https://streak-stats.demolab.com?user=Ihsan-p1&hide_border=true&background=0A0E1F&currStreakNum=E2E8F0&sideNums=E2E8F0&sideLabels=4ECDC4&dates=94A3B8&ring=38BDF8&fire=A78BFA" alt="GitHub Streak" /></td>
</tr>
</table>

<h2 align="center">Contributions</h2>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Ihsan-p1/Ihsan-p1/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Ihsan-p1/Ihsan-p1/output/snake.svg" />
  <img src="https://raw.githubusercontent.com/Ihsan-p1/Ihsan-p1/output/snake.svg" alt="Contribution snake" />
</picture>
