# 🖼️ Image_Enhancement_Filtering

---

## 🎯 PROJECT OBJECTIVE

The objective of this experiment is to analyze and enhance real-world images affected by noise, poor contrast, and blurred details using **spatial domain filtering techniques**. The experiment focuses on applying **smoothing filters**, **sharpening filters**, and **histogram analysis** using **Python and OpenCV** to improve image quality while preserving important visual information.

---

## 📂 Folder Contents

| File Name | Description |
|---------|-------------|
| `Image_Enhancement_Spatial_Filtering.ipynb` | Google Colab notebook implementing smoothing filters, sharpening filters, and histogram analysis |
| `image.png` *(optional)* | Input image uploaded during execution |
| `README.md` | Project documentation |

---

## 🛠️ TOOLS & TECHNOLOGIES USED

- 🐍 **Python 3.x**
- ☁️ **Google Colab**
- 📷 **OpenCV (cv2)**
- 🔢 **NumPy**
- 📊 **Matplotlib**

---

## 🧩 PROBLEM STATEMENT

Real-world images captured in low-light or noisy environments often suffer from poor contrast, noise, and blurred details, making them unsuitable for analysis. This experiment demonstrates how image histograms can be analyzed and how appropriate **smoothing and sharpening filters** can be applied to enhance image quality while preserving important visual information.

---

## 🔍 METHODOLOGY / STEPS PERFORMED

### 🔹 1. Image Upload & Reading
- Image uploaded using Google Colab file upload
- Image read using `cv2.imread()`
- Converted to RGB and grayscale formats

### 🔹 2. Display of Original Image
- Original RGB image displayed using Matplotlib
- Grayscale image used for processing

### 🔹 3. Smoothing Filters (Spatial Domain)
Applied to reduce noise:
- Mean (Averaging) Filter
- Gaussian Filter
- Median Filter

### 🔹 4. Sharpening Filters
Applied to enhance edges and details:
- Laplacian Filter
- High-Pass Filter

### 🔹 5. Histogram Analysis
- Histogram of original grayscale image plotted
- Histogram after smoothing plotted
- Histogram after sharpening plotted
- Comparison performed to analyze intensity distribution changes

---

## 📊 RESULTS & OBSERVATIONS

- Mean and Gaussian filters reduced noise but slightly blurred edges
- Median filter preserved edges while effectively reducing noise
- Laplacian and high-pass filters enhanced edges and fine details
- Histogram after smoothing showed reduced intensity variation
- Histogram after sharpening showed expanded intensity distribution
- Visual clarity improved while preserving important features

---

## 🚀 HOW TO RUN / VIEW

1. Open the notebook  
   `Image_Enhancement_Spatial_Filtering.ipynb`
2. Run it in **Google Colab**
3. Upload an image when prompted
4. Execute all cells sequentially
5. Observe filtered images and histogram plots

---

## 💡 KEY LEARNINGS / NOTES

- Smoothing filters are effective for noise reduction
- Median filter works best for impulse noise
- Sharpening filters enhance edges but may amplify noise
- Histogram analysis helps evaluate enhancement effectiveness
- Proper filter selection is crucial for preserving visual information

---

## 🏁 CONCLUSION

In this experiment, image enhancement techniques were applied to improve the quality of real-world images affected by noise, poor contrast, and blurred details. Spatial domain smoothing filters such as mean, Gaussian, and median filters were used to reduce noise, while sharpening filters including Laplacian and high-pass filters were applied to enhance edges and fine details. Histogram analysis before and after processing helped in understanding changes in pixel intensity distribution and contrast. The results show that smoothing filters effectively suppress noise, whereas sharpening filters improve image clarity by emphasizing important visual features. Proper selection of filtering techniques enhances image quality while preserving essential information, making the image suitable for further analysis.

---

## 🔗 REFERENCES

-📘 Google Colab: 👉[https://colab.research.google.com/drive/1sth4DR4fkfoXPW18ArgIgFvaPHpUJLjH?authuser=0#scrollTo=opHxFXM0Qy49]

---

## 🙌 ACKNOWLEDGEMENT

This experiment was carried out as part of **Machine Vision / Computer Vision laboratory work** using Python and OpenCV.

---

