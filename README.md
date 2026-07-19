# CodeAlpha_Handwritten_Character_Recognition
A Deep Learning project that recognizes handwritten digits using Convolutional Neural Networks (CNN) and the MNIST dataset.

# ✍️ Handwritten Character Recognition using CNN

## 📌 Project Overview

This project focuses on recognizing handwritten digits using **Convolutional Neural Networks (CNN)** and the **MNIST dataset**. The model learns patterns from thousands of handwritten digit images and accurately classifies them into one of the ten digit classes (0–9). This project demonstrates the practical application of **Deep Learning** and **Computer Vision** for image classification tasks.

---

## 🎯 Project Objective

The objective of this project is to develop a deep learning model capable of accurately recognizing handwritten digits from grayscale images. By leveraging a Convolutional Neural Network (CNN), the project aims to automate digit classification while demonstrating the effectiveness of image preprocessing, feature extraction, and deep learning techniques in computer vision applications.

---

## 📂 Dataset

**Dataset Used:** MNIST Handwritten Digits Dataset

The MNIST dataset contains grayscale images of handwritten digits from **0 to 9**.

### Dataset Information

- **Training Images:** 60,000
- **Testing Images:** 10,000
- **Image Size:** 28 × 28 pixels
- **Classes:** 10 (Digits 0–9)

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- TensorFlow
- Keras
- Scikit-learn
- Google Colab

---

## 📊 Project Workflow

1. Import Required Libraries
2. Load the MNIST Dataset
3. Data Understanding
4. Data Preprocessing
5. Build the CNN Model
6. Compile the Model
7. Train the Model
8. Evaluate Model Performance
9. Generate Predictions
10. Visualize Handwritten Digit Predictions

---

## 🔍 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Sample Handwritten Digit Images
- Image Dimensions
- Pixel Value Range

---

## ⚙️ Data Preprocessing

The following preprocessing techniques were applied:

- Pixel Value Normalization
- Image Reshaping
- One-Hot Encoding of Labels

---

## 🧠 CNN Architecture

The Convolutional Neural Network consists of:

- Input Layer
- Convolutional Layer (32 Filters, 3×3 Kernel)
- Max Pooling Layer
- Dropout Layer
- Flatten Layer
- Fully Connected Dense Layer (128 Neurons)
- Dropout Layer
- Output Layer (10 Neurons with Softmax Activation)

---

## 📈 Model Performance

The CNN model achieved excellent performance on the MNIST dataset.

### Final Results

- **Training Accuracy:** ~98.60%
- **Validation Accuracy:** ~98.70%
- **Test Accuracy:** **98.78%**

The model was evaluated using:

- Classification Report
- Confusion Matrix
- Sample Predictions
- Random Handwritten Digit Prediction

---

## 📷 Sample Prediction

The trained CNN model successfully predicts handwritten digits and compares the predicted digit with the actual label, demonstrating high classification accuracy on unseen images.

---

## 🚀 Future Enhancements

- Train on the EMNIST alphabet dataset
- Recognize handwritten alphabets
- Extend to handwritten word recognition
- Build a real-time digit recognition application
- Deploy the model using Flask or Streamlit

---

## 📁 Project Structure

```
CodeAlpha_Handwritten_Character_Recognition/
│
├── Handwritten_Character_Recognition.ipynb
├── README.md
```

---

## 🎯 Key Features

- Image Classification using Deep Learning
- Convolutional Neural Network (CNN)
- MNIST Handwritten Digit Dataset
- Data Preprocessing
- Model Evaluation
- Classification Report
- Confusion Matrix
- Handwritten Digit Prediction
- Random Sample Prediction
- High Accuracy (~98.78%)

---

## 📚 Learning Outcomes

Through this project, I learned:

- Fundamentals of Computer Vision
- Image Preprocessing Techniques
- Convolutional Neural Networks (CNN)
- TensorFlow & Keras Model Development
- Deep Learning Model Training
- Performance Evaluation using Classification Metrics
- Handwritten Digit Recognition

---

## 👩‍💻 Author

**Kalpana**

Machine Learning Intern

---

## ⭐ Acknowledgement

This project was completed as part of the **CodeAlpha Machine Learning Internship**, applying deep learning techniques to solve handwritten digit recognition problems using the MNIST dataset.
