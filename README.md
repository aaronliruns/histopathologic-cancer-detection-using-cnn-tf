
## Histopathologic Cancer Detection with CNN (tf)


This project focuses on creating an algorithm to identify metastatic cancer in small image patches taken from larger digital pathology scans. In this dataset, we are provided with a large number of small pathology images to classify. Files are named with an image id. The train_labels.csv file provides the ground truth for the images in the train folder. We need to predicting the labels for the images in the test folder. A positive label indicates that the center 32x32px region of a patch contains at least one pixel of tumor tissue. Tumor tissue in the outer region of the patch does not influence the label. This outer region is provided to enable fully-convolutional models that do not use zero-padding, to ensure consistent behavior when applied to a whole-slide image.

In this project, we will explore the data, create two CNN models, fit the models into data, and finally compare their performance and select the model.



Please find Kaggle submission at - [](https://www.kaggle.com/code/chli3841/histopathologic-cancer-detection-with-cnn-tf) 