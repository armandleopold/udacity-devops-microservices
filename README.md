[![CircleCI](https://circleci.com/gh/armandleopold/udacity-devops-microservices.svg?style=svg)](https://circleci.com/gh/armandleopold/udacity-devops-microservices)

## Project Overview

This project will give examples of running an app as a microservice in a kubernetes infrastructure.
Using best practices such as Containerization with Docker, orchestration with kubernetes, scripting with Makefile and bash files, and continuous deloyement with circleci.

## Run


## Setup the Environment

* Create a virtualenv and activate it
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


## Files

* *.sh : All the bash scripts to run the stack
* .circleci folder : CI/CD config
* Dockerfile : Container building file
* Makefile : scripting file
* app.py : the app
* outpu_files : examples of output from running the app
