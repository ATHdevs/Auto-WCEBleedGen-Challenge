# Auto-WCEBleedGen-Challenge

The Auto-WCEBleedGen challenge is focused on developing, testing, and evaluating artificial intelligence (AI) models for automatic detection and classification of bleeding and non-bleeding frames extracted from Wireless Capsule Endoscopy (WCE) videos. The challenge aims to promote the development of vendor-independent, interpretable, and generalized AI models.

## Approach

For this challenge, we will be using YOLOv5 to train on the dataset and get the prediction and validate it. Our approach is to develop a robust and interpretable AI model that can aid in reducing the burden on gastroenterologists by providing computer-aided classification between bleeding and non-bleeding frames and further detection of bleeding regions in those frames

## Preprocessing 

The training dataset consists of 2618 bleeding and non-bleeding WCE frames collected from multiple internet resources and datasets with a vast variety and types of gastrointestinal (GI) bleeding throughout the GI tract along with medically validated binary masks and bounding boxes in three formats (txt, XML, and YOLO txt). The test dataset is an independently collected WCE data containing bleeding and non-bleeding frames of more than 30 patients suffering from acute, chronic, and occult GI bleeding referred at Department of Gastroenterology and HNU, All India Institute of Medical Sciences, New Delhi, India.

## Methodology

Our methodology involves training YOLOv5 on the training dataset using the provided binary masks and bounding boxes. We will then validate our model on the test dataset to determine its accuracy in detecting and classifying bleeding and non-bleeding frames. The goal is to develop an AI model that can accurately detect bleeding regions in WCE videos, reducing the burden on gastroenterologists and improving patient outcomes.

## Metrics 

![results](https://github.com/ATHdevs/Auto-WCEBleedGen-Challenge/assets/147138099/51ce9ed5-076e-48a4-9231-36d74105ca40)


##  5 best images selected from testing datasets 1 and 2 separately showing its classification and detection (bounding box with confidence level)

![A0000](https://github.com/ATHdevs/Auto-WCEBleedGen-Challenge/assets/147138099/130f246b-1391-48fe-b084-2c7da6d2750d)
![A0001](https://github.com/ATHdevs/Auto-WCEBleedGen-Challenge/assets/147138099/21b90de9-9a91-4854-9ccb-e831981d8e0f)
![A0002](https://github.com/ATHdevs/Auto-WCEBleedGen-Challenge/assets/147138099/80815b91-6152-4d71-9172-8f87ae1be22a)
![A0003](https://github.com/ATHdevs/Auto-WCEBleedGen-Challenge/assets/147138099/fa7afb2e-0f30-45d6-86a0-3e2db5770113)
![A0004](https://github.com/ATHdevs/Auto-WCEBleedGen-Challenge/assets/147138099/fde9af64-5070-42f1-aac7-5a131553a306)
![A0050](https://github.com/ATHdevs/Auto-WCEBleedGen-Challenge/assets/147138099/c1db35c3-11a1-459b-8adf-9d4d5ab1eb09)
![A0051](https://github.com/ATHdevs/Auto-WCEBleedGen-Challenge/assets/147138099/8a17c342-4817-42ee-a27d-96448c39dddb)
![A0052](https://github.com/ATHdevs/Auto-WCEBleedGen-Challenge/assets/147138099/705b4d0f-6a34-4afb-a2c8-b536a5b43f97)
![A0053](https://github.com/ATHdevs/Auto-WCEBleedGen-Challenge/assets/147138099/2ce22e11-0beb-47ca-bce5-949516693fee)
![A0054](https://github.com/ATHdevs/Auto-WCEBleedGen-Challenge/assets/147138099/8aa1d845-d621-402a-8c54-c0212c46f7d2)
