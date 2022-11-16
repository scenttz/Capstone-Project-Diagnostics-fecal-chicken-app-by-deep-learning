# Diagnostics Fecal Chicken App By Deep Learning
_“Prevention Is Better Than Cure”_ 
– The Dutch philosopher Desiderius Erasmus. In this project, we aim to develop an application that can help to detect the disease of chickens via chicken fecal by deep learning neural network.

## Contents:
- [Problem Statement](#Problem-Statement)
- [Executive Summary](#Executive-Summary)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)
- [Further Improvements](#Further-Improvements) 
- [Acknowledgements](#Acknowledgements) 

## Problem Statement 
Lately, one of the major transitions in Thailand is related to the agricultural industry which is due to the higher competition in terms of quality and yield. Therefore, smart farming can be used as an opportunity to improve our farm's quality. The use of technology can help to improve farm productivity and increase efficiency through agricultural research and by adopting advanced technologies, including biotechnology, drones, big data, artificial intelligence, and robotics. With the help of these disruptive technologies, new businesses and business models have emerged to help smallholders, who are the majority of Thai farmers, to reduce costs and produce more crops, benefiting the whole economy.[Source](https://www.boi.go.th/upload/content/TIR7_Aw_Smart%20farming_5e5dc88fa8284.pdf) 

Moreover, it is corresponding to the increasing trend of Thailand's chicken meat production which is expected to grow up to 3% in 2023. In addition, after the pandemic, Thailand's chicken market is recovering due to the impact of the supply chain.[Source](https://apps.fas.usda.gov/newgainapi/api/Report/DownloadReportByFileName?fileName=Poultry%20and%20Products%20Annual_Bangkok_Thailand_09-01-2020) The common poultry diseases that affect all farming systems such as Salmonella, Newcastle, and Coccidiosis that effectc of such widespread poultry disease include high mortality rates and failure to compete on the expoert and consumption market with other high producing countries. These challenges are usually found in small to medium scale farms which managed by young people as they don't have much knowledge on how to cope with those situations, especially when the disease get spreader. Therefore, an early detection is a very important method to control the spread of the diseases.[Soure](https://www.frontiersin.org/articles/10.3389/frai.2022.733345/full)

This project focused on **developing the streamlit application which helps to classify the disease of a chicken via an image of a chicken's fecal using through the deep learning neural network.**

## Executive Summary


## Conclusions and Recommendations
Pamameters | CNN_Baseline  | VGG16_Transfer_Leraning  |  VGG16_Fine_Tuning | MobileNetV2_Transfer_Leraning | MobileNetV2_Fine_Tuning 
----- | ----- | ----- | ----- | ----- | ----- |
Loss function training | 0.14 | 0.50 | 0.07 | 0.06 | 0.04 |
Loss function vaildation | 0.45 | 0.54 | 0.29 | 0.32 | 1.43 |
Accuracy score training  | 0.95 | 0.82 | 0.97 | 0.98 | 0.99 |
Accuracy score vaildation  | 0.88 | 0.80 | 0.92 | 0.90 | 0.86 |
F1 score average  | 0.86 | 0.74 | 0.90 | 0.88 | 0.84 |
Size model(MB)  | 24.11 | 56.23 | 110.26 | 9.13 | 23.46 |
Number parameters   | 2,102,564 | 14,716,740 | 14,716,740 | 2,263,108 | 2,263,108 |
Input image size  | (128,128,3) | (224,224,3) | (224,224,3) | (128,128,3) | (128,128,3) |

## Further Improvements

## Acknowledgements
 - [Machine Learning Dataset for Poultry Diseases Diagnostics - PCR annotated](https://doi.org/10.5281/zenodo.5801834)
 - [Machine Learning Dataset for Poultry Diseases Diagnostics](https://doi.org/10.5281/zenodo.4628934)
 - [Fast and Flexible Image Augmentations](
https://www.mdpi.com/2078-2489/11/2/125)
 - [TensorFlow API](https://lengyi.medium.com/tensorflow-api-custom-object-detection-2-5cdabf8f5e35)
 - [Transfer Learning Image Classification](https://theaisummer.com/cnn-architectures/)
 - [Analysis of deep neural networks](https://culurciello.medium.com/analysis-of-deep-neural-networks-dcf398e71aae)
 - [Deploy your deep learning-based image classification model with Streamlit](https://analyticsindiamag.com/deploy-your-deep-learning-based-image-classification-model-with-streamlit/)
