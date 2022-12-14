## TimeSeries Analysis
 <img align="center" width="800" height="600" src="https://github.com/Helal-Chowdhury/LSTM-PROPHET/blob/main/UIFIG.png">
 



### Introduction
A synthetic time-series datasets has created with the given trend and seasonality parameters. Bi-directional __LSTM__ neural network is used to predict the signal. 

### How to create project environment and install packages:

```bash
conda create --name <environment name> python=3.8
conda activate <environment name>
pip install -r requirements.txt
```
## RUN the App
To run the app, Go to __FRONEND__ folder and shoot this command:              
```bash
streamlit run LSTMTimeseries.py
```
## From Web UI 

 - Choose Number of Samples
 - Initial Sample index
 - Final Sample index
 
 Error metrics __MAE__, and __MSE__ will generate and plot will be shown for visualisation.

 <img align="center" width="1000" height="400" src="https://github.com/Helal-Chowdhury/LSTM-PROPHET/blob/main/Fig1.png">




