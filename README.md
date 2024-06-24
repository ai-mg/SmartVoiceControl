
**SmartVoiceControl Speech Command Detection System**

### Repository Description
This repository contains the code and documentation for the SmartVoiceControl speech command detection system, developed as part of the course Machine Learning and Pattern Classification-2024 project at JKU Linz. The system is designed to recognize specific speech commands in German for controlling various household devices like TVs, heating, lights, and more, using smart devices such as phones, watches, or tablets. 

### Project Overview
The SmartVoiceControl system aims to provide an accurate and efficient solution for recognizing speech commands in domestic environments. The project was carried out in four main phases:

1. **Data Collection**: Recording a diverse set of spoken keywords and everyday scenes to train and evaluate machine learning models.
2. **Data Exploration**: Analyzing audio features to identify useful features for the classification phase.
3. **Classification**: Training various classifiers, including Support Vector Machines (SVM), Decision Trees, Random Forests, and Convolutional Neural Networks (CNN), to distinguish between keywords and unrelated sounds.
4. **Challenge**: Applying and evaluating the trained classifiers on real-world scenarios provided by SmartVoiceControl, optimizing for a cost matrix that penalizes false positives and false negatives.

### Key Features
- **Keyword Detection**: The system detects keywords like "Fernseher", "Heizung", "Licht", etc., and actions "an" (on) and "aus" (off), forming commands such as "Licht an" or "Radio aus".
- **Post-Processing**: Implemented methods for temporal smoothing and contextual correction to enhance the accuracy of keyword recognition.
- **Hyperparameter Tuning**: Extensive tuning of hyperparameters for SVM, Random Forest, and CNN models to achieve optimal performance.
- **Energy-Based Onset Detection**: Leveraging energy features to accurately detect the start of spoken words and improve recognition accuracy.

### Repository Contents
- **Data**: Scripts and documentation for data collection and preprocessing.
- **Models**: Implementation of various classifiers with detailed training and evaluation scripts.
- **Evaluation**: Methods for testing the classifiers on provided datasets and calculating performance metrics.
- **Documentation**: Comprehensive documentation detailing the project phases, methods, and results (to be uploaded soon).
