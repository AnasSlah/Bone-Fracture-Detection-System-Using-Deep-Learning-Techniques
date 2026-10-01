# 🦴 Bone Fracture Detection System Using Deep Learning 

## 📌 About The Project
This repository contains the graduation research project submitted to the **Department of Information Technology at Omdurman Ahlia University, Sudan**. It presents a robust AI-based diagnostic support system designed to analyze bone X-ray images automatically and detect fractures with high precision.

To address the challenges of medical imaging in emergency settings and resource-limited environments, this system utilizes a **hierarchical architecture of eight AI models (M0-M7)**. It effectively combines **Convolutional Neural Networks (CNNs)** for anatomical region classification and **YOLO** for precise fracture localization. The models were trained on a dataset of approximately 24,000 X-ray images to ensure reliable clinical performance.

## 🚀 System Architecture (M0 - M7)
The system operates through a multi-level intelligent pipeline:
* **M0 (Gatekeeper):** Validates whether the uploaded image is a legitimate X-ray.
* **M1-M6 (Region Classifiers):** A series of CNN models that accurately classify the anatomical region (e.g., Pelvis, Knee, Ankle, Chest, Skull, Arm).
* **M7 (Fracture Detector):** A YOLO-based object detection model that analyzes the identified region, detects fractures, and outputs bounding boxes with confidence scores.

## 🛠️️ Tech Stack
* **Machine Learning & Computer Vision:** Python, TensorFlow / Keras, Ultralytics YOLO, OpenCV.
* **Web Interface & Backend:** Flask (Python).
* **Environment:** Google Colab (Training & Deployment).

## 📊 Key Features
* **Automated Workflow:** Seamless processing from image upload to final diagnostic report.
* **High-Speed Inference:** Optimized for quick detection to aid medical staff in emergency rooms.
* **Interactive UI:** A user-friendly web interface designed for doctors and patients to upload scans and view detailed annotated results.

## 👥 Research & Development Team
* **Prepared by:** 
  * Anas Ahmed Salah Abdalazeez
  * Awab Ayman Ibrahim Mahdi
  * Gehan Mahgoub Alsadig Mohamed 
  * Rayan Alsadig Mohamed Suliman
* **Supervised by:** Dr. Rami Badr Eldeen

---
*This project was developed as a Bachelor's degree graduation requirement for the Batch One IT students (2026).*
