# Getting Started with MLOps on Google Cloud

## A Beginner Pipeline Using Vertex AI & Kubeflow Pipelines (KFP)

This repository contains the Jupyter Notebook completed as part of the Coursera – Google Cloud: Getting Started with MLOps course.
The notebook demonstrates how to create, package, and execute a simple MLOps workflow using Vertex AI Pipelines and Kubeflow Pipelines (KFP).

## Project Overview

This project walks through the foundational steps required to operationalize an ML workflow on Google Cloud:

- Installing the required Google Cloud & MLOps SDKs

- Setting up environment variables and authentication

- Creating a custom Kubeflow component using Python

- Exporting the component to a reusable YAML file

- Loading the component back into a pipeline

- Preparing the pipeline for execution on Vertex AI

Although simple, this project illustrates the core concepts of component-based ML pipelines, enabling scalable and reproducible MLOps practices.

## Key Features

✔ Custom KFP Component

A Python function is converted into a portable component using:

@component(base_image="python:3.12", output_component_file="first-component.yaml")

✔ Component Loading

Demonstrates reuse by loading the generated component back into the pipeline.

✔ Vertex AI Integration (Preparation)

Configures the environment for running the pipeline on Google Cloud.

## Technologies Used
### Category:             Tools

Cloud:	                  Google Cloud Platform (GCP)

MLOps Platform:  	        Vertex AI Pipelines

Pipeline Orchestration:  	Kubeflow Pipelines (KFP v2)

Languages:               	Python

Notebook Environment:     JupyterLab

## Repository Structure
├── mlops_notebook.ipynb      # Jupyter Notebook from Coursera Lab
├── first-component.yaml      # Custom KFP Component Definition
└── README.md                 # Project Documentation

## Outputs Generated

A working KFP component YAML

Verified component loading

Pipeline foundation ready for Vertex AI execution

## License

This project is for learning and educational purposes only.
Subject to Coursera and Google Cloud platform terms.
