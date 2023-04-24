## Electricity Demand Forecasting

This collection of notebooks is devoted to forecasting of daily electricity demand in Alberta (Canada). We extensively use the DARTS library which is specifically created for time series forecasting tasks and has a variety of popular classical time series models as well as ML models implemented as wrappers. The data spans a time interval from 2000-01-01 to 2019-12-31.

For classical time series methods including TBATS, see [electricity_classical_daily.ipynb](electricity_classical_daily.ipynb).
For Deep Learning methods including TCN, N-BEATS, TFT, see [electricity_nn_daily.ipynb](electricity_nn_daily.ipynb).
For ensembling methods including LightGBM, XGB and Random Forest, see [electricity_RF_daily.ipynb](electricity_RF_daily.ipynb).