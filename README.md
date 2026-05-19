# A Machine Learning Approach to Predict Autism Spectrum Disorder

This project applies machine learning techniques to predict Autism Spectrum Disorder (ASD) traits using AQ-10 screening responses and related demographic/medical attributes.

The goal of the project is to design and implement a system that can help identify whether an individual may require a comprehensive autism assessment.

## Project Overview

Autism Spectrum Disorder is a neurodevelopmental condition that can affect communication, interaction, learning, and behavior. Early detection can help individuals receive support and intervention sooner.

This project uses machine learning models to analyze screening data and predict whether a person may show autism traits.

## Problem Statement

To design and implement a system that can efficiently detect Autism Spectrum Disorder using machine learning algorithms.

## Dataset

The project uses autism screening data collected from Kaggle/UCI-style datasets. The dataset includes AQ-10 screening questions and additional attributes such as:

- Age
- Gender
- Jaundice history
- Family history of ASD
- Person completing the screening test
- AQ-10 question responses

## Methodology

The project follows the CRISP-DM methodology:

- Business understanding
- Data understanding
- Data preparation
- Modeling
- Evaluation
- Deployment

## Machine Learning Models Used

Several classification models were trained and compared:

- Random Forest Classifier
- Support Vector Machine
- Logistic Regression
- AdaBoost Classifier

Based on model comparison, Random Forest was selected as the final model because it produced strong prediction performance.

## Deployment

The selected model was deployed using Flask as a web application.

The application allows users to enter AQ-10 responses and related attributes, then predicts whether the person may show autism traits.

Local application endpoint:

```text
http://127.0.0.1:5000/index
