# Covid-19-Detection-Through-X-Ray-Images-Using-Deep-Learning
The basic aim of this project is to create a model that can predict whether a particular chest x-ray image of person given is infected with covid19 or not.
For training the model 460 covid19 and 460 normal patients chest x-ray images are used and all the images are resized to 256 X 256 pixels.
For augmentation purpose horizontal flip, zoom range, shear range of 20% is used.
The model is trained is simple Sequential CNN model with 4 convolutional layers followed by the artificial neural network.
The model is trained for 10 epochs anf the train test split of 75% for training and 25% for validation.
For testing the model 116 images of both covid19 and normal is used and confusion matrix is made whose results are given below.
The proposed model trained have give the accuracy of 97.84% with precision of 99.11%, sensitivity of 96.55% and f1 score of 97.81%.
Further enhancement can be done by increasing dataset and using pretrained models like resnet50, vgg16, etc.
Do contribute and enjoy.
