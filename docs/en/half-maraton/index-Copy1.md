# Half-Marathon Time Predictor – End-to-End ML App with GPT-4 Integration


# Project description 

 Developed a machine learning application that predicts half-marathon finish times based on user demographics and 5K race performance, using both structured data and natural-language inputs.

- Performed exploratory data analysis (EDA), feature engineering, and preprocessing on real-world race datasets
 - Trained and compared multiple regression models using PyCaret; selected Lasso for its strong performance and interpretability
 - Integrated GPT-4 to convert unstructured text input into structured features (via JSON parsing and chat completions)
 - Deployed the model in a user-friendly Streamlit app hosted on DigitalOcean
 - Implemented real-time monitoring of model and LLM performance with Langfuse
 - Ensured secure handling of API keys and configurations using environment variables

## This project highlights a complete data science pipeline: from data exploration and modeling to deployment, LLM integration, and production monitoring.


## Project Summary
This project delivers a predictive web application that estimates half-marathon finish times based on runners’ personal, physiological, and training data. Beyond raw prediction, it also integrates GPT-4 to generate personalized, human-like training advice and motivational messages tailored to the user’s performance level.

## Problem
Casual runners often lack data-driven guidance when preparing for races. Online calculators tend to oversimplify performance prediction and offer generic tips. I wanted to build a more intelligent tool that combines statistical modeling and LLM capabilities to give nuanced, helpful, and personalized output.

## My Role
Led the entire pipeline: data sourcing, cleaning, modeling, evaluation, deployment
Designed the user interface and experience
Integrated GPT-4 to generate customized textual outputs
Applied UX principles 
Workflow & Key Components
Data Processing
Modeling
Prompted GPT-4 with user profile and model output to:
deliver personalized time
detect anomalies 
Front-End Deployment

Built a clean, interactive UI using Streamlit.
Allowed real-time predictions and generated dynamic feedback.

## Tools & Technologies
Python, pandas, Streamlit, OpenAI API (GPT-4), matplotlib

## Outcome 
Delivered a fully functional web application predicting half-marathon finish times based on structured and natural-language input.
Achieved accurate, interpretable predictions using Lasso regression trained on real-world race data.
Demonstrated ability to combine machine learning and generative AI to solve a real-world, user-facing problem.

# [Go to the app](https://coral-app-2chue.ondigitalocean.app/)



# [Download notebook](assets/maraton_pred.ipynb)














