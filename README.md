## 🧪 Dataset Information

- **Dataset Name:** Padang Food Image Dataset
- **Source:** [Kaggle - Padang Food Dataset](https://www.kaggle.com/datasets/faldoae/padangfood)
- **Total Classes:** Traditional Indonesian food items (e.g., Nasi Goreng, Sate, Rendang, etc.)
- **Image Format:** JPG
- **Structure:** Labeled folders for each food category

> 📥 You can download the dataset from the link above and place it inside the `/dataset/` folder for training and testing.


# 🍕 Food Image Classifier using CNN

Welcome to the Food Image Classifier project!  
This deep learning model uses a **Convolutional Neural Network (CNN)** to recognize and predict the **name of a food item** from an image.

> ✅ This project was developed as part of my 3rd-year B.Tech (AIDS) coursework at **Sanjivani College of Engineering**, with the goal of applying computer vision to real-world image classification tasks.



## 📌 Project Overview

- 📷 **Input**: Food image  
- 🧠 **Model**: CNN trained on a custom food dataset  
- 🗂️ **Output**: Predicted **name** of the food (e.g., Pizza, Burger, Pasta)

This AI model helps in identifying food items from images using supervised learning and convolutional layers, and it has been trained and tested with a labeled dataset of popular food images.


## 🧠 Technologies & Tools Used

| Tool | Purpose |
|------|---------|
| Python | Core Programming Language |
| TensorFlow / Keras | Deep Learning Framework |
| NumPy & Pandas | Data Handling |
| Matplotlib | Data Visualization |
| OpenCV | Image Processing |
| Jupyter Notebook | Model Training & Visualization |


## 🏗️ CNN Architecture Summary

- `Conv2D` Layers (for feature extraction)
- `MaxPooling2D` (for downsampling)
- `Dropout` (to avoid overfitting)
- `Flatten` & `Dense` (for classification)
- **Activation Functions**: ReLU, Softmax
- **Optimizer**: Adam
- **Loss Function**: Categorical Crossentropy



