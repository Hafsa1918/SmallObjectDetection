# SmallObjectDetection

This repository helps in development and training of YOLOv3 network for real-time detection of small objects such as traffic signs.

# License
This repository is licensed under MIT license. This work is adaption from [AntonMu/TrainYourOwnYOLO](https://github.com/AntonMu/TrainYourOwnYOLO), which was inspired from [qqwweee/keras-yolo3](https://github.com/qqwweee/keras-yolo3)

# Author
[Hafsa Amanullah] - 🌐 [Github](https://github.com/Hafsa1918) - 🌐 [LinkedIn Profile](https://www.linkedin.com/in/hafsa-amanullah)

# Collaborators
[Prof. Dr. Min Young Kim] - 🌐 [Google scholar](https://scholar.google.com.pk/citations?user=Xhawz8EAAAAJ&hl=en)

[Dr. Yawar Rehman] - 🌐 [Github](https://github.com/YawarGuguma) - 🌐 [LinkedIn Profile](https://www.linkedin.com/in/yawar-rehman-820118b/)

# Steps

You may use this code for small traffic sign detection by following these simple steps.

1- Estimate anchors using anchors.mat file

2- Copy test and train images in Data/Source_images/Test_images and Data/Source_images/Training_images respectively

3- Use [Train_YOLO.py](https://github.com/Hafsa1918/SmallObjectDetection/blob/main/Training/Train_YOLO.py) to train your network. 

4- Use [Detector.py](https://github.com/Hafsa1918/SmallObjectDetection/blob/main/Inference/Detector.py) to test the trained network with test images.

The remaining codes will be uploaded soon

# Test results of the proposed algorithm on German Traffic Sign Dataset Benchmark
![amanu8](https://github.com/ha007-aman/SmallObjectDetection/assets/73087518/480464da-9626-47aa-b4b3-7fa2e479ae8b)

Traffic sign detection in GTSDB dataset (a) traffic sign detection with size variation (b) small traffic sign detection (c) a larger traffic sign recognition (d) small traffic sign detection

# Test results of the proposed algorithm on Swedish Traffic Sign Dataset 
![amanu9](https://github.com/ha007-aman/SmallObjectDetection/assets/73087518/66cc4035-8c93-49fc-b995-a302b03383d7)

Traffic sign detection in STS dataset (a-c) small-sized traffic sign detection (d) a large-sized traffic sign detection

# Our work on the small traffic sign detection

Please cite the following if this code/work is helpful to you

1. Y. Rehman, H. Amanullah, M. A. Shirazi and M. Y. Kim, "Small Traffic Sign Detection in Big Images: Searching Needle in a Hay," in IEEE Access, vol. 10, pp. 18667-18680, 2022. [link](https://doi.org/10.1109/ACCESS.2022.3150882)
2. Rehman, Y.; Amanullah, H.; Saqib Bhatti, D.M.; Toor, W.T.; Ahmad, M.; Mazzara, M. Detection of Small Size Traffic Signs Using Regressive Anchor Box Selection and DBL Layer Tweaking in YOLOv3. Appl. Sci. 2021, 11, 11555. [link](https://doi.org/10.3390/app112311555)
