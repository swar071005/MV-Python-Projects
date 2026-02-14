# 📌 Experiment 3: Image Restoration of Degraded Surveillance Footage

---

## 🎯 PROJECT OBJECTIVE

The objective of this project is to restore degraded nighttime surveillance images captured in a low-light parking area. The images suffer from noise, motion blur, and distortion due to poor lighting and camera movement. The goal is to apply and compare various image restoration techniques to improve visual clarity and recover meaningful information such as vehicle details and facial features.

---

## 📜 PROBLEM STATEMENT

A surveillance camera installed in a parking area captures footage under nighttime conditions. Due to low illumination, motion blur, and sensor noise, the recorded images are unclear. Important features such as vehicle number plates and faces are not easily recognizable. As a machine vision engineer, you are required to identify types of degradation (noise, blur, motion distortion) and apply suitable restoration techniques to enhance image quality.

---

## 📁 FOLDER CONTENTS
```
Image-Restoration-Project/
│
├── Image_Restoration_Project.ipynb   
└── README.md                         
```

---

## 🛠 TOOLS & TECHNOLOGIES USED

|       Tool          |                Usage                 |
|---------------------|--------------------------------------|
| **Google Colab**    |     Execute Python notebooks online  |
| **Python 3.x**      |          Code implementation         |
| **OpenCV**          |     Image processing and filtering   |
| **NumPy**           |        Numerical computation         |
| **scikit-image**    | Advanced image restoration functions |
| **Matplotlib**      |        Visualization of images       |
| **sklearn.metrics** |        Quantitative evaluation       |

---

## 🧠 METHODOLOGY / STEPS PERFORMED

1. **Data Loading**
   - Load degraded surveillance images.
   - Visualize original degraded images.
2. **Identify Degradation Types**
   - Detect noise patterns (salt-pepper, Gaussian noise).
   - Observe blur and motion distortion.
3. **Apply Restoration Filters**
   - Median Filtering
   - Mean (Averaging) Filtering
   - Max / Min Filters
   - Adaptive Filtering
   - Inverse Filtering (Frequency Domain)
   - Wiener Filtering
4. **Visual Comparison**
   - Display restored images for qualitative assessment.
5. **Quantitative Evaluation**
   - Compute **MSE**
   - Compute **PSNR**
   - Compute **SSIM**
6. **Analysis**
   - Compare performance of each method
   - Identify best restoration approach
7. **Save Results**
   - Export restored image outputs

> Each filter targets a specific type of degradation to evaluate strengths and limitations.

---

## 📊 RESULTS & OBSERVATIONS

|    Technique    |   MSE ↓  |  PSNR ↑ |  SSIM ↑ |       Visual Quality       |
|-----------------|----------|---------|---------|----------------------------|
| Median Filter   | Moderate | Medium  | Medium  | Good for salt-pepper noise |
| Mean Filter     | High     | Low     | Low     |        Blurs edge          |
| Max Filter      | Moderate | Medium  | Medium  |    Removes pepper noise    |
| Adaptive Filter | Lower    | Higher  | Higher  |       Good overall         |
| Inverse Filter  | High     | Low     | Low     |     Sensitive to noise     |
| Wiener Filter   | Lowest   | Highest | Highest |  Best overall restoration  |

**Key Observations:**
- Median and adaptive filters handle noise efficiently with less edge blurring.
- Inverse filter fails under heavy noise.
- Wiener filter produces the best balance of PSNR/SSIM and visual clarity.
- Quantitative metrics closely align with visual quality results.

---

## ▶️ HOW TO RUN / VIEW

1. Click on the Google Colab link below.
2. Upload the `parking_night.zip` folder when prompted (if required).
3. Run the notebook cells sequentially.
4. Observe restored images and metric outputs.
5. Compare results and interpretations.

---

## 💡 KEY LEARNINGS / NOTES

- **Spatial filters** (median, mean) are effective for simple noise.
- **Adaptive filtering** adjusts to local noise conditions.
- **Frequency domain methods** (Inverse, Wiener) are powerful for blur but noise-sensitive.
- **Evaluation metrics** (PSNR, MSE, SSIM) quantify image quality beyond visual interpretation.
- Edge preservation vs noise removal is a crucial trade-off.

---

## 🏁 CONCLUSION

This project demonstrates a complete workflow for image restoration using classic spatial and frequency domain techniques. Among all methods, **Wiener filtering** consistently produced the best results in terms of PSNR and SSIM under combined noise and blur conditions. Understanding how degradation affects image data and selecting appropriate restoration techniques is essential for practical machine vision applications such as surveillance and forensic analysis.

---

## 🔗 Project & Dataset Links
**Google Colab Notebook:** 👉 [https://colab.research.google.com/drive/1wnKkJfkuLqAJDELflLigapxflQSAself#scrollTo=okcld3AM7iqA]

---

## 🙏 ACKNOWLEDGEMENT

I would like to thank my **faculty**, **online communities**, and the **open-source ecosystem** for the invaluable resources and support that helped achieve the objectives of this project.

---

