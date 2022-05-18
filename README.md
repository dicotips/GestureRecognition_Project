# GestureRecognition_Project

**Student:**  Jheser Guzman

## Introduction 

This analysis is based on a home electronics company which manufactures state of the art smart televisions. It has a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help them control the TV without using a remote.

The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:

* **Thumbs up:**  Increase the volume
* **Thumbs down:** Decrease the volume
* **Left swipe:** 'Jump' backwards 10 seconds
* **Right swipe:** 'Jump' forward 10 seconds  
* **Stop:** Pause the movie
 
In this programming assignment I built a 3D-Convs and CNN-RNN Stack model to learn and classify the gesture detected in the images.

This repository contains the following file required by the assignment:

* Jupyter Notebook file with the Data Preparation and Model Building to detect Gestures.

## Understanding the Dataset

The training data consists of a few hundred videos categorised into one of the five classes. Each video (typically 2-3 seconds long) is divided into a sequence of 30 frames(images). These videos have been recorded by various people performing one of the five gestures in front of a webcam - similar to what the smart TV will use.

## Methods Used

* Python
* Pandas
* Numpy
* matplotlib
* TensorFlow

## Download and Setup

This project needs Jupyter Notebook with TensorFlow libraries.

* For more details about the instalation in Anaconda, go to:  https://docs.anaconda.com/anaconda/install/index.html

### How to Run

You can download the source code cloning this repository using Git:

1. Open your favorite Terminal app (Unix, Linux or Macos), such as Terminal, Command, Console, iTerm2, so on.

2. Clone the repository

```
git clone https://github.com/dicotips/GestureRecognition_Project.git
```

3. Open the ** *.ipynb** notebook file in Anaconda.

```
jupyter notebook Jheser_Guzman_CNN.ipynb
```

## Goals of this Project

In this project, you will build a model to recognise 5 hand gestures. The starter code has been shared with you above. Before you start working on the mode, let's see the suggestions Snehansu has to finish the project successfully.

You need to accomplish the following in the project:

* **Generator:**  The generator should be able to take a batch of videos as input without any error. Steps like cropping, resizing and normalization should be performed successfully.

* **Model:** Develop a model that is able to train without any errors which will be judged on the total number of parameters (as the inference(prediction) time should be less) and the accuracy achieved. As suggested by Snehansu, start training on a small amount of data and then proceed further.

* **Write up:** This should contain the detailed procedure followed in choosing the final model. The write up should start with the reason for choosing the base model, then highlight the reasons and metrics taken into consideration to modify and experiment to arrive at the final model. 

## Final Conclusion

TBD
### Future Word

TBD