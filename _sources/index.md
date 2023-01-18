# Introduction

**Welcome to STATS320!**

_This course is cross-listed as STATS220, NBIO220 and CS339N. They are all the same. Enroll in the version that is best for your degree requirements._

**Instructor:** Scott Linderman <br>
**TAs:** Sifan Liu and Ying Jin <br>
Winter Quarter, 2022-23 <br>
Stanford University

## Course Description
With modern high-density electrodes and optical imaging techniques, neuroscientists routinely measure the activity of hundreds, if not thousands, of cells simultaneously.  Coupled with high-resolution behavioral measurements, these datasets offer unprecedented opportunities to learn how neural circuits function.  This course will study statistical machine learning methods for analysing such datasets, including: spike sorting and calcium deconvolution techniques for extracting relevant signals from raw data; markerless tracking methods for estimating animal pose in behavioral videos; state space models for analysis of high-dimensional neural and behavioral time-series; point process models of neural spike trains; and deep learning methods for neural encoding and decoding. We will develop the theory behind these models and algorithms and then apply them to real datasets in the in-class coding labs and final project.

## Prerequisites
You should be comfortable with basic probability (STATS 116) as well as multivariate calculus and linear algebra. This course will emphasize implementing models and algorithms in Python, so coding proficiency is important. We will have a coding primer in the first week to help get you up to speed if you're coming from R or Matlab.

## Logistics
- **Time:** MWF 11:30am-12:20pm
- **Location:** 380-380Y
- **Grading:** Credit or letter grade
- **Components:** Lectures on Mon/Wed, in-class labs on Fri
- **Office Hours:**
    - Sifan: 6:00-7:30pm Tues, Sequoia Hall, Room 207
    - Scott: 1:30-2:30pm Wed, Wu Tsai Neurosciences Institute, Room M252G
    - Ying: 11:00-12:30pm Thurs, Sequoia Hall, Room 207
- This course will have a **final project, not an exam**


## Schedule
The lectures develop the theory behind the methods developed in lab. I've organized the course into three units: signal extraction, encoding and decoding, and unsupervised modeling. At the end, you'll work on a final project in which you will use, explore, or extend the techniques studied in class.

### Unit I: Extracting biological signals from raw data
| Date        | Type       | Topic |
| ----------- | ---------- | ----- |
| Mon, Jan 9  | Lecture 1  | {Download}`Course Overview<lectures/pdf/lecture01.pdf>`
| Wed, Jan 11 | Lecture 2  | [Probabilistic modeling](lectures/02_probabilistic_modeling)
| Fri, Jan 13 | Lecture 3  | [Basic neurobiology](lectures/03_neurobio) and [Simple spike sorting](lectures/04_simple_spike_sorting.ipynb). <br> _Lab 0: Python and PyTorch primer_ released (it will not be graded)
| Mon, Jan 16 | MLK Day    | _No class_
| Wed, Jan 18 | Lecture 4  | [Spike sorting by deconvolution](lectures/05_deconv_spike_sorting.ipynb)
| Fri, Jan 20 | Lab 1      | Kilosort from scratch
| Mon, Jan 23 | Lecture 5  | Finishing [spike sorting](lectures/05_deconv_spike_sorting.ipynb) and starting [calcium deconvolution](lectures/06_calcium_imaging.ipynb)
| Wed, Jan 25 | Lecture 6  | [Demixing and deconvolving calcium imaging data](lectures/06_calcium_imaging.ipynb)
| Fri, Jan 27 | Lab 2      | CaImAn from scratch
| Mon, Jan 30 | Lecture 7  | Markerless pose tracking

### Unit II: Encoding and decoding models for neural data
| Date        | Type       | Topic |
| ----------- | ---------- | ----- |
| Wed, Feb 1  | Lecture 8  | Encoding and decoding neural spike trains
| Fri, Feb 3  | Lab 3      | DeepLabCut from scratch
| Mon, Feb 6  | Lecture 9  | Encoding models of retinal ganglion cells
| Wed, Feb 8  | Lecture 10 | Encoding models of retinal ganglion cells II
| Fri, Feb 10 | Lab 4      | DeepRetina from scratch
| Mon, Feb 13 | Lecture 11 | Bayesian decoding of neural spike trains
| Wed, Feb 15 | Lecture 12 | Unsupervised modeling with latent variable models
| Fri, Feb 17 | Lab 5      | Decoding movement from neural data

### Unit III: Unsupervised models of neural and behavioral data
| Date        | Type       | Topic |
| ----------- | ---------- | ----- |
| Mon, Feb 20 | Pres. Day  | _No class_
| Wed, Feb 22 | Lecture 13 | Hidden Markov models (HMMs)
| Fri, Feb 24 | Lab 6      | MoSeq from scratch
| Mon, Feb 27 | Lecture 14 | Poisson linear dynamical systems
| Wed, Mar 1  | Lecture 15 | Switching linear dynamical systems (SLDS)
| Fri, Mar 3  | Lab 7 (not graded) | SLDS from scratch
| Mon, Mar 6  | Lecture 16 | Variational Autoencoders (VAEs)
| Wed, Mar 8  | Lecture 17 | Sequential VAEs
| Fri, Mar 10 | Lab 8 (not graded) | LFADS from scratch
| Mon, Mar 13 | Guest Lec. | [Russ Poldrack](https://poldrack.github.io/) (topic TBD)
| Wed, Mar 15 | Lecture 19 | Current research
| Fri, Mar 17 | Presentations | Project presentations (ideally 11:20-1:20pm, with lunch provided)

## Labs
- You will work start the labs in class on Fridays, so attendance is required. (If you are sick or have a one-time conflict, please let me know as soon as possible.)
- You will be automatically assigned to a team of 3 students.
- The labs will probably take more than one class period to complete. You should find time to work with your teammates outside of class to finish them.
- The labs are due the following Thursday night at 11:59pm.
- Lab reports will be submitted via GradeScope.

## Final project

- You will work on the final project in teams of 2-3 people.
- You must use real neural or behavioral data. We will provide links to suggested datasets, or if you are an experimentalist, you can use your own!
- The final report will be due **Friday, Mar 24 at 11:30am.**

## Grading
- First 6 labs: 10% each, total 60%
- Final project presentation: 10%
- Final project report: 20%
- Participation: 5%

*Note: We will work on Labs 7 and 8 in class, but they will not be graded. That way you can focus on final proejcts in March. Your attendance on those days will count toward the class participation grade.*