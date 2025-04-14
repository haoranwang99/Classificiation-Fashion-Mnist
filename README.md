# 🧠 Fashion MNIST Image Classification

This project demonstrates how to build and compare deep learning models to classify clothing images using the [Fashion MNIST dataset](https://github.com/zalandoresearch/fashion-mnist).

Two models are implemented and evaluated:
- A basic **Multilayer Perceptron (MLP)**
- A **Convolutional Neural Network (CNN)** for better performance on image data

## 📂 Dataset

Fashion MNIST is a dataset of 60,000 training and 10,000 test grayscale images of size 28x28, each labeled with one of 10 clothing categories (e.g., T-shirt, coat, sneakers).

## 🛠️ Technologies Used

- Python 3
- TensorFlow / Keras
- NumPy
- Matplotlib
- scikit-learn

## 📊 Project Workflow

1. **Data Loading** – Load Fashion MNIST via `keras.datasets`
2. **Data Preprocessing** – Normalize pixel values and reshape for model input
3. **Model 1: MLP** – Fully connected layers with dropout
4. **Model 2: CNN** – Conv2D and MaxPooling layers, followed by dense layers
5. **Training & Validation** – Track accuracy and loss over epochs
6. **Evaluation** – Test set performance and optional confusion matrix

## 🖼️ Sample Output

![accuracy_plot](./images/training_accuracy_plot.png)  
> *Training vs Validation Accuracy for CNN*

## 🚀 How to Run

Make sure you have Python 3.10+ and install required packages:

```bash
pip install tensorflow numpy matplotlib scikit-learn
```

Then run the Jupyter notebook:

```bash
jupyter notebook Fashion_MNIST.ipynb
```

## 📈 Final Performance

| Model | Test Accuracy |
|-------|---------------|
| MLP   | ~88%          |
| CNN   | ~91–93%       |

## 📚 Acknowledgments

- Dataset: [Zalando Research - Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist)
- Deep learning powered by Keras + TensorFlow

---

## 🤝 Let's Connect!

Feel free to fork the project or reach out with feedback!
