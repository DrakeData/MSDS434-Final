# MSDS434 - Final Project (Part I)

This repository contains code and documentation for MSDS 434 final project (Part I). This repository covers week 1-10 learning objective documentations, code used, and videos that corraspond with them.

## Table of Contents
- [Class Contents](#class-contents)
  * [Week 1 - Introduction to GCP](#week-1---introduction-to-gcp)
  * [Week 2 - Github and Continuous Integration](#week-2---github-and-continuous-integration)
  * [Week 3 - Google Cloud Platform (GCP)](#week-3---google-cloud-platform--gcp-)
  * [Week 4 - Cloud-Native Database Choice and Design](#week-4---cloud-native-database-choice-and-design)
  * [Week 5 - Applied Data Engineering](#week-5---applied-data-engineering)
  * [Week 6 - Managed ML Platforms](#week-6---managed-ml-platforms)
  * [Week 7 - Operationalizing ML Models](#week-7---operationalizing-ml-models)
  * [Week 8 - Total Cost of Ownership (TCO) Estimation for Engineering Projects](#week-8---total-cost-of-ownership-tco-estimation-for-engineering-projects)
  * [Week 9 - Monitoring](#week-9---monitoring)
  * [Week 10 - Coming Soon](#week-10)

## Class Contents
### Week 1 - Introduction to GCP
#### Video Recording
[![Week 1 Video](https://cdn.loom.com/sessions/thumbnails/2dfa50f27e6c4cc993c0aadd6618d7ef-with-play.gif)](https://www.loom.com/share/2dfa50f27e6c4cc993c0aadd6618d7ef)

#### Objective
- Demo instantation of an instance on both the Google Cloud Platform as well as on Amazon AWS.
- Describe one application of AI that you would be interested in pursuing in the context of the GCP leveraging the technologies identified in this course.

#### My Learnings
- How to start up and stop projects within GCP and AWS
- How to access the consul within GCP and AWS

### Week 2 - Github and Continuous Integration
#### Video Recording
##### GCP Example
[![Week 2 Video - GCP](https://cdn.loom.com/sessions/thumbnails/71f4a9788a6846e7a0735e5ce318bc68-with-play.gif)](https://www.loom.com/share/71f4a9788a6846e7a0735e5ce318bc68)

##### AWS Example
[![Week 2 Video - AWS](https://cdn.loom.com/sessions/thumbnails/15a9f0868ca346989ddfb1f17ff90535-with-play.gif)](https://www.loom.com/share/15a9f0868ca346989ddfb1f17ff90535)

#### Objective
- Start up a project in both GCP and AWS 
- Create a GitHub repository and push code to it
- Clone GitHub repository to both GCP and AWS projects
- Edit code in GCP and AWS projects and push the changes back to the GitHub repository

#### My Learnings
- How to clone a GitHub repository in both GCP and AWS
- How to edit code in GCP and AWS, then push it to my GitHub repository
- In GCP, you need to sudo install git as git is not installed automatically

#### Code Used
- [Week 2 Commands](https://github.com/DrakeData/MSDS434-Final/blob/main/code/msds434_week2_commands.txt)

### Week 3 - Google Cloud Platform (GCP)
#### Video Recordings
[![Week 3 Video](https://cdn.loom.com/sessions/thumbnails/b06813ff52294b14aa21944e70991002-with-play.gif)](https://www.loom.com/share/b06813ff52294b14aa21944e70991002)

#### Objective
- Create a “hello world” pipeline to Google Cloud that calls into a Python-based Google App Engine (GAE) project and returns “hello world” as a JavaScript Object Notation (JSON) response.

#### My Learnings
- How to set up APIs & Services on GCP
- Enabeling Cloud Builder API
- Connecting my builing account to the project
- Activating a yaml file to deploy app
- How to shutdown project after I am done using it
- Gcloud commands to verify the shutdown of the project

#### Code Used
- [Week 3 Commands](https://github.com/DrakeData/MSDS434-Final/blob/main/code/msds434_week3_commands.txt)

### Week 4 - Cloud-Native Database Choice and Design
#### Video Recordings
[![Week 4 Video](https://cdn.loom.com/sessions/thumbnails/8cf1f8d97c5946a88a5a058ea6aecd8a-with-play.gif)](https://www.loom.com/share/8cf1f8d97c5946a88a5a058ea6aecd8a)

#### Objective
- Create an ingest to ETL pipeline using CSV files and Google BigQuery
- Schedule a recurring cron job to batch update the data

#### My Learnings
- How to access Cloud Shell Editor in GCP and use the GUI to manage directories
- Use Python to call an API and save the json output in a pandas data frame, then export the data frame to a CSV file in my GCP project
- Use command line to grab a CSV file in my project directory, move it to a GCP Bucket, then load the data into BigQuery

#### Code Used
- [Week 4 Commands](https://github.com/DrakeData/MSDS434-Final/blob/main/code/msds434_week4_commands.txt)

### Week 5 - Applied Data Engineering
#### Video Recordings
[![Week 5 Video](https://cdn.loom.com/sessions/thumbnails/b5ee846203ca4fe9bf3c84d951b46c33-with-play.gif)](https://www.loom.com/share/b5ee846203ca4fe9bf3c84d951b46c33)

[Kaggle Data Set](https://www.kaggle.com/datasets/lehaknarnauli/spotify-datasets?select=tracks.csv)

#### Objective
- Return an aggregated result with a machine-learning (ML) prediction using Google BigQuery ML
- Serve out results using Google App Engine

#### My Learnings
- How to load a dataset into BigQuery
- Run a basic Machine Learning (ML) Regression Model within BiqQuery
- View results of model and evaluate how it performed

#### Code Used
- [Week 5 Commands](https://github.com/DrakeData/MSDS434-Final/blob/main/code/msds434_week5_commands.txt)


### Week 6 - Managed ML Platforms
#### Video Recordings
[![Week 6 Video](https://cdn.loom.com/sessions/thumbnails/1f06e9292818475c82c867a853c54b7e-with-play.gif)](https://www.loom.com/share/1f06e9292818475c82c867a853c54b7e)

#### Objective
- Train a multi-class classification model on AutoML

#### My Learnings
- How to use AutoML within BiqQuery
- AutomML does take time to run and might not provide the best model results

#### Code USed
- [Week 6 Commands](https://github.com/DrakeData/MSDS434-Final/blob/main/code/msds434_week6_commands.txt)
- [Week 6 Python Code](https://github.com/DrakeData/MSDS434-Final/blob/main/code/week6_code/file_cleanup.ipynb)


### Week 7 - Operationalizing ML Models
#### Video Recordings
[![Week 7 Video](https://cdn.loom.com/sessions/thumbnails/1db48100eb124e35aca3ff70dac58095-with-play.gif)](https://www.loom.com/share/1db48100eb124e35aca3ff70dac58095)

#### Objective
- Create a production and development environment
- Deploy your final project to both environments

#### My Learnings
- Different ways you can deploy, monitor, and maintain multiple enviornments
- Built a Staging and Production projects enviornment within GCP.

#### Code Used
- [Week 7 Commands](https://github.com/DrakeData/MSDS434-Final/blob/main/code/msds434_week7_commands.txt)

#### Additional Learning Resource
- [Google Cloud Tech - Top 3 ways to run your containers on Google Cloud](https://www.youtube.com/watch?v=jh0fPT-AWwM)


### Week 8 - Total Cost of Ownership (TCO) Estimation for Engineering Projects
#### Video Recordings
[![Week 8 Video](https://cdn.loom.com/sessions/thumbnails/dbb2cdcd17d94dbba36a523ac753ccae-with-play.gif)](https://www.loom.com/share/dbb2cdcd17d94dbba36a523ac753ccae)

#### Objective
- Use the Google Cloud Platform Billing API
- Create a cost forecast using BigQuery ML

#### My Learnings
- Connect data transfer to a GCP billing table you create for your project
- Go to 'Billing Export' wihtin GCP and enable the different billing options you would like to export and conect ot BiqQuery table
- It does take time to load billing data into table
- Ran a simple query to take a look at my billing usage

#### Code Used
- [Week 8 Commands](https://github.com/DrakeData/MSDS434-Final/blob/main/code/msds434_week8_commands.txt)

### Week 9 - Monitoring
#### Video Recordings
[![Week 9 Video](https://cdn.loom.com/sessions/thumbnails/922521b42a574fcd9a4c6a27b3d98691-with-play.gif)](https://www.loom.com/share/922521b42a574fcd9a4c6a27b3d98691)

#### Objective
- Set up a monitoring dashboard within GCP
- Perform a simple load test using ApacheBench or a similar tool

#### My Learnings
- Started up a Virtual Machine (VM) within GCP
- Installed Go on VM
- Created a simple Go program to create activity on VM
- Built a monitoring within GCP
- Used apache within the command line to run basic metric checks
- How to create, edit and save a file using command line

#### Code Used
- [Week 9 Commands](https://github.com/DrakeData/MSDS434-Final/blob/main/code/msds434_week9_commands.txt)

### Week 10
Coming Soon
