# Crime Prediction using a CNN-LSTM Deep Learning Model

This repository contains a group project completed as part of the Deep Learning course in the M.Sc. Social and Economic Data Science program. The repository contains the data and notebook to run our proposed combined CNN+LSTM model to predict crime in Chicago. 
Running the full notebook, which consists of loading the data, cleaning, creating heatmaps, sequences, tranining and testing the model takes around 2 hours.

**Project Overview**
This project explores deep learning approaches for predicting weekly crime counts across Chicago districts by combining spatial, temporal, and socio-economic information.
We developed a hybrid CNN-LSTM architecture that integrates crime hotspot heatmaps with weather and census data to model spatiotemporal crime patterns.

**Data Sources**
- Chicago Crime Dataset (2001–2024)
- Community Data Snapshots (U.S. Census)
- Historical Weather API
After preprocessing, the final dataset consisted of more than 700,000 crime reports from 2021–2024.

**Methods**
- Python
- TensorFlow / Keras
- Convolutional Neural Networks (CNN)
- Long Short-Term Memory Networks (LSTM)
- Time-series forecasting
- Geospatial data processing
- Feature engineering
- Data normalization
- Model evaluation

**Key Steps**
- Combined crime, census, and weather datasets into a unified prediction pipeline.
- Generated weekly crime hotspot heatmaps for each district.
- Built a dual-input CNN-LSTM model combining image-based and tabular features.
- Trained and evaluated the model for district-level crime prediction.

**Results**
The model successfully learned spatial and temporal crime patterns and achieved stable convergence during training. While predictive performance leaves room for improvement, the project demonstrates the application of deep learning techniques to complex real-world spatiotemporal datasets.
