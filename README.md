# Fashion-Classification-using-CNN

# 📖 1. Overview
This project builds a Convolutional Neural Network (CNN) model to classify fashion items from the Fashion-MNIST dataset.

The goal is to explore deep learning techniques for image classification and understand how CNNs extract visual features from raw pixel data.

## ⚠️ Limitations

- Model struggles with visually similar classes (e.g., Shirt vs T-shirt)
- No data augmentation applied
- Limited model depth


# 📊 2. Dataset
- Dataset: Fashion-MNIST
- Total samples: 70,000 images
- Training: 60,000
- Testing: 10,000
- Image size: 28x28 grayscale
- Classes: 10 (T-shirt, Trouser, Dress, Sneaker, etc.)

# 🧠 3. Model Architecture

The CNN model consists of:
- Convolutional layers (feature extraction)
- MaxPooling layers (downsampling)
- Fully connected layers (classification)
- Dropout (reduce overfitting)

# ⚙️ 4. Pipeline

1. Data loading
2. Data preprocessing (normalization)
3. Model building (CNN)
4. Training
5. Evaluation

# 📈 5. Results

- Test Accuracy: 91.63% (evaluated on test set)
- Evaluation metrics:
  - Precision, Recall, F1-score
  - Confusion Matrix

## Observations
- Some classes show lower recall due to visual similarity between categories
- Model performs well overall but struggles with similar clothing types

# 🛠️ 6. Tech Stack

- Python
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib, Seaborn

# 🚀 7. How to Run

1. Clone repo:
```bash
git clone https://github.com/HungTrn/Fashion-Classification-using-CNN.git
cd Fashion-Classification-using-CNN
```
2. Install dependencies:
```pip install -r requirements.txt```
3. Run notebook:
```jupyter notebook```
4. Open:
```Fashion_Class_Classification_Using_CNN.ipynb```


