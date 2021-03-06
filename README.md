
# FACE-MASK-DETECTION
# In this tutorial, you will learn how to train a COVID-19 face mask detector with OpenCV, Keras/TensorFlow, and Deep Learning.

Readers really enjoyed learning from the timely, practical application of that tutorial, so today we are going to look at another COVID-related application of computer vision, this one on detecting face masks with OpenCV and Keras/TensorFlow.

In this tutorial, we’ll discuss our two-phase COVID-19 face mask detector, detailing how our computer vision/deep learning pipeline will be implemented.

From there, we’ll review the dataset we’ll be using to train our custom face mask detector.

I’ll then show you how to implement a Python script to train a face mask detector on our dataset using Keras and TensorFlow.

We’ll use this Python script to train a face mask detector and review the results.

# Given the trained COVID-19 face mask detector, we’ll proceed to implement two more additional Python scripts used to:

1.Detect COVID-19 face masks in images

2.Detect face masks in real-time video streams
We’ll wrap up the post by looking at the results of applying our face mask detector.

I’ll also provide some additional suggestions for further improvement.

![face_mask_detection_phases](https://user-images.githubusercontent.com/87760317/132211152-d697c1fe-b076-4bc7-b07d-47d7df19b997.png)

In order to train a custom face mask detector, we need to break our project into two distinct phases, each with its own respective sub-steps (as shown by Figure 1 above):


# Training:
Here we’ll focus on loading our face mask detection dataset from disk, training a model (using Keras/TensorFlow) on this dataset, and then serializing the face mask detector to disk


# Deployment: 
Once the face mask detector is trained, we can then move on to loading the mask detector, performing face detection, and then classifying each face as with_mask or without_mask



We’ll review each of these phases and associated subsets in detail in the remainder of this tutorial, but in the meantime, let’s take a look at the dataset we’ll be using to train our COVID-19 face mask detector.

![face_mask_detection_dataset](https://user-images.githubusercontent.com/87760317/132211549-d128f4ce-409a-43f6-b38e-3a914d5993c4.jpg)

connect me on :)
# Linkedln:www.linkedin.com/in/rathodrohan222 


