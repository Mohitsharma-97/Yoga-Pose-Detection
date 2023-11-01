                                                      Yoga-Pose-Detection
The purpose of this project is to explore the use of machine learning for yoga pose classification. 
Given an input image I in which some yoga pose is performed, the objective is to learn a classifier which can detect the pose performed in I.
This task comes under the general human activity recognition problem. 
The yoga pose can be from the following 5 poses:
1. Plank
2. GOddess
3. Warrior2
4. Tree
5. DownDog
----------------------------------------
**Methods:**
----------------------------------------
The main points in solving the problem are as follows:
(a)	Data Augmentation and Preprocessing
(b)	Keypoint extraction using MediaPipe
(c)	Pose Prediction

For pose prediction we used three models, one uses traditional Machine Learning Algorithms, and the other two are based on deep learning architecture.
The Machine Learning Model is combination of PCA and KNN.
The deep learning models are based on CNN and LSTM architecture.
