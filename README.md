# ADAS
Detection of Pedestrians and Vehicles to aid Advanced  Driver-Assistance Systems

Advanced Driver Assistance Systems (ADAS) were developed in order to reduce the number of accidents that take place due to human error. These systems include different types of technologies that can be used to assist drivers in driving and parking functions. The main objective of these systems is to increase car and road safety by making use of automated technology like cameras and different kinds of sensors.

Please download the datasets and all the required dependencies and install all libraries before running the files.

For the Pedestrian detection the datasets used are-
1. Penn-Fudan Dataset- https://www.cis.upenn.edu/~jshi/ped_html/
2. Human detection dataset on Kaggle found on- https://www.kaggle.com/datasets/constantinwerner/human-detection-dataset

For Vehicle detection please download the KITTI dataset- http://www.cvlibs.net/datasets/kitti/

In this project different types of augmentation have been implemented from scratch in order to aid in training the model. Each of these augmentations will help in increasing the accuracy of the model and account for factors like lossy and unclear data. Dropout has also been employed in order to prevent overfitting.
