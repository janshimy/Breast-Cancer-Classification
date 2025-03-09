## **BREAST CANCER CLASSIFICATION**
### **Via SuperDataScience Team**

*   Breast cancer is the most common cancer among women worldwide accounting for 25% of all cancer cases and infected two point one million people in 2015.
*   Ealy diagnosis significantly increase the chances of survival. 
*   The key challenge in cancer detection is how to classify tumours into *malignant* or *benign* machine learning techniques can dramatically improve the accuracy of diagnosis.
*   Research indicates that most experienced physicians can diagnose cancer with 79% accuracy. 


**First stage**: Any process which is simply extracting some of the cells out of the tumour

When we say benign that means the tumour is kind of not spreading across the body so the patient is safe somehow if it's malignant that means it's a cancerous.
That means we need to intervene and actually stopping cancer growth. 

---



What we do here in the machine learning aspect. 
* We excute all these images and 
* We wanted to specify if that cancer out of these image is malignant or benign.

So what we do with that we extract out of these images some features when we see features that mean some characteristics out of the image such as 
* radius
* cells
* texture
* perimeter
* area
* smoothness

We feed all these features in to kind of our machine learning model.

**MAIN PART:**  We want to teach the machine how to basically classify images or classify data and tell us if it's malignant or benign.

## **PROBLEM IN MACHINE LEARNING VOCABULARY**

*Input:* 30 feautures 
* Radius
* Texture
* Perimeter
* Area
* Smoothness
* ...

*Target Class:* 2 
* Malignant
* Benign

*How many datasets we have? :* 
* Number of Instances : 569
* Class Distribution: 212 Malignant, 357 Benign

*Data source:*
* [Breast Cancer Wisconsin(Diagnostic)](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)
* [Breast Cancer Detection with Reduced Feature Set](https://www.researchgate.net/publication/271907638_Breast_Cancer_Detection_with_Reduced_Feature_Set)


We're going to say look if you look at these features then indicate that the cancer is let's say zero which is malignant in this case. 

And then if we look at the 30 features may be classified as one which kind of a benign.

So  it's kind of the opiate is binary in a forum indicating zero or one for malignant or benign.

---
**SUPPORT VECTOR MACHINE CLASSIFIER**

Near the max Margin Hyperplane, we don't know whether this cancer is malignant or benign. 

That's why the support vector machine classifier is very unique in this sense. It's simply uses the points or the support vectors that are on the boundary to draw the boundary out to classify the classes.

Support vector machines are really powerful techniques.
Why? Because it's kind of an extreme algorithm.
It just focus on the support of the suppor vectors or the points on the boundary and seperate them somehow.
