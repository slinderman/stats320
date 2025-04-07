# Syllabus

**Welcome to STATS320!**

_This course is cross-listed as STATS220, NBIO220 and CS339N. They are all the same. Enroll in the version that is best for your degree requirements._

**Instructor:** Scott Linderman <br>
**TAs:** Noah Cowan and Amber Hu<br>
Spring Quarter, 2024-25 <br>
Stanford University

## Course Description
With modern high-density electrodes and optical imaging techniques, neuroscientists routinely measure the activity of hundreds, if not thousands, of cells simultaneously.  Coupled with high-resolution behavioral measurements, these datasets offer unprecedented opportunities to learn how neural circuits function.  This course will study statistical machine learning methods for analysing such datasets, including: spike sorting and calcium deconvolution techniques for extracting relevant signals from raw data; markerless tracking methods for estimating animal pose in behavioral videos; state space models for analysis of high-dimensional neural and behavioral time-series; point process models of neural spike trains; and deep learning methods for neural encoding and decoding. We will develop the theory behind these models and algorithms and then apply them to real datasets in the in-class coding labs and final project.

## Prerequisites
You should be comfortable with basic probability (STATS 116) as well as multivariate calculus and linear algebra. This course will emphasize implementing models and algorithms in Python, so coding proficiency is important. We will have a coding primer in the first week to help get you up to speed if you're coming from R or Matlab.

## Logistics
- **Time:** MW 1:30pm-2:20pm
- **Location:** MW in [STLC115](http://campus-map.stanford.edu/?srch=STLC115)
- **Grading:** Credit or letter grade
- **Components:** Lectures on Mon/Wed
- **Office Hours:**
    - Scott: 10:30am-12:00pm Tuesday, Wu Tsai Neurosciences Institute, 2nd floor by the NeuroTheory center
    - Noah: 10am-11:30am Monday, CoDa room B06
    - Amber: 1:30-3pm Friday, CoDa room B40
- This course will have a **final project, not an exam**

## Book
We will use an online textbook that I have been developing over the past few years called [_Machine Learning Methods for Neural Data Analysis_](https://slinderman.github.io/ml4nd/). It's a work in progress, and I will continue to update it throughout the quarter!

## Schedule
The lectures develop the theory behind the methods developed in the labs (i.e., homework assignments). I've organized the course into four units: signal extraction, encoding and decoding, unsupervised modeling, and current research. At the end, you'll work on a final project in which you will use, explore, or extend the techniques studied in class.

### Unit I: Extracting Biological Signals from Raw Data

| Date        | Neuro Topic | ML Topic | Reading | Assignment |
| ----------- | ------------------ | -------- | ------- | ---------- |
| Mon, Mar 31 | Course Overview {Download}`[slides]<slides/pdf/01_intro.pdf>` | | [Basic neurobiology](https://slinderman.github.io/ml4nd/chapters/03_neurobio.html) <br> [Probabilistic modeling](https://slinderman.github.io/ml4nd/chapters/02_probabilistic_modeling.html)|
| Wed, Apr 2  | Spike Sorting | Mixture Models | [Spike Sorting by Clustering](https://slinderman.github.io/ml4nd/chapters/04a_spike_sorting_clustering.html) | <span style="color:red">[**Lab 1 Out**](https://slinderman.github.io/ml4nd/labs/01a_spike_sorting.html)</span> | 
| Mon, Apr 7  | Calcium Deconvolution | Matrix Factorization | | | 
| Wed, Apr 9  | Calcium Deconvolution | Convex Optimization  | | <span style="color:red">**Lab 1 Due** <br> **Lab 2 Out**</span> |
| Mon, Apr 14 | Markerless Pose Tracking | Convolution and Cross-Correlation | | |
| Wed, Apr 16 | Markerless Pose Tracking | Convolutional Neural Networks (CNNs) | | <span style="color:red">**Lab 2 Due** <br> **Lab 3 Out**</span> |

### Unit II: Encoding and Decoding Models for Neural Data

| Date        | Neuro Topic | ML Topic | Reading | Assignment |
| ----------- | ------------------ | -------- | ------- | ---------- |
| Mon, Apr 21 | Neural Encoding | [Generalized Linear Models (GLMs)]() | |  |
| Wed, Apr 23 | Neural Encoding | [Poisson Processes]() | | <span style="color:red">**Lab 3 Due** <br> **Lab 4 Out**</span> |
| Mon, Apr 28 | Bayesian Decoding | Bayesian Inference | | |
| Wed, Apr 30 | Bayesian Decoding | Markov Chain Monte Carlo (MCMC) | | <span style="color:red">**Lab 4 Due** <br> **Lab 5 Out**</span> |

### Unit III: Unsupervised models of neural and behavioral data

| Date        | Neuro Topic | ML Topic | Reading | Assignment |
| ----------- | ------------------ | -------- | ------- | ---------- |
| Mon, May 5  | Behavioral Segmentation | Hidden Markov Models (HMMs) | | |
| Wed, May 7  | Behavioral Segmentation | Expectation Maximization (EM) | | <span style="color:red">**Lab 5 Due** <br> **Lab 6 Out**</span> |
| Mon, May 12 | Neural Dynamics | Linear Dynamical Systems (LDS) | | | 
| Wed, May 14 | Neural Dynamics | Switching Linear Dynamical Systems (SLDS) | | <span style="color:red">**Lab 6 Due** <br> **Lab 7 Out**</span> |

### Unit IV: Current Research Topics

| Date        | Topic | Reading | Assignment |
| ----------- | ----- | ------- | ---------- |
| Mon, May 19 | (Sequential) Variational Autoencoders | | | 
| Wed, May 21 | Gaussian Process State Space Models | | <span style="color:red">**Lab 7 Due**</span> |
| Mon, May 26 | _Memorial Day, No Class_ | | | | 
| Wed, May 28 | (Neuromodulated) Recurrent Neural Networks | | |
| Mon, Jun 2  | Deep State Space Models | | |
| Wed, Jun 4  | Foundation Models for Neuroscience| | |
| Mon, Jun 9  | | | <span style="color:red">**Final Project Due**</span> |

## Labs
- Each week, you will implement a minimal version of the method we discussed in lecture. These labs will be your assignments.
- You must work in a **team of two** people. 
- There's a **catch**! You may _not_ work with the same person twice. (We will have a discussion forum on Ed to facilitate matching.)
- Lab reports will be submitted via GradeScope.
- All assignments are due at 11:59pm PT on the specified date.

### Links to Assignments

1. [Lab 1: Spike Sorting by Clustering](https://slinderman.github.io/ml4nd/labs/01a_spike_sorting.html)

## Final project

- You will work on the final project in teams of 2 people (you choose your team!)
- You must use real neural or behavioral data. We will provide links to suggested datasets, or if you are an experimentalist, you can use your own.
- A project proposal will be due **TBD.**
- The final report will be due **Mon, June 9 at 11:59pm.**

## Late Policy
We will allow 7 late days to be used as needed throughout the quarter. Since assignments are done in teams of two, both students must have sufficient late days to turn in a late assignment. Unfortunately, we cannot allow late days on the final project.

## Grading
- 7 labs: 10% each, total 70%
- Final project: 25%
- Participation: 5%

**Note: You must do a final project in order to pass.**
