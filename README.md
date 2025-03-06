# AI Driven Investor Recommendation Market Prediction-System

This project demonstrates an end-to-end AI system for investor recommendations and market predictions using synthetic data. It integrates traditional predictive analytics with advanced natural language processing using a Large Language Model. The project is designed and implemented in Python.

## Table of Contents

- [Overview](#overview)
- [Project Components](#project-components)
- [Usage](#usage)
- [Future Work](#future-work)

## Overview

The project simulates a fintech application by:
- Generating synthetic stock price data using Geometric Brownian Motion and computing technical indicators.
- Creating synthetic financial news headlines to mimic market sentiment.
- Leveraging an LLM for advanced sentiment analysis of the synthetic news.
- Producing synthetic investor profiles.
- Integrating these components into a recommendation engine that provides investment advice based on market trends, news sentiment, and individual investor risk profiles.

## Project Components

1. **Synthetic Financial Data**  
   - Simulates stock prices over a trading year using GBM.
   - Computes a 20-day Simple Moving Average (SMA) to indicate market trends.

2. **Synthetic News Headlines**  
   - Generates financial news headlines using predefined templates.
   - Mimics various market sentiments (positive, negative, neutral).

3. **Falcon LLM Integration for Sentiment Analysis**  
   - Utilizes an LLM model from Hugging Face to analyze news headline sentiment.
   - Interprets sentiment as Positive, Negative, or Neutral.

4. **Synthetic Investor Profiles**  
   - Creates dummy investor profiles with attributes such as Age, Risk Tolerance, and Investment Horizon.

5. **Recommendation Engine**  
   - Combines market indicators, sentiment analysis, and investor profiles.
   - Outputs investment recommendations such as "Aggressive Buy", "Sell / Hold", or "Hold".
  


## Usage

- **Synthetic Data Generation:**  
  Execute the notebook cells to generate synthetic stock prices, news headlines, and investor profiles.

- **Sentiment Analysis with the LLM:**  
  Run the LLM's sentiemt analysis function which is used to determine the sentiment of each synthetic news headline. Adjust the prompt as needed for your use case.

- **Investment Recommendation:**  
  Use the recommendation engine that combines market trends, sentiment scores, and investor profiles to generate personalized investment recommendations.

- **Visualization:**  
  Visualize synthetic stock prices and computed indicators through built-in plotting functions to better understand market trends.

## Future Work

- **Real Data Integration:**  
  Enhance the pipeline by integrating real financial data from APIs to replace or supplement the synthetic data.

- **Enhanced Sentiment Analysis:**  
  Fine-tune the LLM or experiment with alternative prompts.

- **Full-Stack Deployment:**  
  Develop a web application using frameworks like Flask or Streamlit to deploy the solution for interactive analysis and real-time recommendations.






