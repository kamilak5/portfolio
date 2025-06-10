# Half-Marathon Time Predictor – End-to-End ML App with GPT-4 Integration


# Project description 

 Developed a machine learning application that predicts half-marathon finish times based on user demographics and 5K race performance, using both structured data and natural-language inputs.

- Performed exploratory data analysis (EDA), feature engineering, and preprocessing on real-world race datasets
 - Trained regression models on 2023 race data and evaluated performance on a 2024 event dataset, ensuring temporal generalization. Selected Lasso for its balance of accuracy and interpretability.
 - Integrated GPT-4 to convert unstructured text input into structured features (via JSON parsing and chat completions)
 - Deployed the model in a user-friendly Streamlit app hosted on DigitalOcean
 - Implemented real-time monitoring of model and LLM performance with Langfuse
 - Ensured secure handling of API keys and configurations using environment variables

## This project highlights a complete data science pipeline: from data exploration and modeling to deployment, LLM integration, and production monitoring.

---

## Project Summary
This project delivers a predictive web application that estimates half-marathon finish times based on runners’ personal, physiological, and training data. Beyond raw prediction, it also integrates GPT-4 to generate personalized, human-like training advice and motivational messages tailored to the user’s performance level.

---

## Problem
Casual runners often lack data-driven guidance when preparing for future races. Most online predictors rely on outdated heuristics. This project used historical race data (2023) to predict performance in a future event (2024), simulating real-life race planning.

---

## My Role
I led the entire pipeline - from data preparation to live deployment. My contributions included:

- Designing the data workflow (EDA, preprocessing, feature engineering)
- Training and evaluating regression models (selected Lasso for interpretability)
- Integrating GPT-4 to parse user-written text into structured input features
- Building the frontend in Streamlit and deploying on DigitalOcean
- Implementing real-time monitoring of both model and GPT-4 outputs with Langfuse
- Ensuring secure API handling via environment configs

---

## Tools & Technologies
Python, pandas, Streamlit, OpenAI API (GPT-4), matplotlib, PyCaret

---

## Outcome 
Delivered a fully functional web application predicting half-marathon finish times based on structured and natural-language input.
Achieved accurate, interpretable predictions when tested on unseen 2024 data, validating the model’s generalization capability across race events.
Demonstrated ability to combine machine learning and generative AI to solve a real-world, user-facing problem

---

## Limitations & Future Work

- **Lack of live feedback loop**: The current app does not incorporate feedback from users (e.g. whether they met predicted time). This limits opportunities for model retraining and continuous improvement.
- **Single-race structure**: The current model was trained on a specific 2023 race dataset and evaluated on the corresponding 2024 event. While this simulates realistic forecasting, broader generalization (across locations, seasons, race types) would require multi-source data.

# [Go to the app](https://coral-app-2chue.ondigitalocean.app/)















