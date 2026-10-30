<p align="center">
  <img src="./assets/header.svg" width="100%" alt="Ihsan: computer vision, NLP, edge AI" />
</p>

<h4 align="center">Building AI that runs on the device, not in the cloud.</h4>

<!--
  Every badge below is used by a project pinned on this page. TensorFlow,
  Dart, TypeScript and JavaScript were dropped for that reason. Add one back
  when a repo here uses it. ONNX Runtime and FastAPI came back with neutral,
  whose serving image runs on both.
-->

<div align="center">
  <img src="https://img.shields.io/badge/Python-0A0E1F?style=for-the-badge&logo=python&logoColor=4ECDC4" alt="Python" />
  <img src="https://img.shields.io/badge/PyTorch-0A0E1F?style=for-the-badge&logo=pytorch&logoColor=A78BFA" alt="PyTorch" />
  <img src="https://img.shields.io/badge/ONNX%20Runtime-0A0E1F?style=for-the-badge&logo=onnx&logoColor=E2E8F0" alt="ONNX Runtime" />
  <img src="https://img.shields.io/badge/Hugging%20Face-0A0E1F?style=for-the-badge&logo=huggingface&logoColor=A78BFA" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/OpenCV-0A0E1F?style=for-the-badge&logo=opencv&logoColor=4ECDC4" alt="OpenCV" />
</div>

<div align="center">
  <img src="https://img.shields.io/badge/FastAPI-0A0E1F?style=for-the-badge&logo=fastapi&logoColor=4ECDC4" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Ollama-0A0E1F?style=for-the-badge&logo=ollama&logoColor=E2E8F0" alt="Ollama" />
  <img src="https://img.shields.io/badge/PostgreSQL-0A0E1F?style=for-the-badge&logo=postgresql&logoColor=38BDF8" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Flutter-0A0E1F?style=for-the-badge&logo=flutter&logoColor=38BDF8" alt="Flutter" />
  <img src="https://img.shields.io/badge/CUDA-0A0E1F?style=for-the-badge&logo=nvidia&logoColor=4ECDC4" alt="CUDA" />
</div>

<br />

### Hi, I'm Ihsan

Computer Science undergraduate from Indonesia. I work on computer vision, NLP, and edge AI, mostly getting models to run on small hardware, so they keep working without a network.

I also shoot photos, work on audio, and build mobile apps, and a lot of my projects sit between those and ML. Currently exploring on-device LLM efficiency and multimodal edge AI. 

Open to internships and collaborations in Edge AI / MLOps, [ 📫 ](mailto:huftrash@gmail.com).

<!--
  Two details worth adding once you want them public, since a recruiter filters on both:
    1. University: "Computer Science undergraduate at <University>, Indonesia"
    2. Availability: "Open to internships ... available <month year> to <month year>"
-->

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### [neutral](https://github.com/Ihsan-p1/neutral)

**Spots biased wording in news, one sentence at a time.**

DeBERTa-v3 scores 0.848 macro F1, up from 0.742 for a TF-IDF baseline. On a second dataset from other outlets it drops to 0.585, and the README puts that number right next to the good one. Serves through FastAPI on ONNX Runtime, with no PyTorch in the image.

![Python](https://img.shields.io/badge/Python-0A0E1F?style=flat-square&logo=python&logoColor=4ECDC4)
![PyTorch](https://img.shields.io/badge/PyTorch-0A0E1F?style=flat-square&logo=pytorch&logoColor=A78BFA)
![ONNX Runtime](https://img.shields.io/badge/ONNX%20Runtime-0A0E1F?style=flat-square&logo=onnx&logoColor=E2E8F0)
![FastAPI](https://img.shields.io/badge/FastAPI-0A0E1F?style=flat-square&logo=fastapi&logoColor=4ECDC4)

</td>
<td width="50%" valign="top">

### [Sentra](https://github.com/Ihsan-p1/Sentra)

**Ask how different outlets framed the same story.**

A RAG chatbot over Indonesian English-language news, running on a 3B model through Ollama with no external API. Every answer is scored twice, by trained models and by plain rules, side by side, so you can see whether the model earns its place. When retrieval finds nothing close enough, it refuses instead of guessing.

![Python](https://img.shields.io/badge/Python-0A0E1F?style=flat-square&logo=python&logoColor=4ECDC4)
![Ollama](https://img.shields.io/badge/Ollama-0A0E1F?style=flat-square&logo=ollama&logoColor=E2E8F0)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0A0E1F?style=flat-square&logo=postgresql&logoColor=38BDF8)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [InfraSight](https://github.com/Ihsan-p1/InfraSight)

**One photo of a pothole, one volume estimate.**

YOLOv8-Seg outlines the hole, Depth Anything V2 reads how deep it goes, and a card or coin in the frame gives the scale. A Streamlit dashboard turns that into severity, repair cost, a map pin and a PDF report.

![Python](https://img.shields.io/badge/Python-0A0E1F?style=flat-square&logo=python&logoColor=4ECDC4)
![OpenCV](https://img.shields.io/badge/OpenCV-0A0E1F?style=flat-square&logo=opencv&logoColor=4ECDC4)
![PyTorch](https://img.shields.io/badge/PyTorch-0A0E1F?style=flat-square&logo=pytorch&logoColor=A78BFA)

</td>
<td width="50%" valign="top">

### [TepiLog](https://github.com/Ihsan-p1/TepiLog)

**Photos organised by place, not by people.**

Every location keeps its own timeline, dated by when the photo was taken (EXIF) rather than when it was uploaded. Flutter app, Node and PostGIS backend, rotating refresh tokens with reuse detection, and CI on every push.

![Flutter](https://img.shields.io/badge/Flutter-0A0E1F?style=flat-square&logo=flutter&logoColor=38BDF8)
![Node.js](https://img.shields.io/badge/Node.js-0A0E1F?style=flat-square&logo=nodedotjs&logoColor=4ECDC4)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0A0E1F?style=flat-square&logo=postgresql&logoColor=38BDF8)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [MediSight-AI](https://github.com/Ihsan-p1/MediSight-AI)

**Reads emotion, drowsiness and pain from a webcam.**

The first numbers looked perfect: 99.97% on fatigue. They were wrong, because frames of the same person sat in both train and test. I withdrew them and re-measured on people the models had never seen. A plain eye-closure signal (EAR) then beat the drowsiness CNN, 0.760 vs 0.690 macro F1.

![Python](https://img.shields.io/badge/Python-0A0E1F?style=flat-square&logo=python&logoColor=4ECDC4)
![PyTorch](https://img.shields.io/badge/PyTorch-0A0E1F?style=flat-square&logo=pytorch&logoColor=A78BFA)
![OpenCV](https://img.shields.io/badge/OpenCV-0A0E1F?style=flat-square&logo=opencv&logoColor=4ECDC4)

</td>
<td width="50%" valign="top">

### [Echo](https://github.com/Ihsan-p1/Echo)

**A robot that listens, looks, then answers.**

Whisper hears, YOLO11 sees, and Llama 3.2 3B replies, all on a laptop, while a Raspberry Pi 4 runs the camera, audio and motors. No LLM command reaches a motor without passing a three-layer safety gate, covered by 71 tests in CI. I tried a LoRA fine-tune and reverted it: the base model wrote more reliable structured output.

![Python](https://img.shields.io/badge/Python-0A0E1F?style=flat-square&logo=python&logoColor=4ECDC4)
![PyTorch](https://img.shields.io/badge/PyTorch-0A0E1F?style=flat-square&logo=pytorch&logoColor=A78BFA)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi%204-0A0E1F?style=flat-square&logo=raspberrypi&logoColor=38BDF8)
![CUDA](https://img.shields.io/badge/CUDA-0A0E1F?style=flat-square&logo=nvidia&logoColor=4ECDC4)

</td>
</tr>
</table>
