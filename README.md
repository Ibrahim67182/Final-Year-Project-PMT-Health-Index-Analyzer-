# ⚡ KE-Portal: Transformer Health Indexer

![Project Banner](https://img.shields.io/badge/AI-Powered-6366F1?style=for-the-badge) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)

An advanced Computer Vision and Deep Learning system for real-time **Pole Mounted Transformer (PMT)** health analysis. Predict failures before they happen with state-of-the-art AI technology integrated beautifully into both a Web Portal and a Mobile Application.

> 🎓 A Final Year Project developed by a team of 3 at **FAST NUCES**



### Project Repo Link: https://github.com/anasahmed81103/FYP-CV_based_Transformer_Health_Indexer

---

## 🌟 Key Features

*   **Intelligence Pipeline:** 
    *   **PMT Classifier Verification:** Non-associated images are immediately filtered using a dedicated classifying neural network to optimize computational load.
    *   **Health Regression Engine:** Evaluates 13 critical structural parameters (e.g., Oil Leakages, Rust, Bushing Cracks) using an **EfficientNet-B0** model to output a concrete Health Defect Percentage.
*   **Grad-CAM Visualizations:** Automatically overlays predictive interactive heatmaps (Grad-CAM) marking exactly where structural defects exist on the original field photograph.
*   **Role-Based Access Control (RBAC):** Strict security tiers (Admin, User, Suspended).
*   **Cross-Platform Architecture:**
    *   **Web Portal**: Next.js & Drizzle ORM powered frontend.
    *   **Mobile App**: Flutter application encompassing GPS mapping, automated Reverse Geocoding (Nominatim), and built-in **Speech-to-Text microphone feedback**.
*   **In-Depth History & Auditing:** PostgreSQL data lakes logging image assets, generated heatmaps, specific geolocation footprinting, and manually collected technician notes.

---

## 🛠️ Tech Stack

### 🤖 AI / Machine Learning
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![EfficientNet](https://img.shields.io/badge/EfficientNet--B0-FF6F00?style=for-the-badge&logo=google&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

### ⚙️ Backend
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Uvicorn](https://img.shields.io/badge/Uvicorn-4B8BBE?style=for-the-badge&logo=python&logoColor=white)
![Gunicorn](https://img.shields.io/badge/Gunicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=white)

### 🌐 Frontend
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### 📱 Mobile
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)

### 🗄️ Database & ORM
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Drizzle ORM](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=for-the-badge&logo=drizzle&logoColor=black)

### ☁️ DevOps & Deployment
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?style=for-the-badge&logo=digitalocean&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![PM2](https://img.shields.io/badge/PM2-2B037A?style=for-the-badge&logo=pm2&logoColor=white)
![systemd](https://img.shields.io/badge/systemd-000000?style=for-the-badge&logo=linux&logoColor=white)

---
_© 2025 KE Portal. Developed to modernize and secure field infrastructure matrices._
