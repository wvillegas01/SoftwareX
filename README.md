# SoftwareX
Code-Data
==================================================== ======
Drought Forecasting Software
==================================================== ======

This software uses a LSTM (Long Short-Term Memory) model to predict the occurrence of droughts based on historical data on soil moisture, precipitation, temperature, humidity, and evaporation.

Requirements
----------
-Python 3.x
- Libraries needed:
     - panda
     -numpy
     -matplotlib
     - pickle
     -datetime
     -tensorflow
     -sklearn
     -prettytable

Facility
-----------
1. Clone the repository from GitHub: https://github.com/your_username/repo.git
2. Ensure you have Python 3.x installed on your system.
3. Install the necessary libraries by running the following command in your terminal: pip install pandas numpy matplotlib pickle tensorflow sklearn prettytable


Use
---
1. Put the historical data in a CSV file called `data_source.csv` and save it in the same directory as the script.
2. Run the script `drought_forecast.py` using the following command: python drought_forecast.py
3. The software will train the LSTM model using the training data and make predictions on the test data.
4. The model's results will be displayed in the console, including evaluation metrics (RMSE, MAE, R^2) and a summary table.
5. A `results.txt` file containing the evaluation metrics will be generated.
6. The trained LSTM model will be saved in the `lstm_model.h5` file, the data scaler object in `scaler.pkl`, the X feature scaler object in `X_scaler.pkl` and the data scaler object. target variable y in `y_scaler.pkl`.

Additionally, the software includes commented code to display results graphs and generate future projections. You can uncomment these sections according to your needs.

Enjoy using the drought forecasting software!

==================================================== ======
