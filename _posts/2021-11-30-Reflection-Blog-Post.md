---
layout: post
title: Reflection Blog Post
---

This is my reflection blog post for PIC16B project MasksOn.

<h1>§1. What Achieved in the project</h1>
In this project, our group was able to create a face mask classifier for differetiating images of people wearing masks and images of people not wearing masks.   
We built a convolutional neural network model with around 90% accuracy on our testing data set. 

<h1>§2. Aspects That I'm Especially Proud Of</h1>
1. I am proud that in addition to simulated masked face images, our group was able to find data of real masked faces. Our data set of masked faces then is a combination of the two types of data, making our model more convincing.                 
2. During earlier stages, the accuracy of our model is promising, but we can see the porblem of overfitting noticeable for the mode. After some experiments and modifications, we are able to solve the problem of overfitting in the end. 
3. I am also proud that the model reached over 90% accuracy on the testing data set. We believe this result is quite promising. 
 
<h1>§3. Things For Further Improvements</h1>
1. The current accuracy is around 90% for our model, there is still room for improvement on accuracy for the model.
2. We were only able to build a mask classifier but not a detector.
3. Currently, the data with masks contain both real masked face images and also simulated masked face images. In future, we can incorporate a even larger data with all images being real masked faces to further improve the validity of our model.

<h1>§4. Thinking Back About Project Proposal</h1>
In our proposal, we set the goal to first build a classifier then try to use openCV to build a detector so can detect people wearing masks in real time. 
However, because we haven't learnt about openCV systematically, even though we made some effort trying to use openCV, several errors were encountered when we try to build the detector.  
Thus, in the end, we were not able to implement the face mask detector, but only the face mask classifier.
In conclusion, we finished the part of building a face mask classifer, but didn't successfully build a face mask detector. 

<h1>§5. Three Things Learned From Project</h1>
1. One major thing that I learned from the project is the collaboration between team members by utilizing GitHub repository. With no need to send code files through email, Github makes the collaboration on coding for a team so much efficient. I really enjoyed this. 
2. I also learned more about data preprocessing through completeing the project. As the images for our data set are colored images with different sizes, we made some effort to process the data so that we converted all images into gray scale, resized all images to the same size. In addition, in order to speed up our training process, we converted the RGB values to 0-1 scale.
3. Through the poject, I learned that convulution neural network is really good at making image classification as our model has reached around 90% accuracy on the testing data set. 

<h1>§6. Benefiting The Future</h1>
One aspect of the project that I believe will benefit my future greatly is the practice of collaborating with team members through GitHub.
As both programing and team work will be essential elements of my future career, my experience from the project will benefit me greatly as I am already quite familiar with the process of coding with a team.
Another thing that will also be important to me is the process of building machine learning models. I gained a lot of proactice about building machine learning models and making modifications to try to improve accuracy or solve problems such as overfitting. I believe this experience will be every beneficial to my future career as I believe model learning models will also be used. 

