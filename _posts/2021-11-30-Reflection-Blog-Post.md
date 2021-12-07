---
layout: post
title: Reflection Blog Post
---

This is my reflection blog post for PIC16B project MasksOn.

<h1>§1. What Achieved in the project</h1>
In this project, our group was able to create a face mask classifier for differetiating images of people wearing masks and images of people not wearing masks.   
We built a machine learning model with around 97% accuracy for both the validation and testing data set. 

<h1>§2. The Concern for the project</h1>
For our project, there is one major concern which is the fact that there are people who who are not able to wear masks for medical reasons. 
As our model is intended to be used to spot people who should wear the masks but didn't, we need to think about how our model will encounter people who are not able to wear masks. 
We consider our model has the potential to be used for control access to buildings or events to spot people who are not wearing masks and ask them to put masks on, I  believe there are ways we could factor in medical exemptions when using the model.
For instance, if the model is utilized for control access to buildings or events, the model will first distinguish whether the person is wearing mask or not. 
If the person wears the mask, then he/she would be allowed to enter the builing or events. 
However, if the model determines the person is not wearing the mask, then on the screen for detection, a message asking whether the person has medical exemptions for not wearing masks will be displaced.
If the person chooses yes, then he/she will be allowed to enter because the person belongs to the group of people not be able to wear masks due to medical issues.
However, if the person chooses no, then the system will issue a reminder to ask the person to put the mask on for safety concerns. 

<h1>§3. Aspects That I'm Especially Proud Of</h1>
1. In the earlier stages of our projct, our data set for masked faces are mostly images of synthetic masked faces. However, we were able to find enough real images at the end and built our model without using synthetic ones.               
2. Throughout the process of completeing our project, we solved problems such as overfitting for our model and also increased accuracy by incorporating preprocess layer and also data augmentation layers.  
3. After some analysis, we found our initial model was biased for people of different races. However, we were able to incorporate transfer learning and create a new model that successfully solved the biase and also increased accuracy at the same time.  
 
<h1>§4. Things For Further Improvements</h1>
1. The current validation accuracy is around 97% for our model, there is still room for improvement.
2. We were only able to build a mask classifier but not a detector while our initial final goal is to build a face mask detector. Thus, one direction for further improvement would be to figure out how to implement a face mask detector. 
3. As our initial purpose is to develop a face mask detector; however, there are certain groups that cannot wear masks because of health or religious reasons. Thus, one director for further improvement is to try to address the needs of people cannot wear masks.

<h1>§5. Thinking Back About Project Proposal</h1>
In our proposal, we set the goal to first build a classifier then try to use openCV to build a detector so can detect people wearing masks in real time. 
However, because we haven't learnt about openCV systematically, even though we made some effort trying to use openCV, several errors were encountered when we try to build the detector.  
Thus, in the end, we were not able to implement the face mask detector, but only the face mask classifier.
In conclusion, we finished the part of building a face mask classifer, but didn't successfully build a face mask detector. 

<h1>§6. Things Learned From Project</h1>
1. One major thing that I learned from the project is the collaboration between team members by utilizing GitHub repository. With no need to send code files through email, Github makes the collaboration on coding for a team so much efficient. I really enjoyed this. 
2. I also learned more about data preprocessing through completeing the project. As the images for our data set are colored images with different sizes, we made some effort to process the data such as resizing all images to the same size. 
3. Through the poject, I learned about how data augmentation could be really useful when there are not enough images.
4. Bias could exist in a model even if the developers are not intended. For our model, because we have less data on black people, the accuracy we tested for black people is lower comparing to white and asian. However, we were then later to solve this problem by incorporating transfer learning into our model. 

<h1>§7. Benefiting The Future</h1>
One aspect of the project that I believe will benefit my future greatly is the practice of collaborating with team members through GitHub.
As both programing and team work will be essential elements of my future career, my experience from the project will benefit me greatly as I am already quite familiar with the process of coding with a team.
Another thing that will also be important to me is the process of building machine learning models. I gained a lot of proactice about building machine learning models and making modifications to try to improve accuracy or solve problems such as overfitting. I believe this experience will be every beneficial to my future career as I believe machine learning models will be needed. 

