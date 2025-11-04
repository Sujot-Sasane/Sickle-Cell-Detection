🧬 Sickle Cell Detection using CNN
📖 Overview

This project detects Sickle Cell Disease (SCD) from microscopic blood cell images using a Convolutional Neural Network (CNN).
The system analyzes red blood cell images, converts them into grayscale and binary formats, applies the Watershed algorithm for segmentation, and calculates the percentage of sickle cells.
It also provides insights about other possible blood deficiencies such as Neutrophil or Lymphocyte presence.

⚙️ Technologies Used

Python

TensorFlow / Keras – for CNN model building

OpenCV – for image preprocessing and segmentation

NumPy / Pandas – for data handling

Matplotlib – for visualization

Tkinter – for GUI

Watershed Algorithm – for cell segmentation

🚀 Features

✅ Detects sickle cells in blood smear images using CNN
✅ Converts input images to grayscale and binary formats
✅ Applies the Watershed algorithm for segmentation
✅ Calculates sickle cell percentage in the sample
✅ GUI interface with Registration and Login
✅ Detects other abnormalities (like Neutrophil or Lymphocyte presence)
✅ Easy to use and extendable for other hematological disorders

🖥️ Project Workflow

Image Input: User uploads a microscopic image of blood cells.

Preprocessing:

Image converted to grayscale and binary.

Watershed algorithm applied for segmentation.

CNN Classification:

CNN model predicts sickle vs normal cells.

Percentage of sickle cells calculated.

Results:

Displays detection results in GUI.

Shows other cell abnormalities if present.

📸 Screenshots
🔹 GUI Screens

Registration and Login Interface
<img width="1862" height="956" alt="Screenshoot1" src="https://github.com/user-attachments/assets/bb3204f2-f2d2-4f02-8517-0998019bf0d0" />




🔹 Image Processing Pipeline

Original → Grayscale → Binary → Watershed Output




🔹 Prediction Output

Detection and Report Generation Interface




💡 You can create a Screenshots/ folder in your repo and place all your images there.
Then rename them (e.g., Screenshot1.png, Screenshot2.png, etc.) for clean linking.

🧩 How to Run

1️⃣ Clone the repository

git clone https://github.com/Sujot-Sasane/Sickle-Cell-Detection.git
cd Sickle-Cell-Detection


2️⃣ Install dependencies

pip install -r requirements.txt


3️⃣ Run the application

python main.py

🧠 Model Details

Architecture: CNN (Convolutional Neural Network)

Layers: Convolution → Pooling → Flatten → Dense

Loss Function: Categorical Cross Entropy

Optimizer: Adam

Accuracy: ~97% (on test set)

🔮 Future Enhancements

Integrate with medical APIs for report generation.

Deploy as a web or mobile app using Flask, Streamlit, or Flutter.

Extend detection to other blood disorders.

Train with larger, more diverse datasets.

🙌 Acknowledgment

Developed by Sujot Sasane as a deep learning–based biomedical project using Python and CNNs.
