# Deepfake-detection-using-Deep-Learning.
Give a Star⭐ to repo and Don't forget to Buy Me A Coffee
Deepfake detection using Deep Learning (ResNext and LSTM)
Give a Star⭐ to repo and Don't forget to Buy Me A Coffee
Latest Update
We have dockerised the Django Application now you can spin up a container within seconds without worring about dependencies
1. Introduction
This projects aims in detection of video deepfakes using deep learning techniques like ResNext and LSTM. We have achived deepfake detection by using transfer learning where the pretrained ResNext CNN is used to obtain a feature vector, further the LSTM layer is trained using the features. For more details follow the documentaion.

You can also watch this Youtube video to get a better intuition about the project. You can watch this playList for step by step installation.

You can read more about the project on Medium 

2. Directory Structure
For ease of understanding the project is structured in below format

Deepfake_detection_using_deep_learning
    |
    |--- Django Application
    |--- Model Creation
    |--- Documentaion
Django Application
This directory consists of the django made application of our work. Where a user can upload the video and submit it to the model for prediction. The trained model performs the prediction and the result is displayed on the screen.
Model Creation
This directory consists of the step by step process of creating and training a deepfake detection model using our approach.
Documentation
This directory consists of all the documentation done during the project
3. System Architecture


4. Demo
You can watch the youtube video for demo


5. Our Results
Model Name	No of videos	No of Frames	Accuracy
model_84_acc_10_frames_final_data.pt	6000	10	84.21461
model_87_acc_20_frames_final_data.pt	6000	20	87.79160
model_89_acc_40_frames_final_data.pt	6000	40	89.34681
model_90_acc_60_frames_final_data.pt	6000	60	90.59097
model_91_acc_80_frames_final_data.pt	6000	80	91.49818
model_93_acc_100_frames_final_data.pt	6000	100	93.58794
6. Contributors
Abhijit Jadhav
Abhijit Jadhav
📆	Vishwesh Thonte
Vishwesh Thonte
🚧
6.1 Offline Contributors
Jay Patel
Hitendra Patil
Abhishek Patange
7. License
License: GPL v3

8. We welcome Open Source Contribution.
Below are the some changes that can be applied to the project. New Ideas will be appreciated.
 Deploying the applications in free cloud
 Creating open source API for detection
 Batch processing of entire video instead of processing first 'x' frames.
 Optimizing the code for faster execution.
Completed
 Dockerizing the app
 Enabling working of project on Non Cuda Computers. i.e on normal or AMD GPUs
9. Dont forget to Star⭐ this repo 😉 and Buy Me A Coffee
