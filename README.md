# Turing DevOps Challenge - GitOps Kubernetes CD Pipelines

## Problem Statement
Build a complete automated deployments for multiple web apps residing in multiple repos into a single cluster with multiple nodes, each web app having a different URL so that public users can access the same. Adding Autoscaling to handle the unexpected load as that the cluster/system determines the load and scales up the web apps horizontally so that the system will be up and available irrespective of the unexpected load/traffic to the web apps.
A single monitoring tool to visualize and monitor the health and resource utilization of the cluster. 

## Technologies used
* GCP - Google Cloud Platform to host our applications
* GKE- Google Kubernetes Engine (Managed Kubernetes by Google Cloud) for container orchestration 
* Cloud Build - Automated Build tool for all kinds of applications
* Docker - To package and containerize the applications
* Github - Source repositories and collaboration.
* Prometheus - To scrape the metric data and monitor Kubernetes
* Grafana - To visualize the data and monitor the health of resources using the metrics queried from prometheus.

## Setup
    TODO
