# MSDS434 - Final Project (Part I)

This repository contains code and documentation for MSDS 434 Analytics Application Development final project (Part I). It covers week 1-10 learning objectives, documentation, code used, and videos that correspond with them.

## Table of Contents
- [Class Contents](#class-contents)
  * [Week 1 - Introduction to GCP](#week-1---introduction-to-gcp)
  * [Week 2 - Github and Continuous Integration](#week-2---github-and-continuous-integration)
  * [Week 3 - Google Cloud Platform (GCP)](#week-3---google-cloud-platform--gcp-)
  * [Week 4 - Cloud-Native Database Choice and Design](#week-4---cloud-native-database-choice-and-design)
  * [Week 5 - Applied Data Engineering](#week-5---applied-data-engineering)
  * [Week 6 - Managed ML Platforms](#week-6---managed-ml-platforms)
  * [Week 7 - Operationalizing ML Models](#week-7---operationalizing-ml-models)
  * [Week 8 - Total Cost of Ownership (TCO) Estimation for Engineering Projects](#week-8---total-cost-of-ownership--tco--estimation-for-engineering-projects)
  * [Week 9 - Monitoring](#week-9---monitoring)
  * [Week 10 - MVP](#week-10---mvp)
- [Learnings from my classmates](#learnings-from-my-classmates)
- [Final Thoughts](#final-thoughts)
- [Repository Information](#repository-information)

## Class Contents
### Week 1 - Introduction to GCP
#### Video Recording
[![Week 1 Video](https://cdn.loom.com/sessions/thumbnails/2dfa50f27e6c4cc993c0aadd6618d7ef-with-play.gif)](https://www.loom.com/share/2dfa50f27e6c4cc993c0aadd6618d7ef)

#### Objective
- Demo instantiation of an instance on both the Google Cloud Platform (GCP), as well as on Amazon AWS.
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
- In GCP, you need to 'sudo install git' as git is not installed automatically

#### Code Used
- [Week 2 Commands](https://github.com/DrakeData/MSDS434-Final/blob/main/code/msds434_week2_commands.txt)

### Week 3 - Google Cloud Platform (GCP)
#### Video Recordings
[![Week 3 Video](https://cdn.loom.com/sessions/thumbnails/b06813ff52294b14aa21944e70991002-with-play.gif)](https://www.loom.com/share/b06813ff52294b14aa21944e70991002)

#### Objective
- Create a “hello world” pipeline to Google Cloud that calls into a Python-based Google App Engine (GAE) project and returns “hello world” as a JavaScript Object Notation (JSON) response.

#### My Learnings
- How to set up APIs & Services on GCP
- Enabling Cloud Builder API
- Connecting my billing account to the project
- Activating a yaml file to deploy app
- How to shutdown project after I am done using it
- Use gcloud commands to verify the shutdown of the project

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
- Run a basic Machine Learning (ML) Regression Model within BigQuery
- View results of model and evaluate how it performed

#### Code Used
- [Week 5 Commands](https://github.com/DrakeData/MSDS434-Final/blob/main/code/msds434_week5_commands.txt)


### Week 6 - Managed ML Platforms
#### Video Recordings
[![Week 6 Video](https://cdn.loom.com/sessions/thumbnails/1f06e9292818475c82c867a853c54b7e-with-play.gif)](https://www.loom.com/share/1f06e9292818475c82c867a853c54b7e)

#### Objective
- Train a multi-class classification model on AutoML

#### My Learnings
- How to use AutoML within BigQuery
- AutomML does take time to run and might not provide the best model results

#### Code Used
- [Week 6 Commands](https://github.com/DrakeData/MSDS434-Final/blob/main/code/msds434_week6_commands.txt)
- [Week 6 Python Code](https://github.com/DrakeData/MSDS434-Final/blob/main/code/week6_code/file_cleanup.ipynb)


### Week 7 - Operationalizing ML Models
#### Video Recordings
[![Week 7 Video](https://cdn.loom.com/sessions/thumbnails/1db48100eb124e35aca3ff70dac58095-with-play.gif)](https://www.loom.com/share/1db48100eb124e35aca3ff70dac58095)

#### Objective
- Create a production and development environment
- Deploy your final project to both environments

#### My Learnings
- Different ways you can deploy, monitor, and maintain multiple environments
- Built a Staging and Production projects environment within GCP

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
- Go to 'Billing Export' within GCP and enable the different billing options you would like to export and connect to BigQuery table
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

### Week 10 - MVP
[![final_project_video](https://cdn.loom.com/sessions/thumbnails/3cb6e0d582fb4f98946dca54bd4f6cc1-with-play.gif)](https://www.loom.com/share/3cb6e0d582fb4f98946dca54bd4f6cc1)

See [GitHub Repository](https://github.com/DrakeData/MSDS434-Final_P2) for full coding documentation.

## Learnings from my classmates
I acquired numerous valuable skills related to cloud architecture from my peers, which enabled me to enhance my own projects. Among the key concepts I learned, containerizing environments using Docker emerged as one of the most significant. Docker provides a uniform platform for developers and system administrators to bundle, deploy, and operate applications. For the final project, I attempted to construct a Docker image to containerize my application, and my efforts proved successful. Additionally, my colleagues adeptly illustrated the importance of Software as a Service (SAAS) and the critical role of continuous integration (CI) systems in SAAS development and deployment, enabling developers to automate the testing and integration of new code changes into software applications. Finally, I discovered that traditional SQL servers update data tables more rapidly than BigQuery, as BigQuery has a restriction on the number of operations allowed per table.

## Final Thoughts
MSDS 434 Analytics Application Development proved to be an incredibly valuable course during my time at Northwestern University. As cloud computing continues to be an increasingly essential skill for career advancement, I anticipate looking back on my work in this course with fondness. Professor Ostrowski's guidance throughout the course was excellent, providing clear explanations for each week's assignments and remaining responsive to all my questions. In hindsight, I wish I had taken this course before MSDS 436 Analytics Systems Engineering, as they share similar content, but Professor Ostrowski focused on GCP and a little AWS, whereas MSDS 436 was more self-directed and heavily emphasized AWS. Nevertheless, I feel much more well-rounded now, having gained experience in two distinct cloud environments and developing a fundamental understanding of how to leverage cloud computing resources.

My big takeaways from this class include the following:
- Learned how to stop billing completely by disabling your billing account to your project.
- The ability to use machine learning within BigQuery is not only powerful but also lowers the barrier of entry as you only need to know how to use SQL to run models.
- GitHub Actions is a cool resource to use for continuous integration and continuous delivery.
- There isn’t a set way you should or have to setup your cloud environments. There are several different tooling options that will help you build what you are looking to deploy and it’s good to know the pros and cons of each one to determine what fits your project's needs the best.
- Setting up building alerts and monitoring is a great way to make sure you stay within your budget and minimize the fear of running up a large bill on your credit card.

## Repository Information
Created by: [Nicholas Drake](https://github.com/DrakeData)

Create date: 01/03/2023
