
# 🥔 Potato Disease Detection using Deep Learning

This project implements a Convolutional Neural Network (CNN) to detect and classify potato leaf diseases into three categories: **Early Blight**, **Late Blight**, and **Healthy**. The model is built using TensorFlow and Keras, with support for model training, evaluation, API serving, and mobile deployment.

---

## 🧠 Model Overview

- **Input**: 256x256 RGB images  
- **Architecture**: CNN with Conv2D → MaxPooling2D → Flatten → Dense layers  
- **Output**: Softmax layer for classifying 3 categories  
- **Frameworks**: TensorFlow, Keras  

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Munia2319/Potato-Disease-Detection.git
cd Potato-Disease-Detection
````

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Train the Model

Open the Jupyter Notebook in the `training/` folder:

```bash
jupyter notebook training/potato-disease-classification-model.ipynb
```

### 4. Run Predictions

Test with images from the `test_images_from_internet/` folder.

---

## 📱 Deployment Options

* ✅ TensorFlow Lite conversion for mobile apps
* ✅ REST API with Flask (`api/` directory)
* ✅ Simple frontend for uploading and predicting images
* ✅ Mobile interface prototype for real-time detection

---

## 📊 Results

The trained CNN model achieves strong accuracy on the PlantVillage dataset and performs well on unseen leaf images. It is lightweight enough for mobile use and can assist in early crop disease detection for farmers.

---

## 📚 Acknowledgments

* **Dataset**: [PlantVillage Dataset on Kaggle](https://www.kaggle.com/datasets/arjuntejaswi/plant-village)
* **Tools**: TensorFlow, Keras, OpenCV, Flask

---





