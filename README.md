# Point_Operators---Computer-Vision
## 📁 Image Processing Fundamentals — Point Operations, Sampling & Interpolation

This Jupyter Notebook is a hands-on project that complements the _"EN3160 L02 - Basics and Point Operations"_ lecture. It provides practical, Python-based demonstrations of the core image processing concepts introduced in the module using OpenCV, NumPy, and Matplotlib.

Each concept from the lecture slides is implemented, visualized, and explained in detail with real images and step-by-step code. The notebook helps bridge theory and application—ideal for self-learning, revision, or lab-based understanding.

---

## 🎯 Topics Covered

### 🔹 1. Digital Image Basics
- What is a grayscale and color digital image?
- Pixel value ranges and image resolution
- DPI and its impact on print/display

### 🔹 2. Image Display and Access
- Creating and displaying grayscale and color images
- Using OpenCV and Matplotlib for image handling
- Understanding image shape, datatype, and size

### 🔹 3. Point Operations
- Brightness adjustment using both vectorized and loop-based methods
- Accessing and modifying individual color channels (RGB planes)

### 🔹 4. Sampling and Reconstruction
- What happens when an image or signal is undersampled
- Real-world aliasing effects (e.g., wagon wheel effect)
- The Nyquist-Shannon sampling theorem

### 🔹 5. Image Resampling and Interpolation
- Subsampling (with and without pre-filtering)
- Gaussian filtering to reduce aliasing
- Upsampling with interpolation
- Bilinear interpolation explained and visualized

### 🔹 6. Intensity Transformations
- Identity and negative transforms
- Intensity windowing
- Gamma correction and power-law transformation

### 🔹 7. Histograms and Histogram Equalization
- How to compute and interpret histograms
- Histogram-based brightness and contrast analysis
- Performing histogram equalization using OpenCV and manually

---

## 📊 Technologies Used

- Python 3.x  
- OpenCV (`opencv-python`)  
- NumPy  
- Matplotlib  
- Jupyter Notebook

---

## 📁 How to Use

1. Clone or download this repository.
2. Open the notebook file:  
   **`Point_Operations`**
3. Make sure the required libraries are installed:
   ```bash
   pip install opencv-python numpy matplotlib
