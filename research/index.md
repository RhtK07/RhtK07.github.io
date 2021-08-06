---
layout: page
title: Research
tags: [research, publications, rohit, kumar, jhu, graduate, pict]
modified: 2014-08-08T20:53:07.573882-04:00
comments: false
---

My interests broadly lie in the fields of computer vision, machine learning and natural language processing.
I recently got interested in understanding semantics from vision and languague by solving multimodal AI tasks like visual dialog, visual question answering, conversational text generation, etc., using deep learning tools.

### Publications

[Google Scholar Page](https://scholar.google.com/citations?user=4PulMD4AAAAJ&hl=en)

**2021**

1. End-To-End Speech Recognition With Joint Derevberation of Sub-Band Autoregressive Envelopes
**Rohit Kumar**, Anurenjan Purushothaman, Anirudh Sreeram and Sriram Ganapathy
*Under Review*

1. SRIB-LEAP submission to Far-field Multi-Channel Speech Enhancement Challenge for Video Conferencing
R G Prithvi Raj, **Rohit Kumar**, M K Jayesh, Anurenjan Purushothaman, Sriram Ganapathy and M A Basha Shaik
*INTERSPEECH 2021*
[<button type="button" class="btn btn-info">Paper</button>](https://arxiv.org/pdf/2106.12763.pdf)

1. Towards sound based testing of COVID-19 - Summary of the first Diagnostics of COVID-19 using Acoustics (DiCOVA) Challenge
Neeraj Kumar Sharma, Ananya Muguli, Prashant Krishnan, **Rohit Kumar**, Srikanth Raj Chetupalli and Sriram Ganapathy
*Elsevier Computer Speech and Language*
[<button type="button" class="btn btn-info">Paper</button>](https://arxiv.org/pdf/2106.10997.pdf)

1. Multi-modal Point-of-Care Diagnostics for COVID-19 Based On Acoustics and Symptoms
Srikanth Raj Chetupalli, Prashant Krishnan, Neeraj Sharma, Ananya Muguli, **Rohit Kumar**, Viral Nanda, Lancelot Mark Pinto, Prasanta Kumar Ghosh and Sriram Ganapathy
*Under Review*
[<button type="button" class="btn btn-info">Paper</button>](https://arxiv.org/pdf/2106.00639.pdf)

1. DiCOVA Challenge: Dataset, task, and baseline system for COVID-19 diagnosis using acoustics
Ananya Muguli, Lancelot Pinto, Nirmala R., Neeraj Sharma, Prashant Krishnan, Prasanta Kumar Ghosh, **Rohit Kumar**, Shrirama Bhat, Srikanth Raj Chetupalli, Sriram Ganapathy, Shreyas Ramoji, Viral Nanda
*INTERSPEECH 2021*
[<button type="button" class="btn btn-info">Paper</button>](https://arxiv.org/pdf/2103.09148.pdf)

1. Investigating the Feature Selection and Explainability of COVID-19 Diagnostics from Cough Sounds
Flavio Avila, Amir Hossein Poorjam, Deepak Mittal, Charles Dognin, Ananya Muguli, **Rohit Kumar**, Srikanth Raj Chetupalli, Sriram Ganapathy and Maneesh Singh
*INTERSPEECH 2021*

**2020**

1. Unsupervised Neural Mask Estimator for Generalized Eigen-Value Beamforming Based ASR
**Rohit Kumar**, Anirudh Sreeram, Anurenjan Purushothaman and Sriram Ganapathy
*International Conference on Acoustics, Speech, and Signal Processing (ICASSP), 2020*
[<button type="button" class="btn btn-info">Paper</button>](https://arxiv.org/pdf/1911.12617.pdf)


1. Coswara - A Database of Breathing, Cough, and Voice Sounds for COVID-19 Diagnosis
Neeraj Sharma, Prashant Krishnan, **Rohit Kumar**, Shreyas Ramoji, Srikanth Raj Chetupalli, Nirmala R., Prasanta Kumar Ghosh, and Sriram Ganapathy
*INTERSPEECH 2020*
[<button type="button" class="btn btn-info">Paper</button>](https://arxiv.org/pdf/2005.10548.pdf)

1. Deep Learning Based Dereverberation of Temporal Envelopes for Robust Speech Recognition
Anurenjan Purushothaman, Anirudh Sreeram, **Rohit Kumar**, Sriram Ganapathy
*INTERSPEECH 2020*
[<button type="button" class="btn btn-info">Paper</button>](https://arxiv.org/pdf/2008.03339.pdf)

1. LEAP Submission to CHiME-6 ASR Challenge
Anirudh Sreeram, Anurenjan Purushothaman, **Rohit Kumar**, Sriram Ganapathy
*CHIME-6 Challenge*
[<button type="button" class="btn btn-info">Paper</button>](https://arxiv.org/pdf/2005.11258.pdf)

-----

### Other projects

* **Spoken Dialog System with Audio and Text**  
*Topics in Deep Learning (10-807), Fall 2016*  
Instructor: Prof. Ruslan Salakhutdinov  
**Abstract:**  
Growth of technology places a lot of importance in human-machine interaction.
With the advent of deep learning, conversational agents that engage with human through free form natural language have become popular.
However, most of these attempts are purely text-based and ignore audio cues.
Emotional information in human-human conversations, encoded in audio cues such as intonation and pitch, often plays an important role that is ignored the text-based approaches.
In other words, the responses depend on not only *what you say* but also *how you say*.
Thus, we explore generative models that jointly train on audio and text in this work.

* **Stochastic Expectation Maximization for Latent Variable Models**  
*Convex Optimization (10-725), Fall 2015*  
Instructor: Prof. Ryan Tibshirani  
**Abstract:**  
In this project, we want to implement and study a type of stochastic optimization. 
This optimization method based on expectation-maximization will be asynchronous & embarrassingly parallel and thus is useful for inference of latent variable models. 
The motivation for this stochastic optimization problem comes from a want to directly design a inference procedure from a "comptastical" (computational + statistical) perspective capable of leveraging modern computational resources like GPUs or cloud computing offering massive parallelism. 
We also find some interesting connection between stochastic expectation-maximization and stochastic gradient descent strengthening validity of proposed method.  
[<button type="button" class="btn btn-info">Report</button>](/reports/F15-CO-Report.pdf){:target="_blank"}
[<button type="button" class="btn btn-success">Poster</button>](/reports/F15-CO-Poster.pptx)  

* **Non-smooth Stochastic Optimization for MCMC**  
*Probabilistic Graphical Models (10-708), Spring 2015*  
Instructor: Prof. Eric Xing  
**Abstract:**  
How do we sample efficiently from the Bayesian Lasso in a high dimensional problem with a large dataset? Hybrid Monte Carlo (HMC) has grown in popularity because it enables more efficient exploration of the state space in high-dimensional problems.
Also, Stochastic Gradient-HMC has been proposed to enable application of HMC to large datasets. 
However, these methods apply to sampling from smooth energy functions only. We propose two ways of dealing with this: 
(1) SPG-HMC: Stochastic Proximal Gradient-HMC, to enable sampling from non-smooth energy functions without losing the benefits of stochasticity, and 
(2) Smoothing-SG-HMC. 
Further, we analyze its properties theoretically and empirically.  
[<button type="button" class="btn btn-info">Report</button>](/reports/S15-PGM-Report.pdf){:target="_blank"}
[<button type="button" class="btn btn-danger">Code</button>](https://github.com/satwikkottur/StochasticMCMC)  

* **Movie Recommendation based on Collaborative Topic Modeling**  
*Machine Learning (10-701), Fall 2014*  
Instructor: Prof. Geoff Gordon and Prof. Aarti Singh  
**Abstract:**  
Traditional collaborative filtering relies on ratings provided by viewers in the movie-watching community to make recommendations to the user.
In this project, we attempt to combine this approach with probabilistic topic modeling techniques to make recommendations that consist not only of movies that are popular in the community, but also those that are similar in content to movies that the user has enjoyed in the past.  
[<button type="button" class="btn btn-info">Report</button>](/reports/F14-ML-Report.pdf){:target="_blank"}
[<button type="button" class="btn btn-success">Poster</button>](/reports/F14-ML-Poster.pptx)
[<button type="button" class="btn btn-danger">Code</button>](https://github.com/satwikkottur/MovieRecommend)  

* **Detecting Text in Natural Images**  
*Computer Vision (16-720), Fall 2014*  
Instructor: Prof. Martial Hebert  
**Abstract:**  
Intelligent systems often need to read text in their surroundings. 
There are multiple aspects that make this a challenging problem.
For instance, locating and identifying the part of image containing text is in itself difficult. 
We study a recent approach that uses stroke width transform, and analyse the success and failure cases to get a clearer understanding.  
[<button type="button" class="btn btn-success">Poster</button>](/reports/F14-CV-Poster.pptx)
[<button type="button" class="btn btn-danger">Code</button>](https://github.com/satwikkottur/ImageTextDetector)  

<a id="static-vehicle-detection-and-analysis-in-aerial-imagery-using-depth"></a>

* **Static Vehicle Detection and Analysis in Aerial Imagery using Depth**  
*Internship at [IRIS](http://iris.usc.edu/iris.html), University of Southern California, Summer 2013*  
Guide: Prof. Gerard Medioni  
**Abstract:**  
This report proposes an approach to automatically detect static vehicles in an outdoor parking space using depth. 
The relevant 3D information is generated from a Digital Surface Model (DSM), which is a result of a novel and existing technique to solve camera pose estimation and dense reconstruction simultaneously. 
Validation using local 2D features, based on existing methods, is then done to ensure better detection rates. 
Further, performance of the detection system is evaluated by changing the internal parameterization of 3D model generation and the dependence is analyzed.  
[<button type="button" class="btn btn-info">Report</button>](/reports/VehicleDetection-Report.pdf){:target="_blank"}
[<button type="button" class="btn btn-success">Poster</button>](/reports/VehicleDetection-Poster.pptx)
[<button type="button" class="btn btn-warning">Project Page</button>](projects/aerial-vehicle/)  

<a id="human-activity-recognition"></a>  
 
* **Human Activity Recognition**  
*B.Tech project-I, IIT Bombay, Fall 2013*  
Guide: Prof. Subhasis Chaudhuri  
**Abstract:**  
Human activity recognition is gaining importance, not only in the view of security and surveillance but also due to psychological interests in understanding
the behavioral patterns of humans. 
This project is a study on various existing techniques that have been brought together to form a working pipeline to study human activity in social gatherings. 
Humans are first detected with Deformable part models and tracked as a feature point in 2.5D co-ordinate system using Lucas-Kanade algorithm. 
Linear cyclic pursuit model is then employed to predict short-term trajectory and understand behavior.  
[<button type="button" class="btn btn-info">Report</button>](/reports/HumanActivity-Report.pdf){:target="_blank"}
[<button type="button" class="btn btn-success">Poster</button>](/reports/HumanActivity-Poster.pptx)
[<button type="button" class="btn btn-warning">Project Page</button>](projects/human-activity)  

<a id="autonomous-underwater-vehicle-auv-iitb"></a>  

* **Autonomous Underwater Vehicle (AUV-IITB)**  
*AUVSI and ONR''s International Robosub Competition, San Diego, USA*  
*Vision (Spring 2012 - Spring 2013)*  
Guides: Dr. Hemendra Arya and Dr. Leena Vachhani  
**Details:**  
Designing and developing an unmanned autonomous underwater vehicle (AUV) that localizes itself and performs realistic missions based on feedback from visual, inertial, acoustic and depth sensors using thrusters and pneumatic actuators.  
Matsya (sanskrit word for fish) is the AUV from IIT Bombay to participate in the International Robosub competition, San Diego which sees teams of different universities from countries all over the world.  
[<button type="button" class="btn btn-info">Journal (2012)</button>](/reports/IIT_Bombay_Journal_Paper_2012.pdf)
[<button type="button" class="btn btn-info">Journal (2013)</button>](/reports/IIT_Bombay_Journal_Paper_2013.pdf)
[<button type="button" class="btn btn-warning">Project Page</button>](projects/auv-iitb/)  

<a id="parallel-simulation-of-verilog-hdl-designs"></a>  

* **Parallel Simulation of Verilog HDL designs**  
*Internship, IIT Bombay, Summer 2012*  
Guide: Prof. Sachin Patkar  
**Abstract:**  
Digital designs, before synthesis, are simulated on a computer platform to test their efficiency. Maximizing the performance and minimizing the overheads is, therefore, a vital area of research. The main focus of this work is to parallelize the simulation of single clock structural/behavior hardware designs without any time or resource conflict. Thus, resulting in a multi-fold in reduction in execution time. I was awarded **Undergraduate Research Award** ([URA 01](http://www.iitb.ac.in/newacadhome/urop.jsp)) for contribution to research at IIT Bombay.  
[<button type="button" class="btn btn-warning">Project Page</button>](projects/parallel-verilog/)  

-----

You can find my other projects from undergraduate [here](/research/oldprojects).  

[Here](/research/courses/) is a list of all the courses I have taken, both during graduate and undergraduate studies.
