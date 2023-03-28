# CICD - React Web App k8s Deployment - Joey Geofrey

## Build Status:
[![CircleCI](https://dl.circleci.com/status-badge/img/gh/joeygeofrey/CICD-CircleCI-k8s-capstone-project/tree/master.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/joeygeofrey/CICD-CircleCI-k8s-capstone-project/tree/master)

## Project Scope:

The main goal of this capstone project is to demonstrate proficiency in the skills and knowledge acquired throughout the Cloud DevOps Nanodegree program.

I will be operationalizing a fully functional and efficient Continuous Integration and Continuous Deployment (CI/CD) pipeline for friendbook - a social media web application, developed in React. This project incorporates various technologies including: CircleCI for the CI/CD pipeline, Nginx for the application delivery, Docker for containerization, and Amazon EKS and CloudFormation for the managed Kubernetes cluster. 

Upon successful completion of the Continuous Integration, Continuous Deployment will be set up by pushing the newly built Docker container(s) to the Docker repository and deploying them to a Kubernetes cluster.

## Project Screenshots:

#### CircleCI Deployment Pipeline - 01/07
![An image of the CircleCI Deployment Piepeline](https://github.com/joeygeofrey/CICD-k8s-capstone-project/blob/master/screenshots/CircleCIPipeline.png)

#### CircleCI/Hadolint - Dockerfile Lint Error - 02/07
![An image of the CircleCI dockerfile lint job failure](https://github.com/joeygeofrey/CICD-k8s-capstone-project/blob/master/screenshots/LintError.png)

#### CircleCI/Hadolint - Dockerfile Lint Error Fix - 03/07
![An image of the CircleCI dockerfile lint job success](https://github.com/joeygeofrey/CICD-k8s-capstone-project/blob/master/screenshots/LintErrorFixed.png)

#### CircleCI/EKS - K8s Deployment - 04/07
![An image of the CircleCI EKS deployment](https://github.com/joeygeofrey/CICD-k8s-capstone-project/blob/master/screenshots/Deployments.png)

#### AWS - EC2 Node Deployments - 05/07
![An image of the Amazon EC2 Page](https://github.com/joeygeofrey/CICD-k8s-capstone-project/blob/master/screenshots/AWSEC2.png)

#### AWS - Load Balancer - 06/07
![An image of the Amazon Load Balancer configuration](https://github.com/joeygeofrey/CICD-k8s-capstone-project/blob/master/screenshots/LoadBalancer.png)

#### Live application - 07/07
![A GIF media of the live application](https://github.com/joeygeofrey/CICD-k8s-capstone-project/blob/master/screenshots/App.gif)

## Project Links:

GitHub Repo: https://github.com/joeygeofrey/CICD-CircleCI-k8s-capstone-project
<br>
Docker Hub Repo: https://hub.docker.com/r/joeygeof/friendbook/tags
