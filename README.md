# 🎨 Real-Time Color Identification & Detection Tool

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/OpenCV-Computer_Vision-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV" />
  <img src="https://img.shields.io/badge/Pandas-Data_Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License" />
</p>

## 📌 Overview
An interactive Computer Vision application built with **Python**, **OpenCV**, and **Pandas** that accurately detects and names colors from any pixel coordinate of an image upon double-clicking. It calculates the minimum Euclidean distance between the sampled pixel's RGB values and a curated dataset of over 865 named colors.

---

## ✨ How It Works

```text
User Double-Clicks Image Pixel
            │
            ▼
Extract (R, G, B) Coordinates
            │
            ▼
Compute Euclidean Distance across colors.csv
Distance = abs(R - cR) + abs(G - cG) + abs(B - cB)
            │
            ▼
Display Identified Color Name & Real-time Hex/RGB Banner Overlay
```

---

## 🚀 Quickstart & Usage

### 1. Install Requirements
```bash
pip install opencv-python pandas numpy
```

### 2. Run Color Detection
```bash
python color_detection.py -i colorpic.jpg
```
- **Double click** anywhere on the image window to inspect the color name and RGB breakdown.
- Press **`Esc`** key to exit.

---

## 👨‍💻 Author
**Muhammad Okasha**  
[GitHub Profile](https://github.com/muhammadokashapak)
