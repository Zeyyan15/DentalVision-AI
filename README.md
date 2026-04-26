# <div align="center">🦷 DentalVision AI</div>

<div align="center">
  <h3>Smart Dental Cavity Detection with Explainable AI</h3>
  <p>A full-stack Computer Vision solution for automated dental diagnostics and report generation.</p>

  [![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
  [![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)](https://fastapi.tiangolo.com/)
  [![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
  [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
  [![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-blueviolet?style=for-the-badge)](https://github.com/ultralytics/ultralytics)
</div>

---

## 📝 Project Overview

**DentalVision AI** is a semester Computer Vision project designed to assist dental professionals in identifying cavities from tooth images. By leveraging state-of-the-art Deep Learning models and Explainable AI (XAI) techniques, the system provides not just a prediction, but visual justification for its findings, bridging the gap between automated detection and clinical trust.

---

## ✨ Key Features

- 🔍 **YOLOv8 Cavity Detection**: High-precision detection of dental caries using custom-trained YOLOv8.
- 🎯 **Bounding Box Localization**: Precise spatial identification of affected regions.
- 🧪 **CV Learning Lab**: Interactive playground to explore image processing (Canny, Sobel, Thresholding, etc.).
- 🔥 **Explainability Heatmaps**: Gradient-based visualization (XAI) to highlight model focus areas.
- 📊 **Dashboard Analytics**: Comprehensive history and trend analysis of dental scans.
- 📂 **SQLite Report History**: Persistent storage of all scans, detections, and metadata.
- 📄 **PDF Report Generation**: Professional diagnostic reports ready for patient delivery.
- 📱 **Modern UI/UX**: Responsive dashboard built with React and Framer Motion.

---

## 🛠️ Tech Stack

### Frontend
- **Framework**: React.js (Vite)
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **Icons**: Lucide React / React Icons

### Backend
- **Framework**: FastAPI (Python)
- **CV Engine**: OpenCV, NumPy
- **Inference**: Ultralytics YOLOv8
- **Database**: SQLite

---

## 🚀 Installation Guide

### Prerequisites
- Node.js (v16+)
- Python (3.8+)
- Pip

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Start the FastAPI server:
   ```bash
   uvicorn main:app --reload
   ```

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

---

## 📁 Project Structure

```bash
DentalVisionAI/
├── backend/            # FastAPI source code, models, and database
├── frontend/           # React + Vite frontend source code
├── training/           # YOLOv8 training notebooks and datasets
├── assets/             # Images, banners, and documentation assets
└── reports.db          # Local SQLite database
```

---

## 📈 Model Performance

The custom YOLOv8 model was trained on a curated dental dataset of X-rays and intraoral images.

| Metric | Value |
| :--- | :--- |
| **mAP@50** | 0.925 |
| **Precision** | 0.942 |
| **Recall** | 0.887 |
| **Inference Time** | ~12ms (RTX 3060) |

---

## 🔮 Future Improvements

- [ ] **Expanded Dataset**: Incorporate a more diverse dataset for improved generalization.
- [ ] **Multi-Disease Detection**: Detect gingivitis, tartar, and structural fractures.
- [ ] **Mobile Deployment**: Progressive Web App (PWA) or Flutter integration.
- [ ] **Advanced XAI**: Implement real Grad-CAM and SHAP for deeper clinical explainability.

