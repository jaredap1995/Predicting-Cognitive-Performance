# Predicting-Cognitive-Performance
Exploratory Data Analysis and some tensorflow models for the prediction of cognitive performance. 

This project is my first foray into the application of deep learning to physiological data to attempt to predict cognitive performance. The data for the project can be found in the open source dataset "A Wearable Exam Stress Dataset for Predicting Cognitive Performance in Real-World Settings" accessible through physionet: https://physionet.org/content/wearable-exam-stress/1.0.0/.

The aim of the project is largely exploratory and attempts to assess if physiological signals derived from wearable sensors can be effectively used to predict an individual's exam score. Despite largely failing in predicting performance, some interesting findings include the ability of wearable based sensors to classify individuals during a stressful event, and a transfer learning approach that could, after being trained on a subset of the subjects, could effectively distinguish between two different unseen subjects solely based on their physiological inputs.
