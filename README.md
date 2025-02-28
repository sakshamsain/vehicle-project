# Vehicle Insurance Prediction Project

## Overview

The Vehicle Insurance Prediction Project is an MLOps application designed to predict whether a vehicle owner will purchase insurance. It leverages machine learning models to analyze various features related to the vehicle and its owner. The project includes a web interface for user interaction and a backend pipeline for data processing and model management.

## Project Structure

- **src/**: Contains the core source code for the project.
  - **entity/**: Defines configuration entities for different stages of the ML pipeline.
  - **constants/**: Holds constant values used throughout the project.
  - **pipeline/**: Manages the execution of the ML pipeline stages.
  - **utils/**: Utility functions for data processing and model handling.

- **templates/**: HTML templates for the web interface.
- **static/**: Static files such as CSS for styling the web interface.
- **data/**: Directory for storing raw and processed data.
- **models/**: Directory for storing trained models.

## Key Components

- **Data Ingestion**: Collects and stores raw data for training and testing.
- **Data Validation**: Ensures the quality and integrity of the data.
- **Data Transformation**: Prepares data for model training by transforming it into suitable formats.
- **Model Training**: Trains machine learning models to predict vehicle insurance requirements.
- **Model Evaluation**: Evaluates the performance of trained models.
- **Model Deployment**: Deploys the model to a cloud storage bucket for production use.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sakshamsain/vehicle-project.git
   cd vehicle-project
