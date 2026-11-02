<div align="center">

# 🧠 Brain Tumor Segmentation · YOLOv7

**Pixel-level brain tumor segmentation on MRI scans with YOLOv7 instance segmentation.**

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"> <img src="https://img.shields.io/badge/YOLO-111F68?style=for-the-badge" alt="YOLO"> <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">

<a href="https://colab.research.google.com/github/KamranUmer/MRI-Tumor-segmentation/blob/main/BrainTumor_using_Instance_segmentation_on_custom_using_yolov7_data.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"></a>

</div>

<p align="center"><img src="https://github.com/KamranUmer/MRI-Tumor-segmentation/assets/86089489/4491a8cf-6e81-4b07-9921-d8d47f1d1be2" alt="Brain Tumor Segmentation · YOLOv7 screenshot" width="85%"></p>

## 📌 Overview

Trains YOLOv7's instance-segmentation model to outline brain tumors in MRI images, producing a mask for each tumor rather than just a bounding box.

## 🔬 Pipeline

- Install YOLOv7 (segmentation branch) and requirements
- Custom MRI dataset in YOLOv7 PyTorch format
- Train for 150 epochs on a Colab GPU
- Evaluate box and mask metrics, visualise predictions

## 📊 Results

| Metric | Value |
|---|---|
| Box mAP@0.5 | 0.995 |
| Mask mAP@0.5 | 0.995 |
| Mask mAP@0.5:0.95 | 0.888 |

> Measured on a small validation set (7 images), so treat these as a proof of concept rather than a clinical benchmark.

## 🚀 Getting Started

```bash
# Open the notebook in Google Colab (badge above), choose a GPU runtime,
# then run the cells from top to bottom.
```

## ⚠️ Disclaimer

This project is for research and learning only. It is **not** a medical device and must not be used for diagnosis or treatment decisions.

## 🙏 Acknowledgements

- [YOLOv7](https://github.com/WongKinYiu/yolov7) by WongKinYiu et al.

---

<div align="center">

Built by <a href="https://github.com/KamranUmer"><b>Kamran Umer</b></a> · ⭐ Star the repo if you find it useful

</div>
