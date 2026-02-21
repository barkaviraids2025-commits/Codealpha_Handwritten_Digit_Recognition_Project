
🧠 Handwritten Digit Recognition (MNIST)
📌 Overview

This project builds a Convolutional Neural Network (CNN) to recognize handwritten digits (0–9) using the MNIST dataset. The model is implemented with TensorFlow/Keras and achieves high accuracy on unseen test data.

🎯 Objective

Classify handwritten digits

Train and evaluate a CNN model

Demonstrate digit prediction

🛠️ Tech Stack

Python • TensorFlow/Keras • NumPy • Matplotlib

📂 Dataset

MNIST Handwritten Digits

60,000 training images

10,000 testing images

28×28 grayscale
(Automatically loaded via TensorFlow)

🧩 Model

Conv2D → MaxPooling → Conv2D → MaxPooling → Flatten → Dense → Softmax

📊 Performance

Test Accuracy: ~98–99%

▶️ How to Run
git clone https://github.com/barkaviraids2025-commits/Codealpha_Handwritten_Digit_Recognition_Project
cd CodeAlpha_Handwritten_Recognition
pip install -r requirements.txt
python mnist_digit_recognition.py
🔮 Output

Training logs

Test accuracy

Sample digit prediction

Saved model: mnist_model.h5

🚀 Future Improvements

User drawing interface

Alphabet recognition (EMNIST)

Web deployment

🙌 Acknowledgment

Completed as part of the CodeAlpha Machine Learning Internship
