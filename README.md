<p align="center">
  <img src="./assets/header.svg" width="100%" alt="Ihsan — Computer Vision, NLP, Edge AI" />
</p>

<h4 align="center">Building AI that runs on the device, not in the cloud.</h4>

<!--
  Every badge below is used by a project pinned on this page. TensorFlow,
  Flutter, Dart, TypeScript, JavaScript and FastAPI were dropped for that
  reason — add one back when a repo here uses it.
-->

<div align="center">
  <img src="https://img.shields.io/badge/Python-0A0E1F?style=for-the-badge&logo=python&logoColor=4ECDC4" alt="Python" />
  <img src="https://img.shields.io/badge/PyTorch-0A0E1F?style=for-the-badge&logo=pytorch&logoColor=A78BFA" alt="PyTorch" />
  <img src="https://img.shields.io/badge/OpenCV-0A0E1F?style=for-the-badge&logo=opencv&logoColor=4ECDC4" alt="OpenCV" />
  <img src="https://img.shields.io/badge/Hugging%20Face-0A0E1F?style=for-the-badge&logo=huggingface&logoColor=A78BFA" alt="Hugging Face" />
</div>

<div align="center">
  <img src="https://img.shields.io/badge/ONNX%20Runtime-0A0E1F?style=for-the-badge&logo=onnx&logoColor=4ECDC4" alt="ONNX Runtime" />
  <img src="https://img.shields.io/badge/Ollama-0A0E1F?style=for-the-badge&logo=ollama&logoColor=E2E8F0" alt="Ollama" />
  <img src="https://img.shields.io/badge/Raspberry%20Pi-0A0E1F?style=for-the-badge&logo=raspberrypi&logoColor=38BDF8" alt="Raspberry Pi" />
  <img src="https://img.shields.io/badge/CUDA-0A0E1F?style=for-the-badge&logo=nvidia&logoColor=4ECDC4" alt="CUDA" />
  <img src="https://img.shields.io/badge/PostgreSQL-0A0E1F?style=for-the-badge&logo=postgresql&logoColor=38BDF8" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Qt-0A0E1F?style=for-the-badge&logo=qt&logoColor=4ECDC4" alt="Qt" />
</div>

<br />

### Hi, I'm Ihsan

Computer Science undergraduate from Indonesia. I work on computer vision, NLP, and edge AI — mostly getting models to run on small hardware, so they keep working without a network.

I also shoot photos, work on audio, and build mobile apps, and a lot of my projects sit between those and ML.

Currently exploring on-device LLM efficiency and multimodal edge AI. Open to internships and collaborations in Edge AI / MLOps — [huftrash@gmail.com](mailto:huftrash@gmail.com).

<!--
  Two details worth adding once you want them public — a recruiter filters on both:
    1. University: "Computer Science undergraduate at <University>, Indonesia"
    2. Availability: "Open to internships ... available <month year> to <month year>"
-->

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### [Echo](https://github.com/Ihsan-p1/Echo)

Context-aware interactive robot assistant on a hybrid laptop–RPi architecture — CUDA inference on the laptop, a Raspberry Pi 4 driving camera, audio I/O and hardware control. Voice, vision, and gesture are fused into one state, so it responds to what it sees and hears together rather than to whichever sensor fires first.

![Python](https://img.shields.io/badge/Python-0A0E1F?style=flat-square&logo=python&logoColor=4ECDC4)
![PyTorch](https://img.shields.io/badge/PyTorch-0A0E1F?style=flat-square&logo=pytorch&logoColor=A78BFA)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi%204-0A0E1F?style=flat-square&logo=raspberrypi&logoColor=38BDF8)
![CUDA](https://img.shields.io/badge/CUDA-0A0E1F?style=flat-square&logo=nvidia&logoColor=4ECDC4)

</td>
<td width="50%" valign="top">

### [Sentra](https://github.com/Ihsan-p1/Sentra)

RAG chatbot for media-framing analysis of Indonesian English-language news. Runs fully local — a 3B LLM on Ollama, local embeddings in PostgreSQL with pgvector, no external API at inference.

Every answer is scored twice, trained model against a rule-based baseline, side by side. That comparison is the point: it keeps the cost of the simple heuristic visible instead of assuming the trained model wins.

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

Local translation engine built on Meta's NLLB-200 — 200 languages, executed entirely on your own hardware. No data leaves the machine.

![Python](https://img.shields.io/badge/Python-0A0E1F?style=flat-square&logo=python&logoColor=4ECDC4)
![Transformers](https://img.shields.io/badge/Transformers-0A0E1F?style=flat-square&logo=huggingface&logoColor=A78BFA)
![ONNX Runtime](https://img.shields.io/badge/ONNX%20Runtime-0A0E1F?style=flat-square&logo=onnx&logoColor=4ECDC4)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [MediSight-AI](https://github.com/Ihsan-p1/MediSight-AI)

Real-time multi-modal facial analysis from a webcam — emotion, drowsiness, and a pain proxy.

The first published numbers were wrong and I said so: `random_split` had put near-duplicate frames of the same person in both train and test, inflating everything. Withdrawn, rebuilt, and re-measured on a subject-disjoint split.

![Python](https://img.shields.io/badge/Python-0A0E1F?style=flat-square&logo=python&logoColor=4ECDC4)
![PyTorch](https://img.shields.io/badge/PyTorch-0A0E1F?style=flat-square&logo=pytorch&logoColor=A78BFA)
![OpenCV](https://img.shields.io/badge/OpenCV-0A0E1F?style=flat-square&logo=opencv&logoColor=4ECDC4)

</td>
<td width="50%" valign="top">

### [ShoreLine](https://github.com/Ihsan-p1/ShoreLine)

Keyboard-first desktop app for culling large photo shoots fast. Built for my own photography workflow, where the bottleneck is the first pass, not the editing.

![Python](https://img.shields.io/badge/Python-0A0E1F?style=flat-square&logo=python&logoColor=4ECDC4)
![Qt](https://img.shields.io/badge/PySide6-0A0E1F?style=flat-square&logo=qt&logoColor=4ECDC4)

</td>
</tr>
</table>
