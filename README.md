# Rainfall_Project 
This project uses deep learning to predict the next day's rainfall based on sequences of past daily rainfall images across India.
It is part of an ongoing research work for my M.Tech thesis and currently under review for publication. 

# Project Overview

- The model looks at daily rainfall patterns from previous days (e.g., 7, 15, or 30 days) to predict rainfall for the next day.
- The data used is in the form of grayscale images (129x135 pixels), covering rainfall over India from 2013 to 2023.
- This can be useful in early-stage weather forecasting and climate-related research.

# Model Summary

The architecture is a **CNN-LSTM hybrid model**:
- CNN layers learn spatial features from rainfall images.
- LSTM layers learn how rainfall patterns change over time (temporal sequences).
- The model predicts one grayscale image for the next day. 

# Tools & Libraries

- Python
- TensorFlow / Keras
- NumPy
- PIL
- scikit-learn
