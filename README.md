# About

- The increase in the number of RSOs (Resident Space Objects) indirectly increases the risk of collision of LEO Satellites.
- Here's a snippet depicting the scale of the problem (Credits to [LeoLabs](https://leolabs.space)):
![Untitled (1)](https://user-images.githubusercontent.com/61016383/148759217-f5cd864b-0b15-4f69-861e-46b4011c60a0.gif)
- The important issue here is the reliable and accurate orbit tracking of satellites to prevent a catastrophic event like a Kessler Syndrom.
- This project is an experiment on predicting and forecasting the position of a satellite orbitting earth using Deep Learning (LSTM) and standard statistical approach (SARIMAX).
- This is a Time Series Forecasting problem where the LSTM is used predict the x-coordinate of a satellite and SARIMAX forecasts the future postions.
- Below are the conclusions:
    - The data
      -![Screenshot (857)](https://user-images.githubusercontent.com/61016383/148768188-d9e9a20d-d15c-4dd0-9936-829ab6ef2b0c.png)
    - LSTM results
      -![Screenshot (856)](https://user-images.githubusercontent.com/61016383/148768262-bc465793-9f91-4e31-92db-b2d584c9960c.png)
    - SARIMAX results
      -![Screenshot (859)](https://user-images.githubusercontent.com/61016383/148772471-f83d9074-d19c-4936-b033-c1527fe2956f.png)


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

