# Braille Digit Translator – MLP-based🔠

Image-based digit recognition system with Braille translation, developed using a Multilayer Perceptron neural network. Part of the course *Softcomputing* (3rd year of Engineering degree).

## 🚀 Features

- Preprocessing pipeline:
  - Grayscale conversion
  - Binarization
  - Normalization
  - Resizing to 28×28 px
- Digit classification using MLP (Multilayer Perceptron)
- Mapping of predicted digits to Braille characters
- Performance evaluation with confusion matrix and per-class metrics

## 🧠 Model Architecture

- Input: 28×28 grayscale images flattened into 784-length vectors
- Hidden layer: 128 neurons with ReLU activation
- Output layer: 10 neurons (digits 0–9) with softmax activation
- Optimizer: Adam
- Loss function: Sparse Categorical Crossentropy

## 📊 Results

- Accuracy: 95.19%
- F1-scores range: 93.87% to 97.26%
- Most confusion between similar digits (e.g., 1 & 7, 5 & 6)

## ⚙️ How to Run

1. Install dependencies (`tensorflow`, `numpy`, `matplotlib`)
2. Run training (if needed) or load saved model
3. Use `predict_image.py` to classify new digit images and print Braille output

## 📝 License

This project is released under the MIT License.
