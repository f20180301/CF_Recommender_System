CONTENTS OF THIS FILE
---------------------

 * Readme
 * Report
 * original
    * RS_main.py
    * test .py
 * innovation_case_amplification
    * RS_main_Amplification.py
 * innovation_significance_weight
   * RS_main_Signif_Weighing.py     
 * Datasets
    * test_user.txt
    * ratings.csv
    * movies.csv
 * Output_Files
    * output.csv
    * eval_1.csv 
    * eval_2.csv  
    * eval_3.csv 

 

INTRODUCTION
------------
The objective of the assignment is to get hands on designing recommender system for movies data using collaborative filtering (CF) personalization techniques and suggest target user top-5 movies  most likely to watch. In part A, we have designed an overall user-based CF recommender system and evaluated its performance. In part B, we have come up with some improvements over the previously used approach in terms of the recommended movies list.

REQUIREMENTS
------------

This module requires the following modules:

 * Python(Version 3 and above)
 * Numpy
 * Pandas
 * Scikit-learn


 
  Inputs and Output Description
 -----
     # INPUTS
     test user.txt 
     ratings.csv
     movies.csv
     
     # OUTPUTS
     output.csv
     eval_1.csv 
     eval_2.csv  
     eval_3.csv 
 STEPS TO RUN THE CODE
 ------------
 Run recommender system which includes user-item matrix generation, neighborhood generation, prediction and and performance evaluation. This should take command line arguments: input as rating.csv and save the output of MAE performance evaluation in eval_1.csv.

     python RS_main.py −−input ratings.csv   −−output eval_1.csv


 Run predictor which will take input as a list of test users and save output predictions in output.csv as the list of the top-5 recommended movies along with previously seen.
 
      python test.py −−input test_user.txt   −−output output.csv


  Run innovation_1 recommender system which includes user-item matrix generation, neighborhood generation, prediction and and performance evaluation. This should take command line arguments: input as rating.csv and save the output of MAE performance evaluation in eval_2.csv
  
      python RS_main_Signif_Weighing.py −−input ratings.csv −−output eval_2.csv


  Run innovation_2 recommender system which includes user-item matrix generation, neighborhood generation, prediction and and performance evaluation. This should take command line arguments: input as rating.csv and save the output of MAE performance evaluation in eval_3.csv
  
     python RS_main_Amplification.py −−input ratings.csv −−output eval_3.csv
 
 

 

Created by
Shubham Agarwal 2018A7PS0301P
Aditya V. Bodade 2018A7PS0256P
Egna Praneeth Gummana 2018A7PS0284P
Utkarsh Srivastava 2018A7PS0339P
Shivansh Rustagi 2018A8PS0745P

Done under:
CS F469, Information Retrieval: Assignment-2
Instructor: Vinti Agarwal (vinti.agarwal@pilani.bits-pilani.ac.in)
Topic: CF based Recommender System
Due Date: 21st November, 2020

