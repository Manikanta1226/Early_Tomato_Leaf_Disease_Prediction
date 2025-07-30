# Early_Tomato_Leaf_Disease_Prediction

A deep learning-based project for early detection and classification of tomato leaf diseases. This project utilizes CNN, ResNet50, VGG16, and AlexNet to assist farmers in boosting crop yield and promoting sustainable agriculture.

🚀 Project Overview
Tomato crops are vulnerable to a range of diseases, impacting both quality and yield. Early diagnosis is essential for timely treatment and productivity. This project classifies tomato leaf images into healthy or diseased categories using deep learning techniques.

🧠 Key Features
📸 Dataset: 8,834 images (healthy & diseased leaves), sourced from Kaggle and real farms in Andhra Pradesh.

🛠️ Preprocessing: Image resizing, batching, and splitting into train/validation sets.

🤖 Models Implemented:

Custom CNN

ResNet50

VGG16

AlexNet

🎯 Best Accuracy: 94% training accuracy using a CNN with data augmentation.

📂 Repository Structure ├── dataset/
│ ├── healthy/
│ ├── diseased/
├── models/
│ ├── cnn_model.ipby
│ ├── resnet50_model.ipby
│ ├── vgg16_model.ipby
│ ├── alexnet_model.ipby
├── preprocessing/
│ └── preprocess_images.ipby
├── results/
│ ├── results_before_augmentation.csv
│ ├── results_after_augmentation.csv
├── README.md
└── requirements.txt


📊 Model Performance
Model	Training Accuracy	Validation Accuracy
CNN	94%	93%
ResNet50	68%	73%
VGG16	24%	24%
AlexNet	93%	41%

⚙️ Setup & Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/<your-username>/Early-Tomato-Leaf-Disease-Prediction.git
cd Early-Tomato-Leaf-Disease-Prediction
Install the dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Prepare the dataset:
Add images into the dataset/ directory:

Copy
Edit
dataset/
├── healthy/
└── diseased/
Run the notebooks:
Choose any model from the models/ folder and run in Jupyter Notebook or any IDE of your choice.

🔮 Future Enhancements
Implement GoogLeNet, YOLO, and LSTM models.

Expand dataset with more diverse real-time images.

Improve preprocessing and augmentation pipelines.

Build a web-based prediction tool for field deployment.

🤝 Contributions
Contributions are welcome!
Feel free to fork the repository, improve the code, and submit a pull request.

🙏 Acknowledgments
Dataset: Kaggle

Field Data: Agricultural farms in Andhra Pradesh, India

📬 Contact
If you have feedback, feature requests, or want to collaborate, feel free to reach out.
Together, let’s support farmers with AI-powered solutions. 🌿

