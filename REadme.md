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



<img width="1738" height="961" alt="Screenshoot2" src="https://github.com/user-attachments/assets/2caf2f53-fe97-4c87-ab6b-ea32e8b2124c" />

🔹 Image Processing Pipeline

Original → Grayscale → Binary → Watershed Output

<img width="1888" height="877" alt="Screenshoot3" src="https://github.com/user-attachments/assets/b6abf131-66d0-4a2f-8bf2-00fe19312794" />


<img width="1845" height="889" alt="Screenshoot4" src="https://github.com/user-attachments/assets/257765bc-e1f7-40e3-bb04-b34167420607" />

🔹 Prediction Output

Detection and Report Generation Interface

<img width="1871" height="905" alt="Screenchoot5" src="https://github.com/user-attachments/assets/f40e8f01-15cb-4230-bfc6-7f3b111b7e04" />


<img width="1911" height="983" alt="Screenshoot6" src="https://github.com/user-attachments/assets/4c71cf10-2af0-44c4-be93-df8b10789c40" />

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
