# Facial Emotion Recognition

Facial Emotion Recognition on FER2013 Dataset. 

![emotions](https://miro.medium.com/max/2000/1*cic1zMaNEcVgGKRXpsUbGA.png)
## Getting Started

All of the code you will run in this two week program will be in the format of Jupyter Notebooks.

### What is Machine Learning

Machine learning is the science of getting computers to act without being explicitly programmed.
### Supervised vs Unsupervised Machine Learning

 - In a supervised learning model, the algorithm learns on a labeled dataset, providing an answer key that 
the algorithm can use to evaluate its accuracy on training data. Classification and regression are examples of 
supervised learning. (we will get to that later!) 

 - An unsupervised model, in contrast, provides 
unlabeled data that the algorithm tries to make sense of by extracting features and patterns on its own.

### Classification

In machine learning, classification refers to a predictive modeling problem where a class label is 
predicted for a given example of input data. For example given a handwritten character, classify it as one of the known 
characters.

#### Multi-Class Classification

Multi-class classification refers to those classification tasks that have more than two class labels. For example plant 
species classification. In this project you will complete a multi-class classification model. 

### Neural Network

Neural networks (NN) or artificial neural networks are computing systems inspired by the biological neural networks that constitute animal brains. They are a means of doing machine learning, in which a computer learns to perform some task by analyzing training examples. Usually, the examples have been hand-labeled in advance. An object recognition system, for instance, might be fed thousands of labeled images of cars, houses, coffee cups, and so on, and it would find visual patterns in the images that consistently correlate with particular labels.

### Facial Emotion Recognition

In this project we would like to recognize emotions of the given image into 6 categories 'Angry', 'Fear', 'Happy', 
'Sad', 'Surprise', 'Neutral' using both classification and neural networks.

#### Beginners (Level-1) - Mandatory

#### Data
The commonly used dataset for this image classification is [FER2013](https://www.kaggle.com/deadskull7/fer2013) 
/ Face Expression
Recognition which prepared by Pierre-Luc Carrier and Aaron Courville. The dataset contains 35,887 grayscale images of faces with 48*48 pixels. 
There are 7 categories: Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral.
In this dataset images contain emotion labels (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral)

Run each step in the `Visualization.ipynb` file and complete `TODO` parts in the notebook to understand dataset.

#### Training and Test Data
As we said before, the model learns on a labeled dataset. Training data is used for the learning process. 
Test data is independent of the training data, used for assessing how good the model is.

##### Classification
Run each step in the `Classification.ipynb` file and complete `TODO` parts in the notebook. 
##### Neural Network
Run each step in the `NeuralNetwork.ipynb` file and complete `TODO` parts in the notebook. 

#### Advanced (Level-2)- Optional

Complete Beginners (Level-1)
##### Real Time Application
Multiple face detection and emotion ecognition on live stream data.
Run each step in the `Real-Time-Application.py` file and complete `TODO` parts.

### Final Thoughts on Facial Emotion Classification

1. Are the final results promising regarding emotions?

2. What about less exaggerated images?

    ![](https://www.nature.com/scitable/content/ne0000/ne0000/ne0000/ne0000/4592603/timroth.jpg)  
  
3. What about other categories of emotions?

To answer these questions it is important to review the research on how the emotions are expressed 
naturally. A recent study by Lisa Feldman Barrett, a professor of psychology at Northeastern University concluded that 
emotions are expressed in a huge variety of ways, which makes it hard to reliably infer how someone feels from a simple 
set of facial movements.

As a result, AI can detect a scowl, but that’s not the same thing as detecting anger. Scowls are not the expression
of anger; they’re an expression of anger — one among many. That means that more than 70 percent of the time, 
people do not scowl when they’re angry. And on top of that, they scowl often when they’re not angry. 

####Facial Action Coding System - FACS
Using FACS human coders can manually code nearly any anatomically possible facial expression, deconstructing it into
the specific action units (AU) and their temporal segments that produced the expression.

   ![](https://i.pinimg.com/originals/d7/0b/8a/d70b8aa3f9074bf21ed469d0ba6f4e27.png)

It is often more accurate to express facial expression in terms of action units instead of emotions.   
   