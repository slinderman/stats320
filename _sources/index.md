# Syllabus

**Welcome to STATS320!**

_This course is cross-listed as STATS220, NBIO220 and CS339N. They are all the same. Enroll in the version that is best for your degree requirements._

**Instructor:** Scott Linderman <br>
**TAs:** Noah Cowan <br>
Spring Quarter, 2024-25 <br>
Stanford University

## Course Description
With modern high-density electrodes and optical imaging techniques, neuroscientists routinely measure the activity of hundreds, if not thousands, of cells simultaneously.  Coupled with high-resolution behavioral measurements, these datasets offer unprecedented opportunities to learn how neural circuits function.  This course will study statistical machine learning methods for analysing such datasets, including: spike sorting and calcium deconvolution techniques for extracting relevant signals from raw data; markerless tracking methods for estimating animal pose in behavioral videos; state space models for analysis of high-dimensional neural and behavioral time-series; point process models of neural spike trains; and deep learning methods for neural encoding and decoding. We will develop the theory behind these models and algorithms and then apply them to real datasets in the in-class coding labs and final project.

## Prerequisites
You should be comfortable with basic probability (STATS 116) as well as multivariate calculus and linear algebra. This course will emphasize implementing models and algorithms in Python, so coding proficiency is important. We will have a coding primer in the first week to help get you up to speed if you're coming from R or Matlab.

## Logistics
- **Time:** MW 1:30am-2:20pm
- **Location:** MW in [STLC115](http://campus-map.stanford.edu/?srch=STLC115)
- **Grading:** Credit or letter grade
- **Components:** Lectures on Mon/Wed
- **Office Hours:**
    - Scott: 10:30am-12:00pm Tuesday, Wu Tsai Neurosciences Institute, 2nd floor by the NeuroTheory center
    - Noah: TBD
- This course will have a **final project, not an exam**

## Book
We will use an online textbook called [_Machine Learning Methods for Neural Data Analysis_](https://slinderman.github.io/ml4nd/) that I have been developing for this course over the past few years. It's a work in progress, and I will continue to update it throughout the quarter!

## Schedule
The lectures develop the theory behind the methods developed in the labs (i.e., homework assignments). I've organized the course into four units: signal extraction, encoding and decoding, unsupervised modeling, and current research. At the end, you'll work on a final project in which you will use, explore, or extend the techniques studied in class.

### Unit I: Extracting Biological Signals from Raw Data

#### Week 1: Spike Sorting
| Date        | Topic | Reading |
| ----------- | ----- | ------- |
| Mon, Mar 31 | Course Overview {Download}`[slides]<lectures/pdf/lecture01.pdf>` | [Basic neurobiology](lectures/03_neurobio) |
| Wed, Apr 2  | Mixture Models | [Probabilistic modeling](lectures/02_probabilistic_modeling) |

<span style="color:red">**Lab 1: Spike Sorting** _Released Wed, Apr 2; Due Wed, Apr 9 at 11:59pm._</span>

#### Week 2: Calcium Deconvolution
| Date        | Topic | Reading |
| ----------- | ----- | ------- |
| Mon, Apr 7  | Matrix Factorization | |
| Wed, Apr 9  | Convex Optimization | |

<span style="color:red">**Lab 2: Calcium Deconvolution** _Released Wed, Apr 9; Due Wed, Apr 16 at 11:59pm._</span>

#### Week 3: Markerless Pose Tracking
| Date        | Topic | Reading |
| ----------- | ----- | ------- |
| Mon, Apr 14 | Convolution and Cross-Correlation | | 
| Wed, Apr 16 | Convolutional Neural Networks (CNNs) | | 

<span style="color:red">**Lab 3: Markerless Pose Tracking** _Released Wed, Apr 16; Due Wed, Apr 23 at 11:59pm._</span>


### Unit II: Encoding and Decoding Models for Neural Data

#### Week 4: Predicting Neural Responses with GLMs
| Date        | Topic | Reading |
| ----------- | ----- | ------- |
| Mon, Apr 21 | [Generalized Linear Models (GLMs)]() | | 
| Wed, Apr 23 | [Poisson Processes]() | |

<span style="color:red">**Lab 4: Generalized Linear Models of Neural Responses** _Released Wed, Apr 23; Due Wed, Apr 30 at 11:59pm._</span>

#### Week 5: Decoding Neural Activity
| Date        | Topic | Reading |
| ----------- | ----- | ------- |
| Mon, Apr 28 | Bayesian Inference | | 
| Wed, Apr 30 | Markov Chain Monte Carlo (MCMC) | |

<span style="color:red">**Lab 5: Bayesian Decoding of Neural Spike Trains** _Released Wed, Apr 30; Due Wed, May 7 at 11:59pm._</span>

### Unit III: Unsupervised models of neural and behavioral data

#### Week 6: Segmenting Behavioral Video
| Date        | Topic | Reading |
| ----------- | ----- | ------- |
| Mon, May 5  | Hidden Markov Models (HMMs) | | 
| Wed, May 7  | Expectation Maximization (EM) | |

<span style="color:red">**Lab 6: Autoregressive HMMs for Behavioral Video** _Released Wed, May 7; Due Wed, May 14 at 11:59pm._</span>

#### Week 7: Modeling Low-Dimensional Neural Dynamics

| Date        | Topic | Reading |
| ----------- | ----- | ------- |
| Mon, May 12 | Linear Dynamical Systems (LDS) | |
| Wed, May 14 | Switching linear dynamical systems (SLDS) | |

<span style="color:red">**Lab 7: State Space Models of Neural Activity** _Released Wed, May 14; Due Wed, May 21 at 11:59pm._</span>

### Unit IV: Current Research Topics

| Date        | Topic | Reading |
| ----------- | ----- | ------- |
| Mon, May 19 | (Sequential) Variational Autoencoders | | 
| Wed, May 21 | Gaussian Process State Space Models | | 
| Mon, May 26 | _Memorial Day, No Class_ |   |
| Wed, May 28 | (Neuromodulated) Recurrent Neural Networks | |
| Mon, Jun 2  | Deep State Space Models | |
| Wed, Jun 4  | Foundation Models for Neuroscience| | 

<span style="color:red">**Final Project** _Due Mon, June 9 at 11:59pm._</span>

## Labs
- Each week, you will implement a minimal version of the method we discussed in lecture. These labs will be your assignments.
- You must work in a **team of two** people. 
- Lab reports will be submitted via GradeScope.

## Final project

- You will work on the final project in teams of 2 people (you choose your team!)
- You must use real neural or behavioral data. We will provide links to suggested datasets, or if you are an experimentalist, you can use your own.
- A project proposal will be due **TBD.**
- The final report will be due **Mon, June 9 at 11:59pm.**

## Grading
- 7 labs: 10% each, total 70%
- Final project: 25%
- Participation: 5%

**Note: You must do a final project in order to pass.**