# DriverDistractionDetection
Driver distraction detection using StateFarm database and Deep Learning Models.

This project performs driver distraction detection by using 6 different deep learning models:

1. Vanilla CNN
2. Optimized CNN with Batch Normalization
3. Optimized CNN with Batch Normalization on Augmented Data
4. VGG-16 Model
5. InceptionNet V# Model
6. ResNet-50 Model

######################### INFORMATION #################################


This repository consists of a driver distraction detection using StateFarm database. The classes used are as follows.

    C0: safe driving
    C1: texting - right
    C2: talking on the phone - right
    C3: texting - left
    C4: talking on the phone - left
    C5: operating the radio
    C6: drinking
    C7: reaching behind
    C8: hair and makeup
    C9: talking to passenger

Database used: StateFarm driver distraction detection.

https://www.kaggle.com/c/state-farm-distracted-driver-detection/data


#################### Technical INFORMATION ##############################

Implemented using: TensorKeras environment
Activate using : source TensorKeras/bin/activate


Environment details:
Python version: 3.8.2
Tensorflow backend : 1.14.0 (with GPU)
Keras : 2.2.4
Open CV : 4.1.0


############################ To Run #####################################

1. To run the cnn models, open the cnn folder and run all the cells in the cnn-model.ipynb file
    
2. To run the vgg-16 models, open the vgg-16 folder and run all the cells in the vgg-model.ipynb file

3. To run the resnet-50 models, open the resnet-50 folder and run all the cells in the resnet-model.ipynb file

4. To run the inception-net-v3 models, open the inceptionnet-V3 folder and run all the cells in the inceptionnet-model.ipynb file

5. The data-EDA.ipynb consists of exploratory data analysis and information about the distribution of the dataset.
