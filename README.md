# 👗 Fashion Image Classification Using Deep Learning

A Deep Learning project using **TensorFlow/Keras** and the **Fashion-MNIST dataset** to classify fashion product images into 10 different categories.

## 📌 Project Overview

This project demonstrates how Deep Learning can be used to automatically classify fashion product images.

**Input:** Fashion product image
**Output:** Predicted product category

The model is trained using the Fashion-MNIST dataset and learns to identify different types of fashion products.

## 🎯 Objectives

* Build a basic Deep Learning image classification model.
* Understand how neural networks process images.
* Train a model using the Fashion-MNIST dataset.
* Evaluate model performance.
* Predict categories for unseen images.
* Understand the business application of image classification.

## 🗂️ Dataset

The project uses the **Fashion-MNIST** dataset available through TensorFlow/Keras.

* 60,000 training images
* 10,000 testing images
* Image size: 28 × 28 pixels
* 10 different product categories

### Categories

| Label | Category    |
| ----: | ----------- |
|     0 | T-shirt/Top |
|     1 | Trouser     |
|     2 | Pullover    |
|     3 | Dress       |
|     4 | Coat        |
|     5 | Sandal      |
|     6 | Shirt       |
|     7 | Sneaker     |
|     8 | Bag         |
|     9 | Ankle Boot  |

## 🧠 Model Architecture

```text
Fashion Image (28 × 28)
        ↓
      Flatten
        ↓
   Dense Layer
   64 Neurons
        ↓
       ReLU
        ↓
   Output Layer
   10 Neurons
        ↓
     Softmax
        ↓
Predicted Category
```

### Model Details

* **Framework:** TensorFlow / Keras
* **Hidden Layer:** Dense layer with 64 neurons
* **Activation:** ReLU
* **Output Layer:** 10 neurons
* **Output Activation:** Softmax
* **Optimizer:** Adam
* **Loss Function:** Sparse Categorical Crossentropy
* **Epochs:** 3
* **Validation Split:** 10%

## 📊 Model Performance

The recorded run achieved a **test accuracy of 84.83%**.

> Accuracy may vary slightly between different training runs.

## 🔍 Example Prediction

The model was tested on an unseen image and successfully predicted:

```text
Predicted Product: Ankle Boot
Actual Product: Ankle Boot
```

Different test images can be selected by changing the image number in the notebook.

## 💼 Business Application

This project demonstrates a potential AI application for **fashion e-commerce**.

Instead of manually categorizing every product image, an AI system can assist employees by automatically suggesting product categories.

```text
Product Image
      ↓
Deep Learning Model
      ↓
Predicted Category
      ↓
Employee Review
      ↓
Product Listing
```

### Benefits

* Faster product categorization
* Reduced repetitive manual work
* More consistent categorization
* Improved product organization
* Better scalability for large product catalogs

## ⚠️ Limitations

The model can make incorrect predictions. Therefore, accuracy should not be the only consideration when deploying an AI system in a real business environment.

Human review may still be required for important or uncertain classifications.

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Google Colab
* Fashion-MNIST

## 🚀 How to Run

### Google Colab

1. Open the Jupyter Notebook in Google Colab.
2. Run the cells from top to bottom.
3. The Fashion-MNIST dataset will be loaded through TensorFlow/Keras.
4. Train the model.
5. Evaluate the model accuracy.
6. Test the model with different images.

### Local Setup

Install the required libraries:

```bash
pip install tensorflow numpy matplotlib
```

Then open the notebook using Jupyter:

```bash
jupyter notebook
```

## 📁 Project Structure

```text
fashion-image-classification-deep-learning/
│
├── Deep_Learning_Fashion_Image_Classification_BBA.ipynb
└── README.md
```

## 📚 Learning Outcomes

This project demonstrates the following Deep Learning concepts:

* Image classification
* Artificial Neural Networks
* Input, hidden and output layers
* Flattening image data
* ReLU activation
* Softmax activation
* Model training
* Validation
* Model evaluation
* Prediction on unseen data
* AI applications in business

## 🔮 Future Improvements

The project can be further improved by:

* Using a Convolutional Neural Network (CNN)
* Increasing the number of training epochs
* Experimenting with different architectures
* Adding a confusion matrix
* Adding more evaluation metrics
* Cr
