🧠 Handwritten Digit Recognition using CNN (MNIST)
A Convolutional Neural Network (CNN) based deep learning project that accurately recognizes handwritten digits (0–9).
The model is trained on the MNIST dataset and is capable of predicting custom handwritten digits drawn by the user ✍️📸.

🚀 Project Highlights   
🔥 Built a CNN from scratch using TensorFlow & Keras  
📊 Achieves ~98–99% accuracy on test data  
✍️ Supports real handwritten digit prediction  
🧠 Strong focus on image preprocessing for real-world inputs  
💾 Model saving & loading implemented  

🛠️ Tech Stack  
Python  
TensorFlow / Keras  
NumPy  
OpenCV  
Matplotlib  

📂 Project Structure  
.  
├── mnist_cnn_full.py  
├── mnist_cnn.h5  
├── digit4.png  
└── README.md  

📊 Dataset  
MNIST Handwritten Digits Dataset  
60,000 training images  
10,000 testing images  
Image size: 28×28 grayscale  

🧠 CNN Architecture  
Conv2D (32 filters, 3×3) + ReLU  
MaxPooling2D (2×2)  
Conv2D (64 filters, 3×3) + ReLU  
MaxPooling2D (2×2)  
Flatten  
Dense (128 neurons, ReLU)  
Dense (10 neurons, Softmax)  

🧪 Image Preprocessing Pipeline  
To handle real handwritten images:  
Resize to larger resolution  
Gaussian blur to reduce noise  
Adaptive thresholding  
Contour detection & cropping  
Resize to 28×28  
Normalization (0–1)  

📈 Results  
Test Accuracy: ~98–99%  
Reliable predictions on clean handwritten inputs  
Demonstrates the importance of preprocessing in CNNs  

🏆 What I Learned  
End-to-end CNN workflow  
Importance of normalization & preprocessing  
Real-world challenges beyond dataset accuracy  
Debugging deep learning models effectively  
