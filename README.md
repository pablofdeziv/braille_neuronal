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

## 🛠️ Technologies

- Python (3.10)
- Google Colab
- TensorFlow / Keras
- NumPy, Matplotlib

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

1. Open the main notebook in Google Colab.
2. Run all cells to:
   - Preprocess the dataset
   - Train or load the saved model
   - Predict digits and display their Braille equivalent
3. You can also run locally:
   ```bash
   pip install tensorflow numpy matplotlib
   python predict_image.py

📌 This project was entirely developed and tested using Google Colab.

## 📝 License

This project is released under the MIT License.
