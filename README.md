# Early-Tomato-Leaf-Disease-Prediction
This repository provides an implementation of a deep learning-based approach for early detection and classification of tomato leaf diseases. Using models like CNN, ResNet50, VGG16, and AlexNet, the study aims to assist farmers in improving crop yields and ensuring sustainable development.

🚀 Project Overview
Tomato plants are prone to various diseases, often resulting in reduced yield and quality. Early disease detection can mitigate these issues significantly. This project classifies tomato leaf images as healthy or diseased using a dataset sourced from Kaggle and agricultural fields in Andhra Pradesh.

Key Highlights
Dataset of 8834 images (healthy & diseased leaves).
Image preprocessing (resizing, batching, train-validation split).
Implementation of CNN, ResNet50, VGG16, and AlexNet models.
Achieved 94% accuracy using the CNN model with data augmentation.

The dataset can be taken from kaggle or from fields just make the folders and add the links.

📂 Repository Structure
├── dataset/  
│   ├── healthy/  
│   ├── diseased/  
├── models/  
│   ├── cnn_model.ipby  
│   ├── resnet50_model.ipby  
│   ├── vgg16_model.ipby  
│   ├── alexnet_model.ipby  
├── preprocessing/  
│   └── preprocess_images.ipby  
├── results/  
│   ├── results_before_augmentation.csv  
│   ├── results_after_augmentation.csv  
├── README.md  
└── requirements.txt  

📊 Results
Model	   Training Accuracy	 Validation Accuracy
CNN	         94%	                93%
ResNet50	   68%	                73%
VGG16	       24%	                24%
AlexNet	     93%	                41%

🛠️ Installation
Clone the repository:
git clone https://github.com/<username>/Early-Tomato-Leaf-Disease-Prediction.git  
cd Early-Tomato-Leaf-Disease-Prediction  

Install dependencies:
pip install -r requirements.txt 

Prepare the dataset:
Place your images in the dataset/ directory, categorized into healthy/ and diseased/ subfolders.

Run the code.

🔮 Future Scope
Use advanced models like GoogLeNet, YOLO, and LSTM for better predictions.
Expand the dataset with diverse real-time images.
Enhance preprocessing and augmentation techniques.

🤝 Contributing
Contributions are welcome! Feel free to fork the repo, make changes, and submit a pull request.

🙌 Acknowledgments
Dataset: Kaggle
Agricultural fields in Andhra Pradesh for real-time images.
Feel free to contact us with suggestions or issues! 🌱







