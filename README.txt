READ ME

Folder contains all data and code necessary to reproduce models and figures.

1)Data Extraction - takes code from DEFRA site, merges with data from folder 'traffic data'

2) Exploratory Data Analysis

3) LSTM 
	- Variable combination traces = 'LSTM_variable_plot.ipynb'
	- Code for hyper parameter grid search = 'LSTM_GridSearch.ipynb'
	- Code for comparison of rolling and update algorithms ='LSTM_extending_forcasts.ipynb'

4) LSTM-CNN
	- Variable combination traces = 'LSTM_CNN_variable_plot.ipynb'
	- Code for hyper parameter grid search = 'LSTM_CNN_GridSearch.ipynb'

5) grid_search_results contains
	- csv files relating to hyperparameter and network topology grid search 
	- code for visualisations.
	- results from extending forecasts + visualisations 

6) Prophet.ipynb contains all code use for Facebook's Prophet model
	- Code for visualization of variable combinations

7) model_comparison.ipynb contains code which compares LSTM, CNN_LSTM and Prophet hourly NO2 distributions. 
