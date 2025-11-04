# 🧬 Sickle Cell Detection using CNN

This project detects **Sickle Cell Anemia** from microscopic blood smear images using **Convolutional Neural Networks (CNN)** and advanced **image processing techniques**.

---

## 🚀 Overview

The model analyzes blood cell images and identifies sickle-shaped cells by:
- Converting the images into **grayscale and binary formats**
- Applying the **Watershed algorithm** for segmentation
- Calculating the **percentage of sickled cells**
- Highlighting additional blood abnormalities such as:
  - **Neutrophil deficiency**
  - **Lymphocyte imbalance**

---

## 🧠 Tech Stack

- **Python 3.x**
- **TensorFlow / Keras** – for CNN model building  
- **OpenCV** – for image preprocessing and segmentation  
- **NumPy** – for matrix operations  
- **Matplotlib** – for visualization  
- **Scikit-learn** – for metrics and model evaluation  
- **Jupyter Notebook / Google Colab** – for experimentation  

---

## ⚙️ How It Works

1. **Input:** Blood smear image.  
2. **Preprocessing:**
   - Convert to grayscale and binary.
   - Apply noise removal and thresholding.
3. **Segmentation:**
   - Use **Watershed algorithm** to separate overlapping cells.
4. **Feature Extraction:**
   - Identify contours and detect sickle shapes.
5. **Classification:**
   - CNN model predicts if the cells are sickled or normal.
6. **Output:**
   - Displays:
     - Sickle cell percentage.
     - Detection of any other blood abnormalities.

---

## 📊 Example Output

```text
Sickle Cell Percentage: 27.4%
Detected Condition: Neutrophil Deficiency
Status: Abnormal
