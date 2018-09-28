# Musical Data Analysis Project for Machine Learning Basic Principles (MLBP) course 2018 at Aalto Univeristy

## Introduction

The data analysis project involves the design of a complete machine learning solution. In
particular, the project revolves around the task of identifying the music genre of songs. This
is useful as a way to group music into categories that can be later used for recommendation
or discovery. The problem of music genre classification is difficult: while some genres
distinctions are fairly straightforward (e.g. heavy metal vs classical), others are fuzzier (e.g.
rock vs blues).

## Objective 

In this data analysis project, our task was to construct a predictor h(x) for each genre Y, which
takes the features x and maps it to a probability h(x) that the genre is "rock" (e.g.) or not.
We tried out different machine learning methods, including but not limited to those
presented throughout this course, for predicting the music genre of songs. The dataset
which was provided to solve this task contains preprocessed audio information. In particular,
the raw audio signals have been transformed to carefully chosen features.

## Dataset

The data is split into two datasets: a training data set with 4363 songs, and a test set dataset
with 6544 songs. Each song has 264 features, and there are 10 possible classes in total.
The dataset is a custom subset of the Million Song Dataset, and the labels were obtained
from AllMusic.com. For simplicity, each song has been assigned only one label that
corresponds to the most representative genre. The 10 labels are:

..* Pop_Rock  
..* Electronic  
..* Rap  
..* Jazz  
..* Latin  
..* RnB  
..* International  
..* Country  
..* Reggae  
..* Blues  

The features provided are a summary representation of the 3 main components of music:
timbre, pitch (melody and harmony) and rhythm. A very brief description of these
components:

**Timbre**: "The tonal colour, or timbre, is a multidimensional psychoacoustic measure. When
two sounds have the same pitch, loudness, and duration, timbre is what makes one
particular musical sound different from another. For example, the same musical notes played
by a piano and a trumpet are easily distinguished by listeners as being different. The best
physical explanation for this difference comes from the spectrum and its variation with time."
[from Communication Acoustics]

**Rhythm**: "Rhythm is a complex concept which refers to different temporal structures in
music. The existence of rhythm is based on natural repetitions in time, such as walking,
running, the heartbeat, and breathing." [from Communication Acoustics]

**Pitch**: "Pitch is defined by the American National Standards Institute as ‘that auditory
attribute of sound according to which sounds can be ordered on a scale from low to high’
(ANSI-S1.1, 2013)." [from Communication Acoustics]

## Findings & Report

All the results from the dataset along with the explanation and some interesting metrics, such as
the accuracy and log loss in correctly identifying each genre has been provided in the Python Notebook.
All details ranging from the alogrithmic techniques used to the reasons for their choice and the relevant
outcomes has been provided in this notebook.

## Authors

1. **Olli Herrala**
2. **Muhammad Abdullah Khan** 

