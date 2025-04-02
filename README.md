Emotion Detection Using CNN (FER-2013 Dataset)

📌 Project Overview

This project implements an emotion detection system using deep learning on the FER-2013 dataset. The model classifies facial expressions into seven emotion categories and is deployed for real-time emotion detection using Gradio and OpenCV.

🛠️ Tech Stack

Python

TensorFlow & Keras

OpenCV

Gradio

CNN (VGG16, ResNet50v2)

Machine Learning & Deep Learning

🎯 Key Features

Class Imbalance Handling: Applied image augmentation and class weighting to improve model robustness.

Advanced CNN Architectures: Built and iterated on custom CNN models including VGG16 and ResNet50v2 to optimize performance.

High Classification Accuracy: Achieved 66% accuracy on emotion recognition, with detailed precision, recall, and F1-scores across 7 emotion labels.

Real-Time Emotion Detection: Integrated OpenCV & Gradio for dynamic emotion prediction in live video streams.

🚀 Model Training & Optimization

Preprocessed FER-2013 dataset (grayscale, resizing, normalization).

Addressed class imbalance using data augmentation (rotation, zooming, flipping).

Fine-tuned CNN models (VGG16 & ResNet50v2) to improve classification.

Evaluated performance using confusion matrix, precision, recall, and F1-score.

📌 Deployment

Deployed the model using Gradio, enabling a user-friendly web interface for emotion prediction.

Real-time emotion recognition using OpenCV for video stream input.

📂 Project Structure

├── dataset/                 # FER-2013 dataset
├── models/                  # Saved models (VGG16, ResNet50v2)
├── src/
│   ├── preprocess.py        # Data preprocessing
│   ├── train.py             # Model training
│   ├── evaluate.py          # Model evaluation
│   ├── app.py               # Gradio-based web app
│   ├── realtime.py          # Real-time emotion detection with OpenCV
├── requirements.txt         # Required Python packages
├── README.md                # Project documentation

📊 Results

Accuracy: 66%

Loss: Optimized with categorical cross-entropy

Evaluation Metrics: Precision, Recall, and F1-score for 7 emotion classes

📦 Installation & Usage

🔹 Clone the Repository

git clone https://github.com/your-username/emotion-detection.git
cd emotion-detection

🔹 Install Dependencies

pip install -r requirements.txt

🔹 Train the Model

python src/train.py

🔹 Run Real-Time Emotion Detection

python src/realtime.py

🔹 Launch Web App

python src/app.py

📜 License

This project is licensed under the MIT License.

✉️ Contact

For any queries, reach out via LinkedIn or email your.email@example.com.
