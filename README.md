🌿 Plant Leaf Disease Detection Using Deep Learning
EfficientNetB4-based Plant Disease Classification System
📌 Overview

This project is an AI-powered system that detects 38 plant leaf diseases using EfficientNetB4, a state-of-the-art deep learning model.
It helps farmers, researchers, and agricultural experts to diagnose diseases from images, enabling early treatment and prevention.

This project includes:
✔️ Machine Learning Model
✔️ Image Preprocessing
✔️ GUI Application
✔️ Training Notebook
✔️ Dataset details
✔️ Model Download Link

🎯 Features

🌱 Classifies 38 plant diseases (PlantVillage Dataset)

🧠 EfficientNetB4 Transfer Learning

📊 99% test accuracy

🖼️ Easy single-image prediction

🖥️ Tkinter GUI app (offline desktop app)

📁 Clean project structure

🔗 Model hosted on Google Drive

⚡ Fast & lightweight inference

🧠 Download Trained Model

GitHub cannot store files larger than 100 MB.
Download the trained model here:

🔗 Google Drive (leaf_disease_model.h5)
https://drive.google.com/file/d/1kSUPm3IKjIafyEnTN0IiC2PaMkuw5QJb/view?usp=drive_link

Place it inside:

/model/leaf_disease_model.h5

📂 Project Structure
Plant-Leaf-Disease-Detection-AI/
│
├── model/
│   └── leaf_disease_model.h5      # Download from Drive link
│
├── src/
│   ├── train_model.ipynb          # Google Colab training file
│   ├── predict_single_image.py    # Script for single image testing
│   ├── gui_app.py                 # Tkinter GUI application
│   └── utils.py                   # Helper functions
│
├── screenshots/
│   ├── gui_output.png
│   ├── prediction.png
│   ├── sample_inputs.png
│
├── dataset_info/
│   ├── class_names.txt
│   └── dataset_description.md
│
├── README.md
└── requirements.txt

🧪 Dataset Details

The model was trained using the PlantVillage Dataset (Augmented) containing:

🍎 Apple

🍇 Grape

🌽 Corn

🍓 Strawberry

🍑 Peach

🍅 Tomato

🫑 Pepper

🫐 Blueberry

🍊 Orange

Includes healthy and infected leaf images.

Dataset link:
https://data.mendeley.com/datasets/tywbtsjrjv

⚙️ Technologies Used

Python 3

TensorFlow / Keras

EfficientNetB4

NumPy, Pandas

PIL & OpenCV

Matplotlib

Tkinter (Desktop GUI)

Google Colab

🚀 How to Run the Project
1️⃣ Install Dependencies
pip install -r requirements.txt

2️⃣ Run The GUI Application
python src/gui_app.py


Browse → Upload a leaf image → Get prediction.

3️⃣ Run Single Image Prediction
python src/predict_single_image.py

📊 Model Performance
Metric	Score
Training Accuracy	98%
Validation Accuracy	80%
Test Accuracy	99%
Loss	Very low
🖥️ Output Screenshots

(Add your images in the screenshots/ folder)

Example:

screenshots/gui_output.png
screenshots/prediction.png

🔮 Future Enhancements

Web-based interface (Flask / FastAPI)

Mobile app using TensorFlow Lite

Real-time camera disease detection

More crop species

Disease treatment recommendations

👨‍💻 Author

Pavan M
B.Tech – CSE (Data Science)

📄 License

This project is open-source and free to use.
