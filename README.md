**Overview**
This project predicts the Wholesale Price Index (WPI) for vegetables in India, using a hybrid CEEMDAN-VMD-LSTM model. The approach leverages Complete Ensemble Empirical Mode Decomposition with Adaptive Noise (CEEMDAN) and Variational Mode Decomposition (VMD) to decompose the time series data, which is then fed into an LSTM model for accurate forecasting. These forecasts assist in resource management, policy decisions, and market strategies to enhance food security.

**Data Source**
Wholesale Price Index for Vegetables (2013-2023): Data sourced from the Office of the Economic Advisor, Ministry of Commerce, Government of India https://eaindustry.nic.in/

**Model Summary**
The model decomposes the time series data with CEEMDAN and VMD, then applies an LSTM network to capture time-dependent patterns in the decomposed signals, achieving high accuracy with metrics like:

**RMSE: 9.14
MAPE: 3.26%
MAD: 7.31
ME: 3.42**
