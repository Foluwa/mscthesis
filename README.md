## Project Title: Comparative Analysis of ARIMA and LSTM Models for Forecasting Stock Closing Prices

### Project Overview
This project provides a comparative analysis of two time series forecasting models: ARIMA (AutoRegressive Integrated Moving Average) and LSTM (Long Short-Term Memory). The objective is to forecast stock closing prices and determine which model performs better under various conditions. The project was implemented using Python and Jupyter Notebook, specifically in a Google Colab environment.

### Table of Contents
1. [Installation](#installation)
2. [Dataset](#dataset)
3. [Project Structure](#project-structure)
4. [How to Run](#how-to-run)
5. [Model Descriptions](#model-descriptions)
6. [Results and Evaluation](#results-and-evaluation)
7. [Contact](#contact)

### Installation
To run the code, you need to have access to Google Colab. All the necessary libraries are pre-installed in the Google Colab environment, but if you are running the code locally, you will need to install the following packages:

- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- sklearn
- tensorflow
- keras
- yfinance 
- pmdarima

You can install these packages using pip:

```bash
pip install pandas numpy matplotlib seaborn statsmodels scikit-learn tensorflow keras yfinance pmdarima
```

### Dataset
The dataset used for this project consists of historical stock prices. The data includes the date, open, high, low, close, and volume for the TESLA stock. This data was gotten from [Yahoo Finance](https://finance.yahoo.com/quote/TSLA/history/?period1=1277818200&period2=1594339200&interval=1d&filter=history&frequency=1d).

### Project Structure
The project is organized as follows:

- **MSCTHESIS.ipynb**: The main Jupyter Notebook containing all the code, analysis, and results.
- **datasets/**: Directory containing the dataset (optional if running on Google Colab with dataset loaded directly from online sources).

### How to Run

1. **Open Google Colab**: Go to [Google Colab](https://colab.research.google.com/drive/1_-fuezmOwgNwPwwAgJX-pMDn5BA-HMvW).

2. **Upload the Notebook**:
   - Click on "File" -> "Upload notebook".
   - Select the `MSCTHESIS.ipynb` file from your computer.

3. **Run the Notebook**:
   - After the notebook is uploaded, you can run the code cells sequentially by pressing `Shift + Enter` or clicking the "Run" button in the Colab interface.
   - The notebook is divided into sections:
     - The data loading and preprocessing
     - ARIMA model implementation
     - LSTM model implementation
     - Comparative analysis and evaluation
   - Each section should be run in order to reproduce the results.

4. **View Results**:
   - The results, including plots and performance metrics, will be displayed within the notebook cells.

### Model Descriptions

- **ARIMA Model**: The autoregressive integrated moving average (ARIMA) model merges autoregressive (AR) and moving average (MA) components with differencing to handle non-stationary data.

- **LSTM Model**: Long-short-term memory (LSTM) is a highly developed form of recurrent neural network architecture specifically designed to model temporal sequences and long-range dependencies more effectively than traditional recurrent neural networks 

### Results and Evaluation
The notebook includes a detailed comparison of the ARIMA and LSTM models based on various evaluation metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), Root Mean Squared Error (RMSE) and Adjusted R-Squared. The results section highlights the strengths and weaknesses of each model in forecasting stock prices.

### Contact
You can reach me via [moronfoluwaakintola@gmail.com](mailto:moronfoluwaakintola@gmail.co)