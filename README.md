# About

- The increase in the number of RSOs (Resident Space Objects) indirectly increases the risk of collision of LEO Satellites.

- Here's a snippet depicting the scale of the problem (Credits to [LeoLabs](https://leolabs.space)):

https://user-images.githubusercontent.com/61016383/149488989-9c8c1ff4-a706-4e6c-8bc1-09574713bf3b.mp4

- The important issue here is the reliable and accurate orbit tracking of satellites to prevent a catastrophic event like the Kessler Syndrome.

- This project is an experiment on predicting and forecasting the position of a satellite orbiting earth using Deep Learning (LSTM).

- The LSTM model is trained on the data recorded over 18days and forecasts the trajectory for the next seven days. 

### The Satellite Trajectory

https://user-images.githubusercontent.com/61016383/149487305-6f9e43d6-35f5-4bc0-a4e0-f1e7c3c03895.mp4

### Forecasted Trajectory

https://user-images.githubusercontent.com/61016383/149499119-84a1d2d9-42d4-4d2a-ad47-a475bf6598d7.mp4
    
    
# Libraries Used:
- Tensorflow 2.x
- Keras
- Scikit Learn
- Python >= 3.7
- Numpy
- Statsmodels
- Matplotlib
- Pandas
- Pmdarima


# Data

- Here's the link to the dataset <https://www.kaggle.com/idawoodjee/predict-the-positions-and-speeds-of-600-satellites>

- The dataset from Kaggle contains information of 600 satellites. 
 
 ***This experiment is performed using data of a single satellite.***

