# Object Detection for In-Store Inventory Management

![Python](https://img.shields.io/badge/python-3.9%2B-brightgreen.svg)
![Framework](https://img.shields.io/badge/Framework-TensorFlow%20%2F%20PyTorch-orange.svg)
![Docker](https://img.shields.io/badge/Docker-Ready-blue.svg)

## 📝 Project Overview
This project delivers a robust **API service** backed by deep learning models to automate inventory tracking. The system processes images of densely packed store shelves to:
1. Detect and locate individual products (Bounding Boxes).
2. **Identify missing products** (Out-of-stock detection) in empty shelf spots.

**Industries:** Retail, Grocery Stores, Physical Stores.

---

## 📊 Dataset: SKU110K
We utilize the **SKU110K dataset** for training and evaluation, characterized by:
* **11,762 images** with over **1.7 million** annotated bounding boxes.
* Challenging scenarios: multiple scales, viewing angles, and lighting conditions.
* Storage: Managed via **AWS S3** with `boto3`.

---

## 🛠️ Technologies and Tools
* **Computer Vision:** YOLO (v5/v8), Deep Learning, Object Detection.
* **Frameworks:** PyTorch / TensorFlow.
* **Deployment:** FastAPI, Docker, HTTP APIs.
* **Data Science:** Pandas, OpenCV, Matplotlib (EDA).

---

## ✅ Main Deliverables & Milestones
- [x] **Repo Setup:** Repository structure and organization.
- [ ] **EDA:** Exploratory Data Analysis & cleaning of corrupted images.
- [ ] **Data Pipeline:** Scripts for YOLO annotation format and S3 integration.
- [ ] **Model Training:** Object detector for products and missing items.
- [ ] **API & UI:** Containerized service with a web interface for demos.
- [ ] **Evaluation:** Performance metrics (mAP, Precision, Recall).

---

## 👥 The Team
* **Sebastian Contreras** - *Team Leader*
* **Nahim Gomez**
* **Rodrigo Chani**
* **Bruno Ruiz**
* **Rosario Ancco Peralta**
* **Daniel Valiente**

---

## 📂 Repository Structure
```text
├── api/                # HTTP API (FastAPI) & Basic UI
├── models/             # Trained weights (.pt/.h5) and training scripts
├── data/               # EDA notebooks and data pre-processing
├── docker/             # Dockerfiles for API containerization
├── notebooks/          # Research, experiments and evaluation
├── tests/              # Unit tests for helper functions and API
└── requirements.txt    # System dependencies
