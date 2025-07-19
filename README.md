# ASL Alphabet Recognition using CNN

This project is a deep learning-based American Sign Language (ASL) alphabet recognition system. It uses a Convolutional Neural Network (CNN) model trained on image data to classify hand gestures representing ASL alphabets A-Z.

## 📌 Features
- Recognizes 26 ASL alphabet gestures (A-Z)
- Built with Python and Keras/TensorFlow
- Jupyter Notebook implementation
- Accuracy tracking and model evaluation
- Useful for educational or assistive technology applications

## 🧠 Model Architecture
- Convolutional layers with ReLU activation
- MaxPooling layers
- Fully connected Dense layers
- Softmax output for 26 classes

## 🛠️ Installation
```bash
Clone the repo:

git clone https://github.com/yourusername/asl-alphabet-recognition-cnn.git
cd asl-alphabet-recognition-cnn 

# Install dependencies:

pip install -r requirements.txt

# 🚀 Usage
# Run the notebook:
```bash
jupyter notebook ASL.ipynb

📁 Dataset
This notebook assumes you are using the ASL Alphabet dataset from Kaggle. Download and extract it into a data/ folder.

📊 Results
Model reaches high accuracy (~95%+) on validation data.
