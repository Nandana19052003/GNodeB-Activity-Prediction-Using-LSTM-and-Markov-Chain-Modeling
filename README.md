# 5G Base Station Activity Prediction

This project predicts whether a 5G base station (gNodeB) is in an Idle or Active state using time-series analysis. It combines LSTM-based models, Markov Chains, and a language model (Google Gemini) for enhanced interpretability.

## Features

- LSTM with Attention for temporal pattern recognition  
- Markov Chains for modeling state transitions  
- Meta-classifier for combining model outputs  
- Gemini (LLM) integration for post-prediction analysis and explanation  

## Model Pipeline

1. LSTM-based models (Univariate, Multivariate, Bidirectional)  
2. LSTM + Attention for better interpretability  
3. Markov Chain model for transition detection  
4. Meta-classifier to combine predictions  
5. Gemini LLM to analyze and explain results  

## Results

- Hybrid LSTM + Markov model: 88.9% accuracy, F1 Score: 0.89  
- Gemini flagged possible data leakage in meta-classifier with perfect scores  
- Time-segmented and location-based insights for network operators  
