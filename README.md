# 👁️ Diabetic Retinopathy Detection

A deep learning-based project for the detection and classification of diabetic retinopathy from retinal fundus images.

## 📌 Overview

Diabetic Retinopathy is a diabetes complication that affects eyes and can lead to vision loss if untreated. This project uses Convolutional Neural Networks (CNNs) to detect the severity of retinopathy from fundus images.

## 🧠 Model

- Model Type: CNN / Transfer Learning (e.g., EfficientNet, ResNet, etc.)
- Classes:
  - 0: No DR
  - 1: Mild
  - 2: Moderate
  - 3: Severe
  - 4: Proliferative DR
- Input Size: 224x224 (adjustable)
- Loss Function: Categorical Crossentropy
- Optimizer: Adam / SGD
- Evaluation Metrics: Accuracy, AUC, Confusion Matrix

## 📁 Folder Structure

Diabetic Retinopathy/
├── dataset/
├── flask/ # Web app for model inference
│ ├── app.py
│ └── templates/
├── notebooks/ # Jupyter notebooks
├── models/ # Saved models
├── utils/ # Helper scripts
├── requirements.txt
└── README.md

bash
Copy
Edit

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/GithubSaurabh1/Diabetic-Retinopathy.git
   cd Diabetic-Retinopathy
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Train the model

bash
Copy
Edit
python train.py
Run the Flask app

bash
Copy
Edit
cd flask
python app.py
Then open http://localhost:5000 in your browser.

📊 Results
Metric	Value
Accuracy	95.2%
AUC	0.97
F1-Score	0.93

(Add your actual results above.)

🖼️ Sample Prediction
Upload a retinal image and receive:

The predicted DR grade

Confidence score

Suggested action (e.g., consult ophthalmologist)

🛠️ Technologies Used
Python

TensorFlow / PyTorch

OpenCV

Flask

Pandas, NumPy, Matplotlib

📚 Dataset
Used the APTOS 2019 or similar publicly available dataset from Kaggle.

🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

📜 License
MIT

