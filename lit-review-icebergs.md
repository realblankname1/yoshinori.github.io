---
layout: default
title: Presentation Schedule
description: This Page would be to coordinate lab presentations in an easy to find spot
---

# Notes

# Tools
## Semantic Segmentation
Demo: [DemoSegmenter.ipynb (https://github.com/CSAILVision/semantic-segmentation-pytorch)](https://colab.research.google.com/drive/1I-iGvV8DAGL3iu7JE2ogifmIwMs_I_ow)

The Basis of this research is detecting and tracking icebergs using deeplearning algorithms. The first step is through Semantic Segmentation, the ability to classify each pixel in an image as part of certain type of subject. In the demo there is a standard Semantic Segmenter. 

I have Trained my own Semantic Segmentation Algorithm using a UNET and the VOC dataset. 

The Next step is Iceberg Classification. This step involves using a Semantic Segmentation Algorithm to identify icebergs and track them. There are terrabytes of data to use for this process, however, going through and obtaining the labels in such a way that it would be useable may prove difficult.

## Prediction
A Future step will be predicting the path of the iceberg. This can be done using a seperate algorithm for prediction. This is pretty far in the future, so I will add to this later.

# References
* [Automated detection of rock glaciers using deep learning and object-based image analysis](https://reader.elsevier.com/reader/sd/pii/S003442572030403X?token=02E31A8FC644831D9A6788822A7707E3A28ED6771EE05AFEF4197C7F3067909E8E124AD95A6EED05F3F45DCA0AAE09DB&originRegion=us-east-1&originCreation=20220509183531)
* [Deep Learning for Detecting and Classifying Ocean Objects: Application of YoloV3 for Iceberg–Ship Discrimination](https://www.mdpi.com/2220-9964/9/12/758/htm)
* [Deep Learning for Iceberg Detection in Satellite Images](https://www.diva-portal.org/smash/get/diva2:1532720/FULLTEXT01.pdf)
* [GlacierNet: A Deep-Learning Approach for Debris-Covered Glacier Mapping](https://web.archive.org/web/20201107031829id_/https://ieeexplore.ieee.org/ielx7/6287639/8948470/09081912.pdf)
