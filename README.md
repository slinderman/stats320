# STATS320: Machine Learning Methods for Neural Data Analysis
Cross-listed as NBIO220 and CS339N <br>
Instructor: Scott Linderman <br>
Winter Quarter, 2021 <br>
Stanford University

## Course Description
With modern high-density electrodes and optical imaging techniques, neuroscientists routinely measure the activity of hundreds, if not thousands, of cells simultaneously.  Coupled with high-resolution behavioral measurements, these datasets offer unprecedented opportunities to learn how neural circuits function.  This course will study statistical machine learning methods for analysing such datasets, including: spike sorting, calcium deconvolution, and voltage smoothing techniques for extracting relevant signals from raw data; markerless tracking methods for estimating animal pose in behavioral videos; state space models for analysis of high-dimensional neural and behavioral time-series; point process models of neural spike trains; and deep learning methods for neural encoding and decoding. We will develop the theory behind these models and algorithms and then apply them to real datasets in the in-class coding labs and final project.

## Labs
The course is organized around eight coding labs. Each lab develops a minimal implementation of a state-of-the-art method from scratch in a self-contained Google Colab notebook. These are widely used techniques for analyzing neural and behavioral data, and through the labs you'll get a deep understanding of how these methods work under the hood:

1. [A simple spike sorting algorithm](https://colab.research.google.com/github/slinderman/stats320/blob/main/labs/Lab_1_Spike_Sorting.ipynb) [[Solutions (upon request)]](https://colab.research.google.com/drive/1Z5lEWvCaN2ny-haB_czs8izprrzYRMnx?usp=sharing)
2. [Kilosort: Spike sorting by Deconvolution](https://colab.research.google.com/github/slinderman/stats320/blob/main/labs/Lab_2_Spike_Sorting_with_Deconvolution.ipynb) [[Solutions (upon request)]](https://colab.research.google.com/drive/1ejD-NL-cjdjGS4woCknqZAo4gBG2q8xo?usp=sharing)
3. [CNMF: Calcium deconvolution via constrained NMF](https://colab.research.google.com/github/slinderman/stats320/blob/main/labs/Lab_3_Calcium_demixing_and_deconvolution.ipynb) [[Solutions (upon request)]](https://colab.research.google.com/drive/1QiiEr-NnGlsUmgbulRum86_2ZL6pOTPG?usp=sharing)
4. [DeepLabCut: Markerless pose tracking with CNNs](https://colab.research.google.com/github/slinderman/stats320/blob/main/labs/Lab_4_Markerless_pose_tracking.ipynb) [[Solutions (upon request)]](https://colab.research.google.com/drive/1j5GcNmPZhjyKioB4mN--N9RspmESXxgb?usp=sharing)
5. [DeepRetina: Deep encoding models of retinal spike trains](https://colab.research.google.com/github/slinderman/stats320/blob/main/labs/Lab_5_Encoding_models_of_retinal_ganglion_cells.ipynb) [[Solutions (upon request)]](https://colab.research.google.com/drive/1Pdw-1TiCQuGDUr_mCzMDj9Q1mF7sYRoS?usp=sharing)
6. [Kalman Smoothers: Decoding movement from neural data](https://colab.research.google.com/github/slinderman/stats320/blob/main/labs/Lab_6_Decoding_movement_from_motor_cortex_recordings.ipynb) [[Solutions (upon request)]](https://colab.research.google.com/drive/1OE1hKHwuUrnfBkILnFsgIdFCZK0q8viM?usp=sharing)
7. [MoSeq: Autoregressive HMMs for animal movements](https://colab.research.google.com/github/slinderman/stats320/blob/main/labs/Lab_7_Autoregressive_Hidden_Markov_Models_of_Behavior.ipynb) [[Solutions (upon request)]](https://colab.research.google.com/drive/1tAlnda5nSR2KdCakRRp7I1fcdBdYEFS1?usp=sharing)
8. [SLDS: Switching LDS model of neural data](https://colab.research.google.com/github/slinderman/stats320/blob/main/labs/Lab_8_Latent_Variable_Models,_Variational_EM,_and_Worm_Brains.ipynb) [[Solutions (upon request)]](https://colab.research.google.com/drive/1NORGTLRu9i9fmMQpxeK7--WsPk4y-boD?usp=sharing)

## Schedule
The lectures develop the theory behind the methods developed in lab. I've organized the course into three units: signal extraction, encoding and decoding, and unsupervised modeling of neural and behavioral data. At the end, you'll work on a final project in which you will use, explore, or extend the techniques studied in class.

_Unit I: Extracting biological signals from raw data_
| Date        | Type       | Topic |
| ----------- | ---------- | ----- |
| Mon, Jan 11 | Lecture 1  | [Course Overview](https://github.com/slinderman/stats320/blob/main/lectures/lecture01.pdf) |
| Wed, Jan 13 | Lecture 2  | [Basic spike sorting](https://github.com/slinderman/stats320/blob/main/lectures/lecture02.pdf) |
| Fri, Jan 15 | Lab 1      | [A simple spike sorting algorithm](https://colab.research.google.com/github/slinderman/stats320/blob/main/labs/Lab_1_Spike_Sorting.ipynb) |
| Mon, Jan 18 | MLK Day    | |
| Wed, Jan 20 | Lecture 3  | [Spike sorting by deconvolution](https://github.com/slinderman/stats320/blob/main/lectures/lecture03.pdf) |
| Fri, Jan 22 | Lab 2      | [Spike sorting by Deconvolution](https://colab.research.google.com/github/slinderman/stats320/blob/main/labs/Lab_2_Spike_Sorting_with_Deconvolution.ipynb) |
| Mon, Jan 25 | Lecture 4  | [Demixing and deconvolving calcium imaging](https://github.com/slinderman/stats320/blob/main/lectures/lecture04.pdf) |
| Wed, Jan 27 | Lecture 5  | [Deconvolution with a point process prior](https://github.com/slinderman/stats320/blob/main/lectures/lecture05.pdf) |
| Fri, Jan 29 | Lab 3      | [Calcium deconvolution via constrained NMF](https://colab.research.google.com/github/slinderman/stats320/blob/main/labs/Lab_3_Calcium_demixing_and_deconvolution.ipynb) |
| Mon, Feb 1  | Lecture 6  | [Markerless pose tracking](https://github.com/slinderman/stats320/blob/main/lectures/lecture06.pdf) |

_Unit II: Encoding and decoding models for neural data_
| Date        | Type       | Topic |
| ----------- | ---------- | ----- |
| Wed, Feb 3  | Lecture 7  | [Encoding and decoding neural spike trains](https://github.com/slinderman/stats320/blob/main/lectures/lecture07.pdf) |
| Fri, Feb 5  | Lab 4      | [Markerless animal pose tracking with CNNs](https://colab.research.google.com/github/slinderman/stats320/blob/main/labs/Lab_4_Markerless_pose_tracking.ipynb) |
| Mon, Feb 8  | Lecture 8  | [Encoding models of retinal ganglion cells](https://github.com/slinderman/stats320/blob/main/lectures/lecture08.pdf) |
| Wed, Feb 10 | Lecture 9  | [Encoding models of retinal ganglion cells II](https://github.com/slinderman/stats320/blob/main/lectures/lecture09.pdf) |
| Fri, Feb 12 | Lab 5      | [Deep encoding models of retinal spike trains](https://colab.research.google.com/github/slinderman/stats320/blob/main/labs/Lab_5_Encoding_models_of_retinal_ganglion_cells.ipynb) |
| Mon, Feb 15 | President’s Day | |
| Wed, Feb 17 | Lecture 10 | [Decoding neural spike trains](https://github.com/slinderman/stats320/blob/main/lectures/lecture10.pdf) |
| Fri, Feb 19 | Lab 6      | [Decoding movement from neural data](https://colab.research.google.com/github/slinderman/stats320/blob/main/labs/Lab_6_Decoding_movement_from_motor_cortex_recordings.ipynb) |

_Unit III: Unsupervised models of neural and behavioral data_
| Date        | Type       | Topic |
| ----------- | ---------- | ----- |
| Mon, Feb 22 | Lecture 11 | [Unsupervised  modeling and Expectation Maximization](https://github.com/slinderman/stats320/blob/main/lectures/lecture11.pdf) |
| Wed, Feb 24 | Lecture 12 | [EM amd Hidden Markov models](https://github.com/slinderman/stats320/blob/main/lectures/lecture12.pdf) |
| Fri, Feb 26 | Lab 7      | [Autoregressive HMMs for animal movements](https://colab.research.google.com/github/slinderman/stats320/blob/main/labs/Lab_7_Autoregressive_Hidden_Markov_Models_of_Behavior.ipynb) |
| Mon, Mar 1  | Lecture 13 | [Switching linear dynamical systems](https://github.com/slinderman/stats320/blob/main/lectures/lecture13.pdf) |
| Wed, Mar 3  | Lecture 14 | [Variational EM for SLDS](https://github.com/slinderman/stats320/blob/main/lectures/lecture14.pdf) |
| Fri, Mar 5  | Lab 8      | [Switching LDS model of neural data](https://colab.research.google.com/github/slinderman/stats320/blob/main/labs/Lab_8_Latent_Variable_Models,_Variational_EM,_and_Worm_Brains.ipynb) |
| Mon, Mar 8  | Lecture 15 | [Stochastic RNNs and LFADS](https://github.com/slinderman/stats320/blob/main/lectures/lecture15.pdf) |
| Wed, Mar 10 | Lecture 16 | [Looking forward](https://github.com/slinderman/stats320/blob/main/lectures/lecture16.pdf) |

_Final Projects_
| Date        | Type       | Topic |
| ----------- | ---------- | ----- |
| Fri, Mar 12 | Projects   | Work on final projects |
| Mon, Mar 15 | Projects   | Work on final projects |
| Wed, Mar 17 | Presentations | Project poster session |
| Fri, Mar 19 | Presentations | Project poster session |
