[![CircleCI](https://circleci.com/gh/mahmuuud/project-ml-microservice-kubernetes.svg?style=svg)](https://circleci.com/pipelines/gh/mahmuuud/project-ml-microservice-kubernetes)


### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

## Project Files
* Makefile: is the main make file for the project to unify the essential commands for the project and make it more simple

* Requirements.txt: is the file containing the project dependencies

* run_docker.sh: is the script needed to run the app in Docker environment

* run_kubernetes.sh: is the script needed to deploy the app in kubernetes

* make_prediction.sh: is the script used to make a prediction

* kubernetes_out.rtf: is a sample text output for running the app in kubernetes and making a prediction

* Docker_out.rtf: is a sample text output for running the app and making a prediction inside a Docker container

* .circleci/config.yml: CircleCi pipeline configuration file.
