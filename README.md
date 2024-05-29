### Creating a Face classification model based on small number of data per class
Dataset is sampled from LFW face dataset.

Total number of images : 9164
Total number of class  : 1680

Goal is to train ResNet-18 for classification on the data of face containing images at first and benchmark this model against same model but trained with cropped face data created from the same dataset.
MTCNN is used for face Cropping.
