# Auto-WCEBleedGen-Challenge

The Auto-WCEBleedGen challenge is focused on developing, testing, and evaluating artificial intelligence (AI) models for automatic detection and classification of bleeding and non-bleeding frames extracted from Wireless Capsule Endoscopy (WCE) videos. The challenge aims to promote the development of vendor-independent, interpretable, and generalized AI models.

## Approach

For this challenge, we will be using YOLOv5 to train on the dataset and get the prediction and validate it. Our approach is to develop a robust and interpretable AI model that can aid in reducing the burden on gastroenterologists by providing computer-aided classification between bleeding and non-bleeding frames and further detection of bleeding regions in those frames

## Preprocessing 

The training dataset consists of 2618 bleeding and non-bleeding WCE frames collected from multiple internet resources and datasets with a vast variety and types of gastrointestinal (GI) bleeding throughout the GI tract along with medically validated binary masks and bounding boxes in three formats (txt, XML, and YOLO txt). The test dataset is an independently collected WCE data containing bleeding and non-bleeding frames of more than 30 patients suffering from acute, chronic, and occult GI bleeding referred at Department of Gastroenterology and HNU, All India Institute of Medical Sciences, New Delhi, India.

## Methodology

Our methodology involves training YOLOv5 on the training dataset using the provided binary masks and bounding boxes. We will then validate our model on the test dataset to determine its accuracy in detecting and classifying bleeding and non-bleeding frames. The goal is to develop an AI model that can accurately detect bleeding regions in WCE videos, reducing the burden on gastroenterologists and improving patient outcomes.

## Metrics Table 

![results](https://github.com/ATHdevs/Auto-WCEBleedGen-Challenge/assets/147138099/51ce9ed5-076e-48a4-9231-36d74105ca40)


## 10 best Images of validation dataset showing the prediction and classification

##  5 best images selected from testing datasets 1 and 2 separately showing its classification and detection (bounding box with confidence level)

##  Interpretability plot of any 5 best images selected from testing datasets 1 and 2 separately
