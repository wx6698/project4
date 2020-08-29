# Template:
[![wx6698](https://circleci.com/gh/wx6698/project4.svg?style=svg)](https://app.circleci.com/pipelines/github/wx6698)

## Project Overview

In this project, I operationalize a Machine Learning Microservice API. 

I use a pre-trained, `sklearn` model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on. You can read more about the data, which was initially taken from Kaggle, on [the data source site](https://www.kaggle.com/c/boston-housing). This project tests your ability to operationalize a Python flask app—in a provided file, `app.py`—that serves out predictions (inference) about housing prices through API calls. This project could be extended to any pre-trained machine learning model, such as those for image recognition and data labeling.

### Instruction runing `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

### Files in github repo
1.Dockerfile: Docker defination files     
2.README.md: Project bref introduction
3.model_data: Foler where trained model data
4.requirements.txt: List of Python libraries need to install for the project    
5.run_kubernetes.sh: Run the App in Kubernetest
6.run_docker.sh: Run the App in Docker
7.upload_docker.sh: Upload the Docker container to Docker hub in order to be used by Kubernetes
8.Makefile: Install prerequesite, test and verify Dockerfile and python file is syntax correct
9.app.py: The App file
10.make_prediction.sh: Test the App run in Docker or Kubernetes
11.test.sh: Test the App run in local
12. output_txt_files: Saved output file from Docker and Kubernest

