# Getting Started with ML in Production Workshop

## Project Overview

This project deploys a machine learning sentiment analysis model as a FastAPI application.

## What the Model Predicts

The model predicts whether a given text sentiment is positive or negative.

## API Endpoints

### GET /health

Checks whether the API is running and whether the model is loaded.

### POST /predict

Accepts text and returns the predicted sentiment and confidence.

Example request:

```json
{
  "text": "I really loved this movie!"
}
