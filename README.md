<div align="center">

# Nada Waleed

**ML / Computer Vision Engineer · Healthcare AI**

*Building systems that turn medical data into clinical insight*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/nada-waleed)
[![HuggingFace](https://img.shields.io/badge/🤗%20Spaces-FFD21E?style=flat)](https://huggingface.co/naddaa)
[![Email](https://img.shields.io/badge/email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:nada@example.com)

</div>

---

## About

I'm a Computer Vision / ML engineer with a focus on healthcare applications — systems where getting the prediction wrong has real consequences for real people.

My work sits at the intersection of:
- **Clinical measurement** — translating domain knowledge (Clarke EGA, ISO 15197, MARD) into loss functions and evaluation protocols
- **Lightweight deployment** — getting models onto Apple Watch, mobile, and edge devices
- **Honest evaluation** — I care about clinical metrics, not just RMSE on a validation split

Currently exploring **MSc programs in Medical AI / ML** (2025 intake). Looking for research roles at the intersection of ML and healthcare.

---

## Projects

### 🩸 [GlucoSense AI — Predictive Glucose Monitor](https://github.com/nada-waleed/diabetes-vision-monitor)
Predicting blood glucose 30 and 60 minutes ahead from continuous CGM sensor data.  
LSTM + Temporal CNN trained on OhioT1DM, evaluated with Clarke Error Grid.  
Exported to Core ML (197 KB) and deployed on watchOS via HealthKit.

`PyTorch` `Core ML` `Swift` `watchOS` `HealthKit` `Streamlit`

> **Live demo:** [glucosense-ai.hf.space](https://huggingface.co/spaces/naddaa/glucosense-ai)

---

### 🔬 [U-Net Replication — Retinal Vessel Segmentation](https://github.com/nada-waleed/paper-replication)
From-scratch replication of Ronneberger et al. (2015) on the DRIVE fundus dataset.  
Includes architecture ablation (BN, dropout, depth) and Grad-CAM visualization.

`PyTorch` `Albumentations` `DRIVE dataset` `Grad-CAM`

---

### 🔍 [Face Symmetry Analyzer](https://github.com/nada-waleed/face-analysis-app)
Bilateral facial symmetry analysis using MediaPipe Face Mesh (468 3D landmarks).  
Measures per-region geometric asymmetry normalized to inter-ocular distance.  
Includes explicit ethical limitations section — this measures geometry, not attractiveness.

`MediaPipe` `OpenCV` `Gradio` `HuggingFace Spaces`

> **Live demo:** [face-analysis-app.hf.space](https://huggingface.co/spaces/naddaa/face-analysis-app)

---

### 📓 [ML Study Notes](https://github.com/nada-waleed/ml-study-notes)
Working notes on the math and code behind modern ML — linear algebra, attention, CNNs, paper notes.  
Implemented from scratch: multi-head attention, dilated convolutions, Grad-CAM, LoRA intuition.

`Jupyter` `PyTorch` `NumPy` `Matplotlib`

---

## Skills

```
Deep Learning    PyTorch · Core ML · TorchScript · ONNX
CV / Medical     Segmentation · Detection · Time Series · CGM Analysis
Deployment       watchOS · HuggingFace Spaces · Streamlit · Gradio
Languages        Python · Swift · SQL
Infrastructure   Git · Docker · W&B
```

---

## Research interests

- **Clinical AI evaluation** — gap between academic benchmarks and clinical utility
- **Uncertainty quantification** — models should express doubt, not be confidently wrong
- **Efficient inference** — making research-grade models deployable on wearables and mobile
- **Multimodal medical data** — fusing CGM + insulin + activity for glucose prediction

---

## Currently reading

- Isensee et al. (2021) — nnU-Net: a self-configuring method for deep learning-based biomedical image segmentation
- Dao et al. (2022) — FlashAttention: Fast and Memory-Efficient Exact Attention
- Hu et al. (2022) — LoRA: Low-Rank Adaptation of Large Language Models

---

<div align="center">

*"A glucose prediction that is 25 mg/dL off in the safe zone is clinically irrelevant. The same error during hypoglycemia could cause a dangerous overcorrection. RMSE alone won't tell you which one you have."*

</div>
