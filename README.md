# Traffic-sign-detecction
Trafiic sign detection using yolo v8

This project focuses on detecting and classifying traffic signs using a custom-trained YOLOv8 model for detection and a separate CNN model for classification. The detection component performs well, accurately identifying traffic signs in real time.

For classification, I initially used the German Traffic Sign Recognition Benchmark (GTSRB) dataset. However, due to class imbalance, certain traffic signs were not recognized correctly. To address this, I removed classes with fewer images, reducing the dataset from 42 classes to 7. After retraining, the classification model now achieves improved real-time performance, accurately predicting the most relevant traffic signs.

dataset link : https://www.kaggle.com/datasets/sivabal/traffic-sign-board/data
dataset link : https://sid.erda.dk/public/archives/daaeac0d7ce1152aea9b61d9f1e19370/published-archive.html

