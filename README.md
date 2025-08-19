## Overview
This project develops an AI-powered video title generation and optimization system that leverages machine learning and natural language processing (NLP) techniques to improve video engagement and click-through rates (CTR).

Using a dataset of nearly 5,000 YouTube videos from “5-Minute Crafts”, the project explores how linguistic features, structural patterns, and emotional tones in titles affect viewer behavior. The pipeline integrates data analysis, clustering, sentiment modeling, and LLM-based generation to provide optimized video titles.

## Key Features

- Exploratory Data Analysis (EDA): Examined distributions of metadata and textual attributes, uncovering patterns in length, structure, and style of titles.

- Clustering: Applied PCA + KMeans to group titles into five thematic clusters (e.g., life hacks, beauty, food, parenting).

- Sentiment Analysis: Built an LSTM model to capture emotional tone in titles, achieving low prediction error.

- CTR Prediction: Trained classification models (Logistic Regression, XGBoost, etc.) to predict title performance.

- Generative Optimization: Integrated clustering + sentiment with a Qwen2.5-0.5B LLM to generate and rank alternative titles, improving predicted CTR while maintaining semantic similarity.
