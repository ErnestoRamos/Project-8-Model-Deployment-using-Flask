# Project-8-Model-Deployment-using-Flask

This repository contains a demo on how to deploy a saved ML model (via pkl) using Flask API. 
This application may be used by a hiring manager to predict the expected salary of an applicant based on the applicant's year's of exprience, test score, and interview score. 

Note that you must have Scikit Learn, Pandas and Flask (for API) installed.

# Brief overview of files:
  - app.py which contains flask api and computes the predicted value  
  - requests.py file which makes request to the api and returns the predicted value (if you want to make a request via cmd)
  - a HTML template to allow the user to host on a webserver
  
The default port flask will run on is port 5000.
  - ie. URL http://localhost:5000
 
![image](https://user-images.githubusercontent.com/56518821/111894214-4c8db600-89df-11eb-9df1-83f0f76442d3.png)

With 5 years experience, and an 8 test score and interview score, the expected salary is ~64k
![image](https://user-images.githubusercontent.com/56518821/111921844-30d0f100-8a6d-11eb-8b9b-c6dcee464997.png)
