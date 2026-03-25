# Object detection for in-store inventory management

![Python](https://img.shields.io/badge/python-3.9%2B-brightgreen.svg)
![Framework](https://img.shields.io/badge/Framework-TensorFlow%20%2F%20PyTorch-orange.svg)
![Docker](https://img.shields.io/badge/Docker-Ready-blue.svg)

## 📝 Project Overview
This project delivers an **API service** backed by machine learning models to automate inventory tracking in retail environments. The system processes images of store shelves and returns precise bounding boxes with product locations, enabling real-time stock management.

**Industries:** Retail, Grocery Stores, Physical Stores.

---

## 🛠️ Technologies and Tools
* **Computer Vision:** Deep Learning, Object Detection (YOLO).
* **Frameworks:** TensorFlow / PyTorch.
* **Deployment:** HTTP APIs, Docker.
* **Languages:** Python.

---

## 👥 The Team
* **Sebastian Contreras** - *Team Leader*
* **Nahim Gomez**
* **Bruno Ruiz**
* **Rosario Ancco Peralta**
* **Daniel Valiente**

---

## 📂 Repository Structure
```text
├── api/                # HTTP API implementation (FastAPI/Flask)
├── models/             # ML Models and weights (YOLO/TensorFlow)
├── data/               # Sample shelf images
├── docker/             # Dockerfiles for deployment
├── notebooks/          # Research and Training
└── requirements.txt    # System dependencies
