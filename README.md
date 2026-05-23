# emotion-detection-in-social-media
A Deep Learning and Computer Vision project for detecting human emotions from images and videos using Transfer Learning with ResNet18, PyTorch, and OpenCV.
# Features
Emotion detection from uploaded images
Emotion detection from uploaded videos
Face detection using OpenCV Haar Cascade
Transfer Learning with ResNet18
GPU/CUDA support
Model saving and loading using .pth
Confusion Matrix and Accuracy/Loss Visualization
Separate notebooks for training, image prediction, and video prediction
# Technologies & Libraries Used
Python
PyTorch
Torchvision
OpenCV
ResNet18
NumPy
Matplotlib
Seaborn
Scikit-learn
PIL
Jupyter Notebook

# Project Workflow
Dataset preprocessing and augmentation
Transfer learning using pretrained ResNet18
Model training and validation
Emotion prediction from images
Face-based emotion prediction from videos
Visualization and evaluation

# Project Structure
RESEARCH PROJ/

├── train/
├── test/
│
├── checkpoints/
│   ├── best_model.pth
│   ├── final_model.pth
│   ├── confusion_matrix.png
│   └── training_history.png
│
├── outputs/
│
├── train_model.ipynb
├── predict_image.ipynb
├── predict_video.ipynb
│
├── sample1.mp4
├── sample2.mp4
└── sample3.mp4
