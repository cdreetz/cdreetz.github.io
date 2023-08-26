4m---
layout: page
title: Extended Resume
permalink: /resume/
---

## What do I do?
I like to work with data and learn about data based skills and tools.  Currently focused on language modeling and application development around custom conversational tools.




## Skills acquired over time and applied during projects or work

- <b>Programs and Languages</b> Python, R, SQL, SAS, SPSS
- <b>Packages</b> Pandas, Numpy, SciPy, Selenium, Ggplot, Caret, Tidyverse
- <b>DS Concepts </b> Linear/logistic regression, time series
- <b>DA Concepts </b> Data preprocessing, missing values, repeated values, converting variable types, column/row subsetting, visualizations
- <b>DA Tools </b> Automated data collection via webdriver
- <b> ML Tools</b> TensorFlow, PyTorch, Lightning, Transformers, Weights and Biases
- <b> NLP/LLM Tools</b> HuggingFace Transformers, Mosaic Composer, Langchain
- <b> NLP/LLM Concepts</b> Sentiment Analysis, Conversational Agents, Agent Tools, Custom Bots
- <b> CV Concepts</b> Object detection, object classification, object tracking
- <b> Cloud Services</b> GCP, TPUs, VertexAI; Azure products; Lambda Labs GPU Clusters 


## Skills in progress

- <b> ML Concepts</b> Production ML data pipeline

----



## Project experience

<b> Drive </b>
- Given 5 driving videos and the respective frame by frame labels of the camera positional pitch and yaw, develop a system to estimate the pitch and yaw of unseen driving videos
- Conduct initial analysis of data at hand, research pretrained models for camera positional estimation, determine candidate systems with and without DL
- Develop and tested non DL approach with a combination of OpenCV tools including Canny edge detection and Hough line transform to calculate pitch and yaw with the vanishing point to extrinsic and intrinsic matrix conversions
- Train a CNNLSTM on labeled videos, reaching a <0.1 MSE on the validation set
- Perform CNNLSTM training on an A600 Lambda Labs Cloud GPU due to local device limitations


<b> Google TPU Research Program </b>
- Having limited compute resources, and wanting to experiment with the GCP platform, applied for and was granted access to the Google TPU Research Program 
- Deployed Google VM instances for downloading large data to Goolge Storage including the >100GB ImageNet dataset
- Experimented with training various large computer vision models with both TPUs and GPUs
- Collaborated with other HuggingFace contributors on HuggingFace Trainer and Accelerate integration for Google TPUs 

<b> Useful Score </b> 
- A straightforward and non opinionated way for indivuduals to gauge their own set of skills or the curriculum of a univerity program they may be interested in.  The scores merely being the importance and relevance of these skills compared directly to the typical requirements in the current job market
- Starting with a Selenium webscraper that is the backbone of the application and is how data is collected to be able to measure scores.  It was developed due to Google job posts not being easily parsed with things like BeautifulSoup.  The scraper searches certain roles and companies on Google while collecting a number of the posts on Google including the jobs id, role, company, and full description.
- All of which initially kept in a MySQL db, then a Mongo db, and finally a Postgresql db due to its integration with Heroku
- Both the API and front end were developed with Flask
- Initially deployed with Heroku
- TODO: Convert the Flask app to something that can be deployed with Vercel, Nextjs maybe

<b> Lightning </b> 
- Learning project on Lightning AI or PyTorch Lightning, a ML framework that speeds up typical ML workflows by eliminating the need to write the typical boiler plate ML code
- Done in parallel while learning common deep learning vision models, including ResNet, VGG, and DeepNet
- Monitored model training times and loss with Tensorboard
- Uploaded all trained models and tensorboard logs to my HuggingFace Hub

<b> DataSci GPT </b> 
- Language model trained specifically on data science related code
- The dataset was a subset of The Stack, one of the largest and best code datasets for language models, filtered for key words down to about 6% its original size
- Done with various HuggingFace libraries including Transformers, and their Auto Tokenizer and Dataloader.
- Trained on A6000 GPU provided by Lambda Labs


## Work experience

<b> Business Intelligence Developer - iGrad </b>
- Complete end to end data projects with Python, from data acquisition, preprocessing, analysis, modeling, and developing tools with both custom and pretrained models
- Deployed open source NLP machine learning models to create systems for projects including sentiment analysis and machine translation
- Query from our datawarehouse or othe data sources with SQL/TSQL/KQL
- Employ Azure products including Azure Data Factory, Pipelines, Cognitive Services, and Azure OpenAI
- Utlize Microsoft Power BI for creating reports and dashboards to present key data and analysis

## Open source

<b> HuggingFace </b>
  - Contribute needed documentation additions and fixes.  As well as contribute key datasets for common tasks, and add new models to the Hub

<b> Flyte - SciPy 2023</b> 
  - Worked alongside key maintainers at SciPy 2023 Conference Sprint Days.  Contributed a new plugin by integrating the model analyzing feature of Weight Watchers into the Flyte platform.


## Recent project work
(July 2023) Over the past few months I have focused on developing LLM based tools both for myself while exploring developing for broad use.  I have also spend some time on widening my ML skills which meant doing some CV learning and projects.  One project consisted of a self driving challenge where I trained a model to predict the pitch and yaw of the camera of an unlabeled video.  Another was a project that consisted of a hand tracking tool where using my laptops camera I could show my hand and 20 different points of my hand were tracked and labeled.  I also trained a 120M parameter GPT-2 model with A100s hosted by Lambda Labs which cost $20 and 20 hours to train (A100's on Lambda are about $1.10 an hour)


(Feb 2023) The most recent work I have been doing is from my UsefulScore repository.  Initirally it was an attempt to learn and apply NLP methods, specifically with Python's Spacy package.  Over time it became more of a learning experience for me on using Selenium, on object oriented code, on HTML/CSS and XPATH direction, and on how to best organize a Github repository for a end to end data pipeline that creates a usable interface from the scraped data.
