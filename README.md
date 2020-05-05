[![CircleCI](https://circleci.com/gh/MigzRuiz/Udacity-Project-4.svg?style=svg)](https://circleci.com/gh/MigzRuiz/Udacity-Project-4)

## Project Summary

In this project, I applied the skills you have acquired in this Cloud Devops Course to operationalize a Machine Learning Microservice API. 

The python application I'm containerizing is a pre-trained, `sklearn` model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on. You can read more about the data, which was initially taken from Kaggle, on [the data source site](https://www.kaggle.com/c/boston-housing). 

The `app.py` serves out predictions (inference) about housing prices through API calls. This project could be extended to any pre-trained machine learning model, such as those for image recognition and data labeling.

Instructions for running the apping using either Docker or Kubernetes are found below.

### Project Setup
* Clone the project
* Create a virtualenv and activate it.
* python3 -m venv ~/.devops
* source ~/.devops/bin/activate
* make install

### Project Tasks

* To run the app in docker, run the script ./run_docker.sh
* To run the app in Kubernetes, you must have minikube installed. Run minikube start then run the script ./run_kubernetes.sh

### Kubernetes Steps

* Setup and Configure Docker locally
* Setup and Configure Kubernetes locally
* Create Flask app in Container
* Run via kubectl
