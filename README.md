# multi-tech-image-segmentation
A comprehensive implementation and visual comparison of multiple image segmentation techniques — including Global, Adaptive, and Otsu Thresholding, K-Means Clustering, Mean Shift, Edge Detection, and Watershed Segmentation — showcasing how each method interprets image structure and boundaries.
# 🧩 Multi-Tech Image Segmentation

## 🧠 Overview
This project presents a **comparative analysis of multiple image segmentation techniques**, exploring how each algorithm partitions and interprets visual information.  
From simple thresholding to clustering and region-based segmentation, this repository demonstrates the strengths and limitations of each approach in different image contexts.

Segmentation is a key step in computer vision and medical imaging — helping systems understand object boundaries, textures, and structures.  

---

## ⚙️ Techniques Implemented
The following methods are applied and compared side-by-side:

1. **Original Image** – Base input for visual reference  
2. **Global Thresholding** – Fixed pixel intensity-based segmentation  
3. **Adaptive Thresholding** – Local neighborhood-based segmentation  
4. **Otsu Thresholding** – Automatic threshold optimization  
5. **K-Means Segmentation** – Clustering-based color segmentation  
6. **Mean Shift Segmentation** – Feature-space clustering for smooth segmentation  
7. **Edge Detection (Canny/Sobel)** – Gradient-based boundary detection  
8. **Watershed Segmentation** – Region-growing approach for separating overlapping objects  

---

## 🧰 Tools & Libraries
- **Python**
- **OpenCV**
- **NumPy**
- **Matplotlib**
- (Optional) **scikit-image** for additional filters and morphology


# 3. Otsu Thresholding
_, otsu = cv2.threshold(gray, 0, 255, cv2.THRESH_BINARY + cv2.THRESH_OTSU)
