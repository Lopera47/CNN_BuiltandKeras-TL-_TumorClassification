General information:
1. This is a personal project done by Luis Lopera.
2. The main aim is to improve my Deep Learnig skills aplying a Convolutional Neural Network for image classification.
3. In this project I used a dataset from kaggle based on brain tumor radiography images.
(link: https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset).
4. For the Transfer Learning part. I used the EfficientNetB0 (link:https://keras.io/api/applications/efficientnet/#efficientnetb0-function). Because, it was trained with million of images including brain tumor radiography (link: https://ieeexplore.ieee.org/document/9823526).
5. All the necessary requirements are on requirements.txt.

- Research question:
The Artificial Intelligence approach has been developed in many areas including Healthcare. So, in this case the idea is to apply and Convolutional Neural Network to classify the images of Brain tumor into 4 categories. And on the other hand, There is Transfer Learning, as an option to help a get fast results. So, the questions here are:

1. Is it possible to classify the type of Brain Tumor based on different kind of labeled images?
2. Is Transfer Learning a better option to get better results quickly and efficiently than training your own-model.

License:
This is a open resource code, if someone wants to use it, go ahead.

Contents:
1. in: files used as a inputs (see info_images.txt).
2. out: final files as part of the outputs including the best classifier (CNN).
3. EDA.ipynb: file with the exploratory data analysys.
4. CNN_Classifier.ipynb: building, runnig, tuning and downlading a classifying Convolutional Network.