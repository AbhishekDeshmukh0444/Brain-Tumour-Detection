
# Optimized Brain Tumor Detection: A Dual-Module Approach for for MRI Image Enhancement and Tumor Classification

This project presents a dual-module system for detecting brain tumors in MRI scans. The system is designed to first enhance MRI images using image processing techniques and then classify them using a deep learning model. A user-friendly web interface built using Flask allows users to upload MRI scans and view predictions in real time.

🔗 GitHub Repository: [https://github.com/AbhishekDeshmukh0444/Brain-Tumour-Detection](https://github.com/AbhishekDeshmukh0444/Brain-Tumour-Detection)

## 🔍 Project Overview

- **Module 1: MRI Image Enhancement**  
  Applies contrast enhancement techniques (e.g., CLAHE) to improve MRI quality before classification.

- **Module 2: Tumor Classification**  
  A Convolutional Neural Network (CNN)-based model is used to classify the MRI scan as Glioma , Meningioma , Pituitary and No Tumor.

## 📌 Features

- Upload and process MRI images via a Flask web interface.
- Automatically enhances MRI images for better feature extraction.
- Predicts presence of a tumor using a trained deep learning model.
- Displays enhanced image and prediction result to the user.

## 🧠 Technologies Used

- **Programming Language**: Python  
- **Frameworks & Libraries**:
  - Flask (for web app)
  - OpenCV, NumPy (for image processing)
  - TensorFlow / Keras (for deep learning)
  - Matplotlib, scikit-learn (for evaluation metrics)

## 📁 Dataset

The dataset consists of MRI images with trained and tested images labeled as "Glioma","Meningioma","Pituitary" and "No Tumor". Preprocessing steps include:
- Resizing to uniform dimensions
- Normalization
- Data augmentation (if applicable)

## 🛠️ Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/AbhishekDeshmukh0444/Brain-Tumour-Detection.git
   cd Brain-Tumour-Detection
   ```

2. **Create a virtual environment (optional)**  
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Flask app**  
   ```bash
   python app.py
   ```

5. **Access the web app**  
   Open your browser and go to `http://localhost:5000`

## 🧪 Evaluation Metrics

- **Accuracy**: 95.88 % 
- **Precision**:95%
- **Recall**: 95%  
- **F1 Score**: 95%

_(Replace these with actual values from your evaluation)_

## 📷 Sample Output
![alt text](image.png)
- Upload MRI image  
- View enhanced image  
- View tumor prediction result (TYpe of Tumor)

## 🚀 Future Work

- Deploying the model on Heroku or AWS
- Improving prediction accuracy and UI responsiveness

## 👥 Contributors

- **Utkarsh Gaikwad**  
- **Akash Devmore**  
- **Abhishek Deshmukh**  
- **Pratik Karode**

Final Year, Electronics and Communication Engineering  
VNIT Nagpur

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
