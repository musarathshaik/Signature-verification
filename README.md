# 🖊️ Signature Verification using MATLAB

## 📌 Project Overview

This project was developed as part of my **mini project coursework**. The goal is to build a **signature verification system** using **MATLAB**. The system extracts **normalized static features** from signature images and uses a **neural network** to classify them as **genuine** or **forged**.

---

## 🧠 Methodology

### 1. **Input**
- Signature images (`.png`, `.jpg`) stored in two folders: `genuine/` and `forged/`.

### 2. **Feature Extraction**
- Extracted **static features** from each image, such as:
  - Aspect ratio (height/width)
  - Number of black pixels (ink density)
  - Edge count using Sobel filter
  - Hu Moments
  - Centroid and bounding box info

### 3. **Normalization**
- Features are normalized to a standard range (e.g., 0–1) to remove scale bias.

### 4. **Neural Network Classification**
- A feedforward **Neural Network** is trained to classify:
  - **0** → Forged
  - **1** → Genuine

---

---

## ✅ Requirements

- MATLAB R2020 or later
- Image Processing Toolbox
- Deep Learning Toolbox

---

## 🚀 How to Run

1. Add your signature images into `dataset/genuine/` and `dataset/forged/`.
2. Update `labels.csv` with:
   ```csv
   filename,label
   sig1.png,1
   sig2.png,0
   📊 Output
The model outputs:
1.User interface
![Screenshot 2025-03-14 054309](https://github.com/user-attachments/assets/9a115e51-fec4-4188-9d5b-a71b2d97ad90)
2.Selecting input from Dataset
![Screenshot 2025-03-14 054334](https://github.com/user-attachments/assets/216d10ab-57af-4d4c-a19e-aca443cb408f)
3.Outputs
![Screenshot 2025-03-14 054401](https://github.com/user-attachments/assets/64e64e6c-0907-4e11-8ad8-7ab12fd29fc1)
![Screenshot 2025-03-14 054434](https://github.com/user-attachments/assets/a7e2eedb-a40c-4812-999e-5c9183858b48)


👨‍🎓 Author
Developed by SHAIK MUSARATH
Course: ECE
Institution: Malla reddy engineering college



