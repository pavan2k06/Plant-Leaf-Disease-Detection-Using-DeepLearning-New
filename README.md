# 🌿 Plant Leaf Disease Detection Using Deep Learning  
### EfficientNetB4-based Plant Disease Classification System  

---

## 📌 Overview  
This project is an AI-powered system that detects **38 plant leaf diseases** using **EfficientNetB4**, a state-of-the-art deep learning model.  
It helps farmers, researchers, and agricultural experts diagnose diseases early and prevent large-scale crop damage.

This project includes:  
✔️ Machine Learning Model  
✔️ Image Preprocessing  
✔️ GUI Application  
✔️ Training Notebook  
✔️ Dataset details  
✔️ Model Download Link  

---

## 🎯 Features  
- 🌱 Detects **38 different plant diseases** (PlantVillage Dataset)  
- 🧠 Uses **EfficientNetB4 Transfer Learning**  
- 📊 Achieves **99% test accuracy**  
- 🖼️ Simple single-image prediction  
- 🖥️ Includes **Tkinter GUI** for offline use  
- 📁 Clean folder structure  
- 🔗 Model hosted on Google Drive for download  
- ⚡ Fast and lightweight inference  

---

## 🧠 Download Trained Model (Required for Predictions)

GitHub does not allow files >100MB.  
Download the trained model here:

🔗 **Google Drive — leaf_disease_model.h5**  
https://drive.google.com/file/d/1kSUPm3IKjIafyEnTN0IiC2PaMkuw5QJb/view?usp=drive_link

Place the model inside:

---

## 📂 Project Structure  
Plant-Leaf-Disease-Detection-AI/
│
├── model/
│ └── leaf_disease_model.h5 # Download from Google Drive
│
├── src/
│ ├── train_model.ipynb # Training notebook (Google Colab)
│ ├── predict_single_image.py # Script for single image prediction
│ ├── gui_app.py # Tkinter-based GUI app
│ └── utils.py # Helper utilities
│
├── screenshots/
│ ├── gui_output.png
│ ├── prediction.png
│ ├── sample_inputs.png
│
├── dataset_info/
│ ├── class_names.txt
│ └── dataset_description.md
│
├── README.md
└── requirements.txt


---

## 🧪 Dataset Details  
The model was trained using the **PlantVillage Dataset (Augmented)** containing leaf images from:

- Apple  
- Grape  
- Corn  
- Strawberry  
- Peach  
- Tomato  
- Pepper  
- Blueberry  
- Orange  

Includes both **healthy** and **diseased** leaf images.

Dataset link:  
https://data.mendeley.com/datasets/tywbtsjrjv

---

## ⚙️ Technologies Used  
- Python  
- TensorFlow / Keras  
- EfficientNetB4  
- NumPy, Pandas  
- PIL & OpenCV  
- Matplotlib  
- Tkinter (Desktop GUI)  
- Google Colab  

---

how_to_run_project:
  prerequisites:
    python_version: "Python 3.9 / 3.10 / 3.11"
    notes:
      - "Check 'Add Python to PATH' during installation."
      - "Works on Windows/Linux/macOS."
      - "GPU is optional."

  step_1_install_dependencies:
    instructions:
      - "Open Command Prompt or Anaconda Prompt."
      - "Navigate to the project directory:"
      - "cd Plant-Leaf-Disease-Detection-AI"
      - "Install the required libraries:"
      - "pip install -r requirements.txt"

    installs:
      - TensorFlow
      - Keras
      - NumPy
      - Pillow
      - Matplotlib
      - OpenCV
      - Tkinter

  step_2_download_model:
    model_file: "leaf_disease_model.h5"
    download_link: "https://drive.google.com/file/d/1kSUPm3IKjIafyEnTN0IiC2PaMkuw5QJb/view?usp=drive_link"
    place_file_in_directory: "Plant-Leaf-Disease-Detection-AI/model/leaf_disease_model.h5"
    note: "Create 'model/' folder if it does not exist."

  step_3_run_gui_application:
    command: "python src/gui_app.py"
    features:
      - "Upload any leaf image."
      - "Displays predicted class."
      - "Shows confidence score."
      - "Works offline."

  step_4_run_single_image_prediction:
    file_to_edit: "src/predict_single_image.py"
    instructions:
      - "Update the image path inside the script."
      - "Run the prediction:"
      - "python src/predict_single_image.py"
    output:
      - "Predicted class"
      - "Probability values"

  system_requirements:
    minimum_ram: "4GB"
    supported_os:
      - "Windows 10/11"
      - "Linux"
      - "macOS"
    internet_needed: "No (offline after setup)"
    gpu_needed: "No (training already completed)"

  final_notes:
    - "Ensure model file is not pushed to GitHub (.h5 > 100MB)."
    - "GUI is powered by Tkinter."
    - "EfficientNetB4 is used for classification."
    - "Dataset is PlantVillage (Augmented)."



