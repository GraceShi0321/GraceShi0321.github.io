---
layout: post
title: Reflection Blog Post
---

This is my reflection blog post for PIC16B project MasksOn.

<h1>§1. What Achieved in the project</h1>
In this project, our group was able to create a face mask classifier for differetiating images of people wearing masks and images of people not wearing masks.   
We built a machine learning model with around 94% accuracy for both the validation and testing data set. 

<h1>§2. Aspects That I'm Especially Proud Of</h1>
1. In the earlier stages of our projct, our data set for masked faces are mostly images of synthetic masked faces. However, we were able to find enough real images at the end and built our model without using synthetic ones.               
2. Throughout the process of completeing our project, we solved problems such as overfitting for our model and also increased accuracy by incorporating preprocess layer and also data augmentation layers.  
3. Though we are not able to implenet the originally planed openCV part, we added a section to our project by analyzing whether the model we developed is biased. 
 
<h1>§3. Things For Further Improvements</h1>
1. The current validation accuracy is around 94% for our model, there is still room for improvement.
2. We were only able to build a mask classifier but not a detector.
3. bias 

<h1>§4. Thinking Back About Project Proposal</h1>
In our proposal, we set the goal to first build a classifier then try to use openCV to build a detector so can detect people wearing masks in real time. 
However, because we haven't learnt about openCV systematically, even though we made some effort trying to use openCV, several errors were encountered when we try to build the detector.  
Thus, in the end, we were not able to implement the face mask detector, but only the face mask classifier.
In conclusion, we finished the part of building a face mask classifer, but didn't successfully build a face mask detector. 

<h1>§5. Things Learned From Project</h1>
1. One major thing that I learned from the project is the collaboration between team members by utilizing GitHub repository. With no need to send code files through email, Github makes the collaboration on coding for a team so much efficient. I really enjoyed this. 
2. I also learned more about data preprocessing through completeing the project. As the images for our data set are colored images with different sizes, we made some effort to process the data such as resizing all images to the same size. 
3. Through the poject, I learned about how data augmentation could be really useful when there are not enough images.
4. Bias could exist in a model even if the developers are not intended. For our model, because we have less data on black people, the accuracy we tested for black people is lower comparing to white and asian. 

<h1>§6. Benefiting The Future</h1>
One aspect of the project that I believe will benefit my future greatly is the practice of collaborating with team members through GitHub.
As both programing and team work will be essential elements of my future career, my experience from the project will benefit me greatly as I am already quite familiar with the process of coding with a team.
Another thing that will also be important to me is the process of building machine learning models. I gained a lot of proactice about building machine learning models and making modifications to try to improve accuracy or solve problems such as overfitting. I believe this experience will be every beneficial to my future career as I believe machine learning models will be needed. 

