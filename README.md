<div align="center">

# 🌱 PLANT-AI  
### Recognition of Plant Diseases Using Leaf Image Classification

</div>

## 📌 Description

Agriculture plays a critical role in global food security, and early detection of plant diseases is essential to reduce crop losses and improve productivity. Traditional disease identification methods rely heavily on manual inspection by farmers or agricultural experts, which can be time-consuming, expensive, and difficult to scale for millions of farms worldwide.

**PLANT-AI** is a deep learning-based plant disease recognition system that identifies diseases from leaf images using image classification techniques. The project uses convolutional neural networks (CNNs) and transfer learning approaches to automatically classify plant diseases and distinguish leaves from their backgrounds.

The developed model can recognize **38 different disease categories across 14 plant species**, helping farmers and researchers achieve faster and more accurate disease detection while reducing unnecessary pesticide usage.

---

# 🍃 Leaf Image Classification

The objective of this project is to build a machine learning model capable of detecting plant diseases from leaf images. The development process consists of the following steps:

## 1. Dataset Collection

The model was trained using the **New Plant Diseases Dataset**, which contains images of healthy and diseased crop leaves.

Dataset source:

- Kaggle: https://www.kaggle.com/vipoooool/new-plant-diseases-dataset

The dataset includes multiple plant species with different disease categories, making it suitable for training a multi-class image classification model.

---

## 2. Model Development

<<<<<<< HEAD
The project uses **PyTorch** for implementing and training deep learning models.

Three different architectures were explored:

### 🔹 Custom CNN Model
A convolutional neural network built using:

- Convolutional layers
- Max pooling layers
- Flatten layers
- Fully connected (linear) layers

### 🔹 VGG16 Transfer Learning
A pretrained VGG16 model was fine-tuned for plant disease classification.

### 🔹 ResNet34 Transfer Learning
A pretrained ResNet34 architecture was adapted and trained for improved feature extraction and classification performance.

---

## 3. Training

The models were trained using different combinations of architectures and hyperparameters to achieve the best classification performance.

The best-performing model achieved:

**✅ Test Accuracy: 98.42%**

---

## 4. Testing

The final model was evaluated on:

- **17,572 test images**
- **38 disease classes**

The trained model successfully predicts diseases from unseen leaf images.

---

# 🤖 Model Capabilities

The final model can identify:

- **38 types of plant diseases**
- Across **14 different plant species**

The complete list of supported plants and diseases can be found in:

[Plant and Disease List](Src)

---

# 🚀 Future Improvements

Future enhancements planned for this project include:

- Implementing **image localization** to identify the exact infected regions of leaves.
- Developing a recommendation system for suitable pesticides and disease control methods.
- Adding intelligent crop management strategies, including:
  - Fungicide recommendations
  - Pesticide application guidance
  - Early disease monitoring

These improvements can help farmers make faster decisions and improve crop productivity.

---

# 📂 Project Structure

=======
>>>>>>> 51d9a54ed539544bd0873f94e46edbc2c33f71f3

PLANT-AI
│
├── Flask
│ └── Flask server and deployment code
│
├── TestImages
│ └── Sample images for testing predictions
│
├── Src
│ └── Source code for training and building models
│
└── Models
└── Pretrained PyTorch models


---

# 🛠️ Technologies Used

<<<<<<< HEAD
- Python
- PyTorch
- Convolutional Neural Networks (CNN)
- Transfer Learning
- VGG16
- ResNet34
- Flask

---

# 📄 License

This project is licensed under the **MIT License**.
=======
<a href="https://www.buymeacoffee.com/soumyajit4419" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-violet.png" alt="Buy Me A Coffee" height= "60px" width= "217px" ></a>
>>>>>>> 51d9a54ed539544bd0873f94e46edbc2c33f71f3
