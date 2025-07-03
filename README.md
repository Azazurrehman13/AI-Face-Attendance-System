🧠 Face Recognition Dataset (Manual Collection)
This repository contains a manually created facial image dataset intended for training and evaluating face recognition models using deep learning techniques such as FaceNet, VGG-Face, and DeepFace.

📂 Dataset Structure
The dataset is organized into folders, where each folder represents one individual/class:


my_face_dataset/
├── person1/
│   ├── img1.jpg
│   ├── img2.jpg
│   └── ...
├── person2/
│   ├── img1.jpg
│   └── ...
...
📸 Image Collection
Images were collected manually using phone camera/webcam.

Each person has 20–100 face images under different lighting, poses, and expressions.

All images are resized to 160×160 pixels for deep learning compatibility.

🧰 Applications
This dataset can be used for:

Face recognition model training

Feature extraction (using FaceNet or similar)

Face classification tasks (e.g., with SVM, KNN)

Real-time attendance systems

✅ Features
Easy-to-use, pre-organized format

Suitable for both training and testing

Compatible with TensorFlow, Keras, and PyTorch pipelines

🛡️ Disclaimer
This dataset is intended for educational and research purposes only. All individuals in the dataset have given consent to use their images for this project.
