### Members : Anuj Rayamajhi, Nisant Uprety
Face Classification with ResNet-18 on LFW Dataset
This project aims to develop a face classification model using the LFW (Labeled Faces in the Wild) dataset. We will train a ResNet-18 model on both uncropped and cropped face images, comparing the performance of these models. The cropping of faces is done using MTCNN (Multi-task Cascaded Convolutional Networks).

Dataset
The dataset is sampled from the LFW face dataset:

Total number of images: 9,164
Total number of classes: 1,680
Project Workflow
Data Preparation

Download and preprocess the LFW dataset.
Crop faces from images using MTCNN.
Model Training

Train a ResNet-18 model on uncropped face images.
Train another ResNet-18 model on cropped face images.
Model Evaluation

Benchmark the performance of both models.
Compare accuracy, precision, recall, and F1-score.
Requirements
Python 3.7+
PyTorch
torchvision
MTCNN
numpy
pandas
scikit-learn
Installation
Clone the repository and install the required packages:

sh
Copy code
git clone https://github.com/yourusername/face-classification-resnet18.git
cd face-classification-resnet18
pip install -r requirements.txt
Data Preparation
Download LFW Dataset
Download the LFW dataset and extract it to the data/lfw directory:

sh
Copy code
mkdir -p data/lfw
cd data/lfw
wget http://vis-www.cs.umass.edu/lfw/lfw.tgz
tar -xzf lfw.tgz
cd ../../
Face Cropping with MTCNN
Use the provided script to crop faces from the LFW dataset using MTCNN.

Model Training
Training on Uncropped Images
Train the ResNet-18 model on uncropped images using the provided script.

Training on Cropped Images
Train the ResNet-18 model on cropped images using the provided script.

Model Evaluation
Evaluate the models on a test set using the provided script. Compare the performance of the models trained on uncropped and cropped images.

Results and Analysis
The performance of both models will be compared using metrics such as accuracy, precision, recall, and F1-score.
Detailed results and analysis will be provided in the final report.
Conclusion
This project demonstrates the impact of face cropping on the performance of a face classification model. The results will help understand the effectiveness of preprocessing steps in enhancing model accuracy.

License
This project is licensed under the MIT License. See the LICENSE file for details.

