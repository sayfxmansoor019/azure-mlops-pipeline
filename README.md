# Azure MLOps Pipeline

## Problem Statement

Deploying machine learning models into production often requires multiple manual steps, making deployments difficult to scale, monitor, and maintain. Organizations need reliable workflows for packaging, validating, deploying, and serving machine learning models across environments.

## Solution

This project demonstrates an end-to-end MLOps workflow built on Microsoft Azure. The system automates model deployment through CI/CD pipelines and serves predictions through scalable cloud-hosted inference endpoints.

Using Azure Machine Learning, Azure Pipelines, Azure Kubernetes Service (AKS), Flask, and Python, the platform showcases production-ready deployment practices for machine learning applications.

## Architecture

Model Training
      ->
Azure ML Workspace
      ->
Model Registration
      ->
CI/CD Pipeline (Azure Pipelines)
      ->
Containerization
      ->
AKS Deployment
      ->
REST Endpoint
      ->
Prediction Requests
