# AI powered Package Theft Identification (Google Coral Platform) #

## Table of Contents ##

* [Introduction]
* [The Problem]
  * [Analysis of the Problem ]
  * [Package Thefts (Facts)]
* [Solution]
  * [Solution Workflow]
  * [Evaluation of the Proposed Solution]
* [Conclusion]
* [References]
* [Contact Us]


## Introduction ##

Online shopping has reached an all-time high due to the coronavirus pandemic and there is a huge surge in Package Theft ( package left on the door by the delivery personnel ). We have built a Proof of Concept of identifying the Package from the real-time CCTV stream when it arrives/ placed on the door side and intimates the house owner if the Package is taken away. (  __ALARM__ is triggered )


## Problem ##

In this particular demonstration we will focus on the package theft problem in USA. Around 1.7 million packages are stolen or go missing every day in USA, accounting to a lost revenue of $25 million per day or $9 billion per year.


### Analysis of the Problem ###


<p float-"left">
<img src="https://github.com/Karthikkannan-AI/AI-Powered-Package-Theft-Identification-Coral-Platform/blob/main/resources/Package.png?raw=true" width="49%">

<img src="https://github.com/Karthikkannan-AI/AI-Powered-Package-Theft-Identification-Coral-Platform/blob/main/resources/Package%20Theft.png?raw=true" width="50%">
</p>

<img src="https://github.com/Karthikkannan-AI/AI-Powered-Package-Theft-Identification-Coral-Platform/blob/main/resources/Package%20Theft%20Facts.png?raw=true" width="100%"/>


### Package Thefts (Facts) ###

<img src="https://github.com/Karthikkannan-AI/AI-Powered-Package-Theft-Identification-Coral-Platform/blob/main/resources/Package%20Theft%20Ranking.png?raw=true" width="100%">


## Proposed Solution ##

### Solution Workflow ###

<img src="https://github.com/Karthikkannan-AI/AI-Powered-Package-Theft-Identification-Coral-Platform/blob/main/resources/Solution%20Workflow%20.jpg?raw=true" width="100%">

To arrive at the solution, we have to go through 5 major steps


| Step Numbers | Procedures | Definitions |
| :-------------- | :-------------- | :-------------- |
| Step 1   | Data Preparation | Collect thousands of Images of Delivery Boxes ( Different shapes, sizes, and background environments) to mimic the real-world situation. |
| Step 2   | Data Annotation | As we have planned to do object detection, we have to annotate those images with Bounding Boxes. |
| Step 3   | Training | The Images are Trained using Google Coral. |
| Step 4   | Evaluation | The custom Deep Learning Model is Tested and Evaluated. If there are issues with the detection accuracy of delivery packages in specific conditions then we have to retrain the model by taking into consideration those scenarios. |
| Step 5   | Deployment | IP CCTV camera is connected to Coral Dev Board through RTSP. If the CCTV Feed identifies the Delivery package, immediately through SMTP a mail is triggered to the House Owner. If the delivery package is taken away, the prior 20 sec frame is taken and converted in to a video and sent as an email to the House Owner , so that we can know the theft event. |


### Evaluation of the Proposed Solution ###

 __Package Detection Test - 1__



<a href="https://youtu.be/mMvSNhvZ56c" target="_blank"><img src="https://github.com/Karthikkannan-AI/AI-Powered-Package-Theft-Identification-Coral-Platform/blob/main/resources/Package%20Detection%20Video%201.png?raw=true" 
alt="Package AI - Test 1" width="75%"  /></a> 


  __Package Detection Test - 2__



<a href="https://youtu.be/RZKY4oaE7E8" target="_blank"><img src="https://github.com/Karthikkannan-AI/AI-Powered-Package-Theft-Identification-Coral-Platform/blob/main/resources/Package%20Detection%20Video%202.png?raw=true" 
alt="Package AI - Test 2" width="75%" /></a> 


  __Package Detection Test - 3__



<a href="https://youtu.be/Vyaga6PCK7I" target="_blank"><img src="https://github.com/Karthikkannan-AI/AI-Powered-Package-Theft-Identification-Coral-Platform/blob/main/resources/Package%20Detection%20Video%203.png?raw=true" 
alt="Package AI - Test 2" width="75%" /></a> 


  __Package Detection Test - 4__



<a href="https://youtu.be/VnzSjJf439o" target="_blank"><img src="https://github.com/Karthikkannan-AI/AI-Powered-Package-Theft-Identification-Coral-Platform/blob/main/resources/Package%20Detection%20Video%204.png?raw=true" 
alt="Package AI - Test 2" width="75%" /></a> 



## Conclusion ##

* We have built this as a Proof of Concept to showcase how we can built a custom deep learning Model to solve a Package theft problem using computer vision. 
* We have considered only carton boxes of different shapes and size for Package, Further works are required to improve the detection accuracy with various other packages other than carton boxes 


## References ##

1. https://www.security.org/resources/stolen-packages-survey/
2. https://www.cnbc.com/2020/01/10/package-theft-how-amazon-google-others-are-fighting-porch-pirates.html
3. https://www.nytimes.com/2019/12/02/nyregion/online-shopping-package-theft.html


## Contact Us ##

__ETOP TECHNOLOGIES__ is a Software development company. 
1. We do AI Consulting for Digital Transformation.
2. We build software solutions using emerging technologies for start-ups and enterprises. 
3. We can develop AI applications with Computer vision, Deep Learning, and Natural Language processing.

We convert your AI Vision into a reality. Our Services are categorized into 
1. AI Data Preparation/ Data Annotation Services 
2. AI Software Development Services 
3. AI-IOT Development Services

__Visit www.etopdigital.com for more information.__

__Email : karthik@etopdigital.com / sales@etopdigital.com__
          
__Phone : 9944865029__

<img src="https://github.com/Karthikkannan-AI/Package-AI/blob/main/resources/About%20ETOP%20Technologies_Github.png">

The COVID-19 pandemic has profoundly influenced the lives of most people on the planet.

Like every business across the World, we too got impacted and affected by Coronavirus.

We are navigating the business impact of Covid-19 through self-motivation and Innovation.

This work is part of our journey towards Recovery and Reinvention.

#EtopTechnologies #Artificialintelligence #DeepLearning #MachineLearning


<img src="https://github.com/Karthikkannan-AI/AI-Powered-Package-Theft-Identification-Jetson-Platform/blob/main/resources/CoronaPandemic.jpeg?raw=true">
