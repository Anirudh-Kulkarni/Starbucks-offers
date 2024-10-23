# Analyzing Starbucks Offers
This project is part of the [Udacity Data Scientist Nanodegree program](https://www.udacity.com/course/data-scientist-nanodegree--nd025). In this project, I explore the Starbucks transactions dataset to uncover which offers effectively encourage users to purchase more coffee.

## Starbucks Capstone Challenge: Using Starbucks app user data to predict effective offers
 
### Table of Contents

1. [Requisites](#requisites)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)



## Requisites <a name="requisites"></a>

This project requires only the Anaconda distribution of Python; no additional libraries are necessary. The code is compatible with Python versions 3.*.

## Project Motivation <a name="project-motivation"></a>
The data set in this project contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. 

An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks. Not all users receive the same offer - this raises the question of whether some offers are more effective than others.

In this project, I use the data to answer 2 business questions:

1. What are the main features influencing the effectiveness of an offer on the Starbucks app?
2. Could the data provided, namely offer characteristics and user demographics, predict whether a user would take up an offer?

To answer the above 2 questions, I firstly defined what an effective offer means in this context. I then created 3 models for the data for the 3 different offer types: 
- Buy One Get One Free (BOGO),
- Discount , and
- Informational (provides information about products).

I then deployed Machine Learning (ML) models to understand which features are important for these effective offers.

## File Descriptions <a name="files"></a>

This repository contains the following files:

- portfolio.json: Contains offer IDs and metadata (duration, type, etc.) for each offer.
- profile.json: Demographic data for each customer.
- transcript.json: Records of transactions, offers received, offers viewed, and offers completed.
- notebook.ipynb: A Jupyter notebook documenting the analysis process and findings.

## Results<a name="results"></a>

The main observations of the code are published in this blog post [here](https://medium.com/@vigyaan/what-makes-starbucks-customers-opt-in-for-offers-92dcde588169).

In summary, the analysis indicates that 
1) Offers are generally more effective for younger customers (ages 20-40), lower-income groups, and male users.
2) The duration of membership emerges as a crucial factor - longer membership correlates with a higher likelihood of responding to offers.
3) Other significant factors include amount spent, age, and income, while gender and the social channel used for communication appear to play a lesser role.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

The data for this project was generously provided by Udacity and Starbucks. This project is licensed under the terms of the MIT license.

