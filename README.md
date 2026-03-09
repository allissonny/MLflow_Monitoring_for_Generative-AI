# MLflow Monitoring for Generative AI

This project demonstrates how to use **MLflow** to track metrics and parameters for generative AI experiments.

The notebook integrates MLflow with the OpenAI API to log model usage statistics such as latency, token counts, and generation parameters during an interactive chat session.

---

## Project Overview

Experiment tracking is essential when working with machine learning models.  
MLflow allows developers to log and compare metrics across multiple runs.

In this notebook, MLflow is used to monitor:

- Model parameters
- Token usage
- Response latency
- Prompt and generation settings

This creates a reproducible experiment record that can be viewed through the MLflow UI.

---

## Technologies Used

- Python
- MLflow
- OpenAI API
- tiktoken
- Jupyter Notebook
- Colorama

---

## Features

### Experiment Tracking

MLflow logs:

- model name
- temperature
- token usage
- response latency
- experiment runs

### Token Monitoring

The notebook calculates the number of tokens used per request, helping monitor API usage and cost.

### Performance Metrics

Each prompt-response interaction records response time, enabling analysis of model latency.

---

## Workflow

1. Configure MLflow experiment tracking
2. Load OpenAI API client
3. Create a chat generation function
4. Log parameters and metrics to MLflow
5. Run an interactive chat loop
6. Visualize experiment results in the MLflow UI

---

## What I Learned

This project helped me understand:

- How MLflow tracks machine learning experiments
- How to log metrics for generative AI models
- The importance of monitoring token usage and latency
- How experiment tracking improves reproducibility

---

## Future Improvements

- Log prompts and outputs for deeper analysis
- Track cost estimates per request
- Compare multiple LLM models within MLflow
