# Starbucks-offers
Udacity Data Scientist Nanodegree Capstone Project: Starbucks offers analysis

This project is an analysis of the Starbucks transactions dataset.

## Starbucks Capstone Challenge: Using Starbucks app user data to predict effective offers
 
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)



## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

### Project Motivation <a name="project-motivation"></a>
This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.

Not all users receive the same offer, and that is the challenge to solve with this data set.

In this project, I use the data to answer 2 business questions:

  - 1. What are the main features influencing the effectiveness of an offer on the Starbucks app?
  - 2. Could the data provided, namely offer characteristics and user demographics, predict whether a user would take up an offer?

To answer the above 2 questions, I firslty defined what an effective offer means in this context. I then created 3 models for the data for the 3 different offer types: Buy One Get One Free (BOGO), Discount , and Informational (provides information about products). I then deployed ML models to understand which features are important.

### File Descriptions <a name="files"></a>
This repo contains 4 files.There is a notebook available here to showcase work related to the above questions and wrangling process. There are 3 data files used to address the above qustions.

1. portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
2. profile.json - demographic data for each customer
3. transcript.json - records for transactions, offers received, offers viewed, and offers completed

## Results<a name="results"></a>

The main observations of the code are published [here]().

In brief, the offers seem to be slightly more effective for the younger age group (20-40 years), lower income group and for men. Furthermore, in all the three datasets, it turns out that the number of membership days is a very important feature. Presumably, the longer one is a member, the more likely they will respond to the offer they receive. Amount, age and income are, in general, other important factors. Gender and social channel used to communicate the offers seem to matter less. 

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

The data for this project was generously provided by Udacity and Starbucks. This project is licensed under the terms of the MIT license.

