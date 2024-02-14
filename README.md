## Melanoma-Detection-Assignment - Skin Cancer Detection Using CNN

## Table of Contents
* [General Info](#general-information)
* [Disease Landscape Summary](#disease-landscape-summary)
* [Problem Statement](#problem-statement)
* [Objectives](#Objectives)
* [Algorithms Used](#algorithms-used)
* [Dataset Details](#dataset-details)
* [Conclusion(Inferences)](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)


## General Information

Disease Landscape Summary

> Cancer manifests in over 200 diverse forms, with melanoma standing out as the most lethal variant within skin cancers. Diagnosis of melanoma typically initiates with clinical screening, progresses through dermoscopic analysis, and culminates in histopathological examination. Early detection significantly enhances the curability of melanoma skin cancer. Initial diagnosis involves a visual inspection of the affected skin area. Dermatologists capture dermatoscopic images of skin lesions using high-speed cameras, achieving diagnostic accuracies ranging from 65% to 80% without supplementary technical aids. Through subsequent expert scrutiny and analysis of these images, the overall predictive accuracy of melanoma diagnosis elevates to between 75% and 84%. The objective of the project is to develop an automated classification system leveraging image processing techniques for the categorization of skin cancer based on images of skin lesions.


### Problem Statement
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

### Objective
 The overarching goal is to support the efforts to reduce the death caused by skin cancer. The primary motivation that drives the project is to use the advanced image classification technology for the well-being of the people. Computer vision has made good progress in machine learning and deep learning that are scalable across domains.

### Dataset Details

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:
- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion
- Conclusion

## Algorithms Used

 - Convolutional Neural Network (CNN)

## Conclusion(Inferences)
 - The training accuracy and validation accuracy are almost same. This is a sign of good fit.
 - The training loss and validation loss are almost same. This is a sign of good fit.
 - Accuracy on training data has increased by using Augmentor library.
 - The Model can be further improved by tuning the hyperparameter.


## Technologies Used
- Python - 3.10.11
- pandas - 2.0.2
- numpy - 1.24.3
- keras - 3.0.4
- Tensorflow 2.2.0 
- matplotlib - 3.7.1
- augmentor - 2.0.1

## Acknowledgements

- https://colab.google/

- Melanoma Skin Cancer from https://www.cancer.org/cancer/melanoma-skin-cancer/about/what-is-melanoma.html

- Introduction to CNN from https://www.analyticsvidhya.com/blog/2021/05/convolutional-neural-networks-cnn/

- Image classification using CNN from https://www.analyticsvidhya.com/blog/2020/02/learn-image-classification-cnn-convolutional-neural-networks-3-datasets/

- Efficient way to build CNN architecture from https://towardsdatascience.com/a-guide-to-an-efficient-way-to-build-neural-network-architectures-part-ii-hyper-parameter-42efca01e5d7

## Contact

Created by [@geek-bhuvnesh] feel free to contact me!
