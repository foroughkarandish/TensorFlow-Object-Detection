# TensorFlow-Object-Detection

This repository is based on my master thesis in Computer Vision.

Summary and Conclusion of my thesis:

In this study, we investigated the performance of the common object detection models obtained from the TensorFlow object detection model zoo when used to detect PPEs. 
Different object detection models were trained and tested on the custom dataset. A diverse range of the object datasets from the construction sites were gathered and 
labelled. The models were trained, and their performance was evaluated using accuracy metrics by reviewing the above-mentioned model systems in object detection. 
We conduct tests on Faster RCNN, RFCN and SSD architectures combined with MobileNet and ResNet101 feature extractors to find the best model for object detection. 
The annotation and preprocessing part is another crucial part of the object detection process and must be done carefully.

To wrap up this study, we can say that the Faster RCNN architecture with the ResNet101 feature extractor has better results with regards to AP, mAP, and considering 
its high computation cost. The SSD MobileNet compared to the Faster RCNN ResNet101 is faster, but less accurate. The RFCN model has good mAP but less accurate than 
Faster RCNN. The SSD MobileNet model could be a suitable model to be used on mobile devices but the performance may not satisfying in terms of accuracy of detection.

You can find my master thesis and related paper in this repository.
