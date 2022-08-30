[![CircleCI](https://dl.circleci.com/status-badge/img/gh/taiwoadeleke/udacity_kubectl_Ml_Microservice_project/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/taiwoadeleke/udacity_kubectl_Ml_Microservice_project/tree/main)

## Project Overview

Deployment of a containerized Python flask application to serve out predictions (inference) about housing prices through API calls. It uses a a pre-trained, sklearn model that has been trained to predict housing prices in Boston according to several features.

### Project Procedure

Your project goal is to operationalize this working, machine learning microservice using [kubernetes](https://kubernetes.io/), which is an open-source system for automating the management of containerized applications. In this project you will:
* Tested code using linting
* Completed a Dockerfile to containerize this application
* Deployed containerized application using Docker and made a prediction
* Improved the log statements in the source code for the application
* Configured Kubernetes and created a Kubernetes cluster
* Deployed a container using Kubernetes and made a prediction
* Uploaded a complete Github repo with CircleCI to indicate that the code has been tested



##Getting Started

---

## Setup the Environment

* Create a virtualenv with Python 3.7 and activate it.  
```bash
python3 -m pip install --user virtualenv
# You should have Python 3.7 available in your host. 
# Check the Python path using `which python3`
# Use a command similar to this one:
python3 -m virtualenv --python=<path-to-Python3.7> .devops
source .devops/bin/activate
```
* Run `make install` to install the necessary dependencies

### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

### Kubernetes Steps

* Setup and Configure Docker locally
* Setup and Configure Kubernetes locally
* Create Flask app in Container
* Run via kubectl
