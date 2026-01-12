# AIDriven-Archaeological-Site-Mapping
It an Archaeological site mapping project, this consist of two models one is for classifying vegetation land or not another model to classify type of soil. These models are going to be used in building  the Archaeological Site Mapping project. 

# 🗺️ AI‑Driven Archaeological Site Mapping

🔗 **Live Application:**  
👉 https://archaeological-frontend-one.vercel.app/

---

## 📌 Overview

**AI‑Driven Archaeological Site Mapping** is a full‑stack web application that uses **artificial intelligence and computer vision** to assist archaeological research through **non‑invasive environmental analysis**.

The platform analyzes:
- **Soil characteristics** to infer potential human activity zones
- **Vegetation patterns** to detect anomalies caused by subsurface structures

By combining environmental science with deep learning, the system helps archaeologists **prioritize areas for investigation** while preserving cultural heritage.

---

## 🎯 Problem Statement

Traditional archaeological surveys:
- Are time‑consuming and labor‑intensive
- Require invasive excavation
- Cannot efficiently cover large geographic regions

However, **subsurface archaeological features alter soil composition and vegetation growth**, creating patterns that can be detected using image analysis.

The challenge is to:
- Detect these patterns automatically
- Deploy the solution on lightweight cloud infrastructure
- Make results accessible through an intuitive web interface

---

## ✅ Solution

This project delivers an **end‑to‑end AI system** that:

- Performs **soil classification** using image data
- Segments **vegetation vs non‑vegetation** areas
- Runs efficiently on **CPU‑only cloud services**
- Provides results via a **modern web application**

---

## 🧠 AI Models Used

### 🟤 Soil Classification
- **Model:** MobileNetV3
- **Task:** Image classification
- **Output:** Soil type (Red, Black, Alluvial, Clay) + confidence score

**Why MobileNetV3?**
- Lightweight and fast
- Low memory footprint
- Ideal for real‑time inference in web applications

---

### 🌱 Vegetation Segmentation
- **Model:** Lightweight UNet (UNet‑Lite)
- **Task:** Binary semantic segmentation
- **Output:** Vegetation vs Non‑Vegetation percentage

**Why UNet‑Lite?**
- CPU‑friendly and stable on cloud platforms
- Efficient pixel‑level segmentation
- Well‑suited for environmental and remote‑sensing imagery

---

## 🏗️ System Architecture

```text
Frontend (React + Vercel)
        |
        | HTTP API Calls
        ↓
Backend (FastAPI + Render)
        |
        | PyTorch Models
        ↓
Soil & Vegetation Analysis

## ⚙️ Tech Stack

### Frontend
- **React**
- Deployed on **Vercel**
- Industrial dark‑themed user interface
- Animated technical background (grid & scan‑line effects)
- Image upload, preview, and result visualization

### Backend
- **FastAPI** (Python)
- **PyTorch** for machine learning inference
- Deployed on **Render**
- RESTful API architecture
- CPU‑optimized inference pipeline

---

## 🌐 Deployment

| Component | Platform |
|---------|----------|
| Frontend | Vercel |
| Backend  | Render |
| Models   | PyTorch |
| API      | FastAPI |

✅ Designed for **free‑tier cloud deployment**  
✅ No GPU required  

---

## 📊 Results & Evaluation

- Accurate soil classification across test images
- Reliable vegetation segmentation using UNet‑Lite
- Model performance evaluated using:
  - **Pixel Accuracy**
  - **Intersection over Union (IoU)**
  - **Dice Score**
  - **Confusion Matrix**
- Stable inference performance on CPU‑only infrastructure

---

## 🔍 Interpretation of Results

- High vegetation coverage may indicate natural growth or fertile soil
- Vegetation anomalies (linear or geometric patterns) may suggest buried structures
- Soil type classification helps contextualize environmental suitability for ancient settlements
- Combined soil and vegetation analysis improves archaeological site prioritization

> ⚠️ AI‑generated results are **indicators**, not definitive conclusions.  
> Archaeological expertise and field validation remain essential.

---

## 🧪 Features

- ✅ Soil type classification with confidence score
- ✅ Vegetation vs non‑vegetation segmentation
- ✅ Vegetation coverage percentage calculation
- ✅ Interactive image upload
- ✅ Mode switching between Soil and Vegetation analysis
- ✅ Responsive and user‑friendly interface
- ✅ Non‑invasive archaeological analysis approach

---

## 🔮 Future Scope

- Integration with satellite and drone imagery
- GIS‑based map overlays
- Temporal vegetation analysis
- Multi‑modal data fusion (soil + vegetation + elevation)
- Offline and field‑deployable versions

---

## 🧑‍🤝‍🧑 Ethical Considerations

- Promotes **non‑destructive archaeological exploration**
- Aims to preserve cultural heritage sites
- Designed as a **decision‑support system**, not a replacement for expert judgment
- Encourages responsible and ethical use of AI in heritage research

---

## 📜 License

This project is intended for **academic, research, and demonstration purposes**.  
Please refer to the repository license file for usage permissions.

---

## 🙌 Acknowledgements

- Roboflow for dataset management and annotation tools
- PyTorch and FastAPI open‑source communities
- Archaeological and environmental research literature

---

## 📬 Contact

For questions, feedback, or contributions, please open an issue or submit a pull request.

---

✅ **Live Demo:**  
👉 https://archaeological-frontend-one.vercel.app/
