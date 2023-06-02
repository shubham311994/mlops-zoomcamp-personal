# MLOps Zoomcamp

Our MLOps Zoomcamp course

- Start watching course videos! [Course playlist](https://www.youtube.com/playlist?list=PL3MmuxUbc_hIUISrluw_A7wDSmfOhErJK)

## Taking the course

### Self-paced mode

All the materials of the course are freely available, so that you
can take the course at your own pace

* Follow the suggested syllabus (see below) week by week
* You don't need to fill in the registration form. Just start watching the videos and join Slack
* Check [FAQ](https://docs.google.com/document/d/12TlBfhIiKtyBv8RnsoJR6F72bkPDGEvPOItJIxaEzE0/edit) if you have problems
* If you can't find a solution to your problem in FAQ, ask for help in Slack

## Overview

### Objective

Teach practical aspects of productionizing ML services — from training and experimenting to model deployment and monitoring.

### Target audience

Data scientists and ML engineers. Also software engineers and data engineers interested in learning about putting ML in production.

### Pre-requisites

* Python
* Docker
* Being comfortable with command line 
* Prior exposure to machine learning (at work or from other courses, e.g. from [ML Zoomcamp](https://github.com/alexeygrigorev/mlbookcamp-code/tree/master/course-zoomcamp))
* Prior programming experience (at least 1+ year)



### Asking for help in Slack

The best way to get support is to use [DataTalks.Club's Slack](https://datatalks.club/slack.html). Join the [`#course-mlops-zoomcamp`](https://app.slack.com/client/T01ATQK62F8/C02R98X7DS9) channel.

To make discussions in Slack more organized:

* Follow [these recommendations](asking-questions.md) when asking for help
* Read the [DataTalks.Club community guidelines](https://datatalks.club/slack/guidelines.html)


## Syllabus

### [Module 1: Introduction](01-intro)

* What is MLOps
* MLOps maturity model
* Running example: NY Taxi trips dataset
* Why do we need MLOps
* Course overview
* Environment preparation
* Homework

[More details](01-intro)

### [Module 2: Experiment tracking and model management](02-experiment-tracking)

* Experiment tracking intro
* Getting started with MLflow
* Experiment tracking with MLflow
* Saving and loading models with MLflow
* Model registry
* MLflow in practice
* Homework

[More details](02-experiment-tracking)

[**Weights and biases workshop**](cohorts/2023/02-experiment-tracking/wandb.md) 


### [Module 3: Orchestration and ML Pipelines](03-orchestration)

* Workflow orchestration
* Prefect 2.0
* Turning a notebook into a pipeline
* Deployment of Prefect flow
* Homework

[More details](03-orchestration)


### [Module 4: Model Deployment](04-deployment)

* Three ways of model deployment: Online (web and streaming) and offline (batch)
* Web service: model deployment with Flask
* Streaming: consuming events with AWS Kinesis and Lambda
* Batch: scoring data offline
* Homework

[More details](04-deployment)


### [Module 5: Model Monitoring](05-monitoring)

* Monitoring ML-based services
* Monitoring web services with Prometheus, Evidently, and Grafana
* Monitoring batch jobs with Prefect, MongoDB, and Evidently

[More details](05-monitoring)


### [Module 6: Best Practices](06-best-practices)

* Testing: unit, integration
* Python: linting and formatting
* Pre-commit hooks and makefiles
* CI/CD (GitHub Actions)
* Infrastructure as code (Terraform)
* Homework

[More details](06-best-practices)


### [Project](07-project/)

* End-to-end project with all the things above

[More details](07-project/)


## Other courses from DataTalks.Club:

- [Machine Learning Zoomcamp - free 4-month course about ML Engineering](https://github.com/alexeygrigorev/mlbookcamp-code/tree/master/course-zoomcamp)
- [Data Engineering Zoomcamp - free 9-week course about Data Engineering](https://github.com/DataTalksClub/data-engineering-zoomcamp/)
