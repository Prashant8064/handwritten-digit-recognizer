Handwritten Digit Recognizer
A deep learning project that uses TensorFlow and a Convolutional Neural Network (CNN) to classify handwritten digits (0–9) from the MNIST dataset with high accuracy.

📌 Problem Statement
Manual recognition of handwritten digits is slow and error-prone. This project automates digit recognition using a CNN, achieving ~98% accuracy on test data.

🚀 Features
Loads and preprocesses the MNIST dataset

CNN architecture with convolution, pooling, and dense layers

Trains model using fit() and evaluates performance

Predicts digits from new images

Optional visualization of predictions with Matplotlib

🛠 Tech Stack
Python 3.x

TensorFlow / Keras

Matplotlib (for visualization)

📂 Project Structure
bash
Copy
Edit
handwritten-digit-recognizer/
│
├── digit_recognizer.py     # Main Python script
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
📊 Model Performance
Test Accuracy: ~98%

Dataset: MNIST (60,000 train images, 10,000 test images)

📦 Installation & Usage
Clone the repository

bash
Copy
Edit
git clone https://github.com/<your-username>/handwritten-digit-recognizer.git
cd handwritten-digit-recognizer
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the model

bash
Copy
Edit
python digit_recognizer.py
📜 License
This project is licensed under the MIT License – see the LICENSE file for details
