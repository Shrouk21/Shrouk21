<p align="center">
  <img src="./assets/banner.svg" alt="Shrook Kassem — AI Engineer, model & data optimization" width="100%">
</p>

<p align="center">
  <a href="https://shrouk21.github.io"><img src="https://img.shields.io/badge/Portfolio-0C1626?style=for-the-badge&logoColor=4ADEC0" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/shrook-kasem-266615220"><img src="https://img.shields.io/badge/LinkedIn-2563EB?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:shrookkasem123@gmail.com"><img src="https://img.shields.io/badge/Email-0E7C66?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

I work on making deep learning models perform better **without spending more compute to get there** — through architectural refinements and data-level improvements.

Research Assistant at **NISC, Nile University** · M.Sc. student in **Artificial Intelligence** · Two papers under review.

<br>

## Selected work

<table>
<tr>
<td width="120" align="center"><h3>4→2</h3><sub>GPUS REQUIRED</sub></td>
<td>
<b><a href="https://github.com/Shrouk21/modified_stp3">ST-P3 — End-to-End Autonomous Driving</a></b><br>
Refactored the official codebase — perception, prediction, and planning unified through spatial-temporal feature learning — and re-engineered training for distributed execution, bringing a 4×V100 setup down onto 2×T4 on Kaggle. Evaluated on nuScenes.<br>
<sub><code>PyTorch</code> <code>Distributed training</code> <code>nuScenes</code> · <i>original method: Hu et al., ECCV 2022</i></sub>
</td>
</tr>

<tr>
<td width="120" align="center"><h3>87%</h3><sub>DICE · +10%</sub></td>
<td>
<b>3D Segmentation for Cardiac MRI Cine Views</b><br>
ResNet-style segmentation with a diffusion model applied at inference time to lift performance on small, under-represented classes. 87% Dice, 89% foreground — 10% over baseline.<br>
<sub><code>PyTorch</code> <code>Medical imaging</code> <code>Diffusion</code> · <i>private — paper in preparation</i></sub>
</td>
</tr>

<tr>
<td width="120" align="center"><h3>92.1%</h3><sub>ALLOCATION RATE</sub></td>
<td>
<b><a href="https://github.com/Shrouk21/Reinforcement-Learning-for-Cloud-VM-Allocation-Strategy">RL for Cloud VM Allocation</a></b><br>
A PPO agent that selects an allocation <i>strategy</i> per request rather than a specific machine — collapsing an unwieldy action space into a tractable one. 100% high-priority success, beating every fixed heuristic under contention.<br>
<sub><code>PPO</code> <code>Gymnasium</code> <code>SQL</code> <code>PSO</code></sub>
</td>
</tr>

<tr>
<td width="120" align="center"><h3>+25%</h3><sub>RELEVANCE</sub></td>
<td>
<b><a href="https://github.com/Shrouk21/Assistant-chatbot">Agentic Code Assistant with RAG</a></b><br>
A LangGraph agent that classifies each request and routes it to a specialized path — generation, explanation, or analysis — with ChromaDB retrieval supplying code context. The conditional workflow carried the gain, not the prompt.<br>
<sub><code>LangGraph</code> <code>LangChain</code> <code>RAG</code> <code>ChromaDB</code></sub>
</td>
</tr>

<tr>
<td width="120" align="center"><h3>96%</h3><sub>ACCURACY</sub></td>
<td>
<b><a href="https://github.com/Shrouk21/Arabic-Dialect-Sentiment-Analysis">Arabic Dialect Sentiment Analysis</a></b><br>
AraBERT and MarBERT fine-tuned for multi-dialect classification, with preprocessing built specifically around a small, unevenly distributed dataset.<br>
<sub><code>AraBERT</code> <code>MarBERT</code> <code>Low-resource NLP</code></sub>
</td>
</tr>

<tr>
<td width="120" align="center"><h3>8</h3><sub>CLASSES</sub></td>
<td>
<b><a href="https://github.com/Shrouk21/UNet-ObjectDetection-Lyft">U-Net Semantic Segmentation</a></b><br>
Encoder-decoder with skip connections for pixel-level classification on the Lyft self-driving dataset, wrapped in a full PyTorch Lightning pipeline with scheduling, checkpointing, and TensorBoard tracking.<br>
<sub><code>U-Net</code> <code>PyTorch Lightning</code> <code>TensorBoard</code></sub>
</td>
</tr>
</table>

<br>

## Publications

| Venue | Paper | Status |
|:--|:--|:--|
| **UBMK 2026** | Efficient Forecasting of Chaotic Attractors Using Machine Learning and Phase Space Reconstruction | Under review |
| **MIUCC 2026** | Few Words, Many Dialects: Benchmarking Transformers for Low-Resource Arabic Dialect Sentiment Analysis | Under review |

<br>

## Stack

<p>
<img src="https://img.shields.io/badge/Python-1B2B45?style=flat-square&logo=python&logoColor=4ADEC0">
<img src="https://img.shields.io/badge/SQL-1B2B45?style=flat-square&logo=postgresql&logoColor=4ADEC0">
<img src="https://img.shields.io/badge/C++-1B2B45?style=flat-square&logo=cplusplus&logoColor=4ADEC0">
<img src="https://img.shields.io/badge/Java-1B2B45?style=flat-square&logo=openjdk&logoColor=4ADEC0">
<img src="https://img.shields.io/badge/MATLAB-1B2B45?style=flat-square&logoColor=4ADEC0">
</p>

<p>
<img src="https://img.shields.io/badge/PyTorch-1B2B45?style=flat-square&logo=pytorch&logoColor=4ADEC0">
<img src="https://img.shields.io/badge/Lightning-1B2B45?style=flat-square&logo=lightning&logoColor=4ADEC0">
<img src="https://img.shields.io/badge/TensorFlow-1B2B45?style=flat-square&logo=tensorflow&logoColor=4ADEC0">
<img src="https://img.shields.io/badge/scikit--learn-1B2B45?style=flat-square&logo=scikitlearn&logoColor=4ADEC0">
<img src="https://img.shields.io/badge/OpenCV-1B2B45?style=flat-square&logo=opencv&logoColor=4ADEC0">
<img src="https://img.shields.io/badge/YOLOv8-1B2B45?style=flat-square&logoColor=4ADEC0">
</p>

<p>
<img src="https://img.shields.io/badge/LangChain-1B2B45?style=flat-square&logo=langchain&logoColor=4ADEC0">
<img src="https://img.shields.io/badge/LangGraph-1B2B45?style=flat-square&logoColor=4ADEC0">
<img src="https://img.shields.io/badge/Hugging%20Face-1B2B45?style=flat-square&logo=huggingface&logoColor=4ADEC0">
<img src="https://img.shields.io/badge/RAG-1B2B45?style=flat-square&logoColor=4ADEC0">
<img src="https://img.shields.io/badge/LoRA%20%2F%20PEFT-1B2B45?style=flat-square&logoColor=4ADEC0">
</p>

<p>
<img src="https://img.shields.io/badge/FastAPI-1B2B45?style=flat-square&logo=fastapi&logoColor=4ADEC0">
<img src="https://img.shields.io/badge/Flask-1B2B45?style=flat-square&logo=flask&logoColor=4ADEC0">
<img src="https://img.shields.io/badge/Docker-1B2B45?style=flat-square&logo=docker&logoColor=4ADEC0">
<img src="https://img.shields.io/badge/Azure-1B2B45?style=flat-square&logo=microsoftazure&logoColor=4ADEC0">
<img src="https://img.shields.io/badge/Git-1B2B45?style=flat-square&logo=git&logoColor=4ADEC0">
</p>

<br>

## Also built

**Early Warning Water Pollution Detection** — anomaly detection over multi-sensor time series; +22% early detection rate over heuristic baselines.

**RL for Wireless QoS Optimization** — adaptive QoS framework; 18% better throughput-latency tradeoff.

**Audio Classification via Spectrograms** — audio recast as images, Librosa spectrograms into a FastAI ResNet vision learner.

<br>

---

<sub>Open to AI/ML engineering roles where model quality and compute cost both matter.</sub>
