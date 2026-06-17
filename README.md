
# 🧬 **Fingerprint Classification Using FastAI + ResNet**

A deep-learning based fingerprint classification system built using **FastAI**, **ResNet**, and **transfer learning**.
This project uses fingerprint images as input and predicts the class/label using a fine-tuned convolutional neural network.

---

## 🚀 **Project Overview**

This project builds a complete end-to-end image classification pipeline:

* Load fingerprint images
* Preprocess & augment images
* Build a deep-learning model using **FastAI’s ResNet architecture**
* Train & fine-tune the model using transfer learning
* Evaluate performance
* Export a `.pkl` model for deployment
* Predict on new fingerprint images

It demonstrates strong skills in **computer vision, transfer learning, image preprocessing, and model deployment**.

---

## 🧠 **Key Features**

* Uses **FastAI DataBlock API** for image loading and transforms
* Applies **image augmentations** for better generalization
* Leverages **pre-trained ResNet** backbone (ResNet34/ResNet50)
* Uses **transfer learning** to train faster and achieve higher accuracy
* Tracks training with accurate metrics
* Saves final trained model as a `.pkl` file
* Provides easy inference on new fingerprint images

---

## 📁 **Project Structure**

```
📂 Fingerprint-Classification
│── 📁 data/                 # Dataset of fingerprint images
│── 📁 models/               # Exported .pkl model
│── 📁 notebooks/            # Training notebooks (Colab / Jupyter)
│── ├── train.ipynb
│── ├── inference.ipynb
│── README.md
```

---

## 🛠️ **Technologies Used**

* **FastAI**
* **PyTorch**
* **ResNet (Transfer Learning)**
* **NumPy / Pandas**
* **Google Colab**
* **Python 3**
* **Matplotlib / Seaborn**

---

## 📊 **Results**

* High accuracy with ResNet transfer learning
* Stable convergence due to FastAI’s one-cycle training
* Model generalizes well on test images

https://colab.research.google.com/drive/1TsERjhGqcUn7R6e7qyojximv6Q1Wug6w?usp=sharing

https://drive.google.com/file/d/1SDd5_EXxibmsNad5w6Se2_bzY_SRn5eP/view?usp=sharing
---

## 🎯 **Use Cases**

* Fingerprint classification
* Biometric research
* Pattern recognition
* Educational purpose (Deep Learning / FastAI demo project)

---

## ✨ **Future Improvements**

* Add more fingerprint classes
* Train on larger public dataset
* Deploy model with FastAPI
* Add real-time mobile app integration
