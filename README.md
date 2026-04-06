# 🎯 YOLOv8 Object Detection Lab

> **Lab Assignment** — Deep Learning & Computer Vision | 2025–26  
> **Institute:** MIT Academy of Engineering | **Department:** Software Engineering & ENTC  
> **Course Code:** MDM | **Semester:** VII | **Batch:** T1 and T4

---

## 👥 Group Details

| # | Member | PRN | GitHub |
|---|--------|-----|--------|
| 1 (Leader) | Aryan Kumar | 202301070164 | [@Aryankr0711](https://github.com/Aryankr0711) |
| 2 | Siddhant Kumar Sahu | 202301070159 | [@siddsahu17](https://github.com/siddsahu17) |
| 3 | Amir Furquani | 202301070165 | [@Amirfurquani](https://github.com/Amirfurquani) |
| 4 | Raviraj Vijay Sonar | 202301070167 | [@RavirajSonar40](https://github.com/RavirajSonar40) |

**Faculty:** Dr. Diptee Ghusse (HOD AIML)  
**Lab Date:** 24/03/2026 | **Submission Date:** 25/03/2026

---

## 📋 About This Project

This project implements **object detection**, **instance segmentation**, and **image classification** using **YOLOv8** (Ultralytics). We evaluate multi-task performance across YOLOv8 variants and explore real-world applications of multi-task YOLO models.

---

## 🔧 Setup

```bash
pip install ultralytics==8.2.0 roboflow supervision matplotlib seaborn pandas numpy opencv-python-headless Pillow PyYAML
```

---

## 🚀 Run

Open `YOLOv8_Object_Detection_Lab_Template.ipynb` in Google Colab and run all cells sequentially.  
Ensure GPU runtime is enabled: `Runtime → Change runtime type → GPU`

---

## 🖼️ Sample Data

![Sample Data](./results/sample_images.png)

---

## 📊 Results

### Training Curves and Loss per Epoch
![Training Results](./results/training_curves.png)

| Task | Model | mAP@50 | mAP@50-95 | Top-1 Acc | Inf. Time (ms) |
|------|-------|--------|-----------|-----------|----------------|
| Detection | YOLOv8n | — | — | N/A | — |
| Segmentation | YOLOv8n-seg | — | — | N/A | — |
| Classification | YOLOv8n-cls | N/A | N/A | — | — |

> Fill in actual values after running training and evaluation cells.

---

## 🌍 Application

> Describe your chosen real-world application domain here (Section 12 of the notebook).

---

## 📁 File Structure

```
.
├── YOLOv8_Object_Detection_Lab_Template.ipynb   # Main notebook
├── README.md
├── requirements.txt
└── results/
    ├── detection_output.png
    ├── segmentation_output.png
    ├── classification_top5.png
    ├── seg_comparison.png
    ├── benchmark_comparison.png
    └── training_curves.png
```

---

## 📜 Undertaking

All code is original group work. Submitted as per academic undertaking signed by all group members.
