# 🖼️ Experiment 01 – Image Processing using OpenCV

## 🎯 Project Objective

The aim of this experiment is to understand and implement **basic image processing techniques** using **Python and OpenCV**.
The experiment focuses on image representation, transformations, edge detection, blur detection, and histogram analysis.

---

## 📂 Folder Contents

| File                            | Description                                                  |
| ------------------------------- | ------------------------------------------------------------ |
| `Image_Processing_Basics.ipynb` | Colab notebook with complete image processing implementation |
| `Experiment-01-Report.pdf`      | Report explaining concepts, steps, and results               |
| `README.md`                     | This file with experiment overview                           |

---

## 🛠 Tools & Technologies

* **Python 3.x** – Programming language
* **Google Colab** – Development environment
* **OpenCV (cv2)** – Image processing library
* **NumPy** – Numerical computations
* **Matplotlib** – Image visualization & plotting

---

## 🧩 Problem Statement

Image processing is a core area of computer vision that deals with manipulating and analyzing digital images.
This experiment demonstrates how images are represented as pixel matrices and how different operations like grayscale conversion, edge detection, line detection, blur detection, and histogram analysis are applied.

---

## 🔍 Methodology

1. **Image Upload & Reading**

   * Upload image using Google Colab
   * Read image using OpenCV and analyze dimensions

2. **Color Space Conversion**

   * Convert BGR → RGB for correct visualization
   * Convert RGB → Grayscale

3. **Pixel Matrix Analysis**

   * Display pixel values
   * Inspect individual pixel intensities

4. **Edge Detection**

   * Apply Canny Edge Detection to identify boundaries

5. **Line Detection**

   * Use Hough Line Transformation to detect straight lines

6. **Blur Detection**

   * Apply Laplacian operator
   * Thresholding to separate sharp and blurred regions

7. **Masking & Sharp Region Extraction**

   * Morphological operations to clean noise
   * Extract only clear parts of the image

8. **Histogram Analysis**

   * Plot grayscale histograms
   * Compare original vs sharp-region histograms

9. **Histogram Equalization**

   * Improve image contrast
   * Compare before and after equalization

---

## 📈 Results & Insights

* Edges and straight lines are detected successfully
* Blurred and sharp regions are clearly differentiated
* Histogram analysis provides insight into pixel intensity distribution
* Histogram equalization improves image contrast significantly

---

## 🚀 How to Run / View

1. Open the notebook file: `Image_Processing_Basics.ipynb`
2. Run all cells in Google Colab
3. Upload an image when prompted
4. Observe output images, plots, and histograms

---

## 💡 Notes

* The experiment demonstrates fundamental concepts of image processing
* Suitable as a foundation for advanced computer vision tasks
* Can be extended to object detection, segmentation, or deep learning

---

## 📌 References

* [Google Colab Notebook](https://colab.research.google.com/drive/1pI-ZdNKf6vL5XiWq2tBhYn4fu-IK21BY)
* OpenCV Documentation

---


