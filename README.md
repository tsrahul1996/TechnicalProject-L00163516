# NIH-Chest-X-rays-Classification using MobileNet

# Project Overview

This project aims to classify the NIH chest x-ray dataset through the use of a MobileNet architecture. This dataset was gathered by the NIH and contains over 100,000 anonymized chest x-ray images from more than 30,000 patients. The data represents NLP analysis of radiology reports and may include areas of lower confidence in diagnoses. As a simplifying assumption, we assume that based on the size of the dataset, the dataset is accurate in diagnoses.

# Technologies


## MobileNet 

As CNN's gained popularity, researchers aimed to make them faster and lighter. One such CNN, MobileNet, emerged as a particularly effective architecture. MobileNet utilizes depthwise seperable convolutions to greatly reduce the number of parameters while retaining the same depth levels as "normal" CNN's. The resulting performance gains make MobileNet a great choice for computer vision on devices with less power, such as cellphones and embedded cameras. MobileNet V1's architecture is shown below. 


# Data Background

This dataset was gathered by the NIH and contains over 100,000 anonymized chest x-ray images from more than 30,000 patients. The results shown below are taken from Wang et. al.

The image set involves diagnoses that were scraped from radiology reports and is a multi-label classification problem.  The diagram below shows the proportion of images with multi-labels in each of the 8 pathology classes and the labels' co-occurrence statistics.


# References

 - Wang X, Peng Y, Lu L, Lu Z, Bagheri M, Summers RM. ChestX-ray8: Hospital-scale Chest X-ray Database and Benchmarks on Weakly-Supervised Classification and Localization of Common Thorax Diseases. [ChestX-ray8: Hospital-scale Chest X-ray Database and Benchmarks on Weakly-Supervised Classification and Localization of Common Thorax Diseases](docs/Wang_ChestX-ray8_Hospital-Scale_Chest_CVPR_2017_paper.pdf).

 - NIH News release: NIH Clinical Center provides one of the largest publicly available chest x-ray datasets to scientific community.  Original source files and documents: https://nihcc.app.box.com/v/ChestXray-NIHCC/folder/36938765345

 - https://www.kaggle.com/nih-chest-xrays/data
 - Kanan C, Cottrell GW (2012) Color-to-Grayscale: Does the Method Matter in Image Recognition? PLoS ONE 7(1): e29740. https://doi.org/10.1371/journal.pone.0029740
 - Skymind. "A Beginner's Guide to Attention Mechanisms and Memory Networks". https://skymind.ai/wiki/attention-mechanism-memory-network
