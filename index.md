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
    - Noah: 10am-11:30am Monday, CoDa room B06 (OH on Monday 4/28 moved to Wednesday 4/30)
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
| Mon, Apr 7  | Spike Sorting{Download}`[slides]<slides/pdf/05_spike_sorting_deconv.pdf>` | Matrix Factorization | [Spike Sorting by Deconvolution](https://slinderman.github.io/ml4nd/chapters/05_deconv_spike_sorting.html) | | 
| Wed, Apr 9  | Calcium Deconvolution{Download}`[slides]<slides/pdf/06_calcium_imaging.pdf>` | Convex Optimization  | [Calcium Deconvolution](https://slinderman.github.io/ml4nd/chapters/06_calcium_imaging.html) | <span style="color:red">**Lab 1 Due** <br> [**Lab 2 Out**](https://slinderman.github.io/ml4nd/labs/02_calcium_imaging.html)</span> |
| Mon, Apr 14 | Markerless Pose Tracking {Download}`[slides]<slides/pdf/07_pose_tracking.pdf>` | Logistic Regression | [Markerless Pose Tracking](https://slinderman.github.io/ml4nd/chapters/07_pose_tracking.html) | |
| Wed, Apr 16 | Markerless Pose Tracking {Download}`[slides]<slides/pdf/07_pose_tracking.pdf>`| Convolutional Neural Networks (CNNs) | [Markerless Pose Tracking](https://slinderman.github.io/ml4nd/chapters/07_pose_tracking.html) | <span style="color:red">**Lab 2 Due** <br> [**Lab 3 Out**](https://slinderman.github.io/ml4nd/labs/03_pose_tracking.html)</span> |

### Unit II: Encoding and Decoding Models for Neural Data

| Date        | Neuro Topic | ML Topic | Reading | Assignment |
| ----------- | ------------------ | -------- | ------- | ---------- |
| Mon, Apr 21 | Neural Encoding {Download}`[slides]<slides/pdf/08_encoding.pdf>` | Generalized Linear Models (GLMs) | [Summary Statistics](https://slinderman.github.io/ml4nd/chapters/08_summary_stats.html) and [GLMs](https://slinderman.github.io/ml4nd/chapters/09_glm.html) | |
| Wed, Apr 23 | Neural Encoding | Poisson GLMs |  | <span style="color:red">**Lab 3 Due** <br> [**Lab 4 Out**](https://slinderman.github.io/ml4nd/labs/04_glms.html)</span> |
| Mon, Apr 28 | Bayesian Decoding | Poisson Processes{Download}`[slides]<slides/pdf/09_poisson_processes.pdf>` | [Poisson Processes](https://slinderman.github.io/ml4nd/chapters/10_poisson_processes.html) | |
| Wed, Apr 30 | Bayesian Decoding | Bayesian Inference{Download}`[slides]<slides/pdf/10_decoding.pdf>` | [Bayesian Decoding](https://slinderman.github.io/ml4nd/chapters/11_decoding.html) | <span style="color:red">**Lab 4 Due** <br> [**Lab 5 Out**](https://slinderman.github.io/ml4nd/labs/05_decoding.html)</span> |

### Unit III: Unsupervised models of neural and behavioral data

| Date        | Neuro Topic | ML Topic | Reading | Assignment |
| ----------- | ------------------ | -------- | ------- | ---------- |
| Mon, May 5  | Behavioral Segmentation{Download}`[slides]<slides/pdf/11_hmms.pdf>` | Hidden Markov Models (HMMs) | [HMMs](https://slinderman.github.io/ml4nd/chapters/13_hmms.html) | |
| Wed, May 7  | Behavioral Segmentation{Download}`[slides]<slides/pdf/12_em.pdf>` | Expectation Maximization (EM) | [HMMs](https://slinderman.github.io/ml4nd/chapters/13_hmms.html) | <span style="color:red">**Lab 5 Due** <br> [**Lab 6 Out**](https://slinderman.github.io/ml4nd/labs/06_arhmm.html)</span> |
| Mon, May 12 | Neural Dynamics | Switching Linear Dynamical Systems (SLDS){Download}`[slides]<slides/pdf/13_slds_new.pdf>` | | | 
| Wed, May 14 | Neural Dynamics | Fitting SLDS models | | <span style="color:red">**Lab 6 Due** <br> **Lab 7 Out**</span> |
| Fri, May 16 | &mdash; | &mdash; | | <span style="color:red">**Project Proposal Due**</span> |

### Unit IV: Current Research Topics

| Date        | Topic | Reading | Assignment |
| ----------- | ----- | ------- | ---------- |
| Mon, May 19 | (Sequential) Variational Autoencoders | | | 
| Wed, May 21 | Gaussian Process State Space Models | | <span style="color:red">**Lab 7 Due**</span> |
| Mon, May 26 | _Memorial Day, No Class_ | | | | 
| Wed, May 28 | (Neuromodulated) Recurrent Neural Networks | | |
| Mon, Jun 2  | Foundation Models for Neuroscience | | |
| Wed, Jun 4  | Wrap Up | | |
| Mon, Jun 9  | | | <span style="color:red">**Final Project Due**</span> |

## Labs
- Each week, you will implement a minimal version of the method we discussed in lecture. These labs will be your assignments.
- You must work in a **team of two** people. 
- There's a **catch**! You may _not_ work with the same person twice. (We will have a discussion forum on Ed to facilitate matching.)
- Lab reports will be submitted via GradeScope.
- All assignments are due at 11:59pm PT on the specified date.

### Links to Assignments

1. [Lab 1: Spike Sorting by Clustering](https://slinderman.github.io/ml4nd/labs/01a_spike_sorting.html). Due Wed, Apr 9 at 11:59pm.
2. [Lab 2: Calcium Demixing and Deconvolution](https://slinderman.github.io/ml4nd/labs/02_calcium_imaging.html) Due Wed, Apr 16 at 11:59pm.
3. [Lab 3: Markerless Pose Tracking](https://slinderman.github.io/ml4nd/labs/03_pose_tracking.html) Due Wed, Apr 23 at 11:59pm.
4. [Lab 4: Generalized Linear Models](https://slinderman.github.io/ml4nd/labs/04_glms.html) Due Wed, Apr 30 at 11:59pm.
5. [Lab 5: Bayesian Decoding](https://slinderman.github.io/ml4nd/labs/05_decoding.html) Due Wed, May 7 at 11:59pm.
5. [Lab 6: Autoregressive HMMs](https://slinderman.github.io/ml4nd/labs/06_arhmm.html) Due Wed, May 14 at 11:59pm.

## Final project

- You will work on the final project in teams of 2 people (you choose your team!)
- You must use real neural or behavioral data. We will provide links to suggested datasets, or if you are an experimentalist, you can use your own.
- A project proposal will be due **Fri, May 16 at 11:59pm.**
- The final report will be due **Mon, June 9 at 11:59pm.**

## Late Policy
We will allow 7 late days to be used as needed throughout the quarter. Since assignments are done in teams of two, both students must have sufficient late days to turn in a late assignment. Unfortunately, we cannot allow late days on the final project.

## Grading
- 7 labs: 10% each, total 70%
- Final project: 25%
- Participation: 5%

**Note: You must do a final project in order to pass.**
