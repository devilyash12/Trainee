# Stock Price Prediction

This repository contains a notebook for stock price prediction using various machine learning and time series models. The goal of the project is to build predictive models using historical stock data and evaluate their performance based on accuracy metrics.

## Models Implemented

The project includes the following models:
- **Linear Regression**
- **LSTM (Long Short-Term Memory)**
- **ARIMA (AutoRegressive Integrated Moving Average)**
- **SARIMA (Seasonal ARIMA)**
- **Prophet**
- **Chronos**

## Project Structure

- `Task.ipynb`: Jupyter notebook containing the code for data preprocessing, model training, and evaluation.
- `data/`: Directory where stock price data (historical data in CSV format) should be stored.
- `output/`: Directory where model results and predictions are saved.

## Prerequisites

To run the notebook, you'll need to have the following installed:

- Python 3.x
- Jupyter Notebook
- The following Python libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `scikit-learn`
  - `statsmodels`
  - `tensorflow` (for LSTM)
  - `fbprophet` (for Prophet model)
  - `pychronos` (for Chronos model)

You can install the necessary libraries by running:

```bash
pip install numpy pandas matplotlib scikit-learn statsmodels tensorflow fbprophet pychronos
```
## How to Run the Program
Clone this repository to your local machine:



```bash
Copy code
git clone https://github.com/your-username/your-repo-name.git
```
Navigate to the project directory:

```bash
Copy code
cd your-repo-name
```
Make sure you have Jupyter Notebook installed. If not, you can install it using:

```bash
Copy code
pip install jupyter
```
Launch the Jupyter Notebook:

```bash
Copy code
jupyter notebook
```
Open the Task.ipynb notebook from the Jupyter dashboard.

Follow the instructions in the notebook to run the different models. You can modify parameters, train models on different stock datasets, and evaluate their performance.

## Input Data
Place the historical stock price data in the data/ directory.
The dataset should be in CSV format, containing columns like Date, Open, High, Low, Close, and Volume.
## Output
The notebook will output visualizations of model predictions and save the results in the output/ directory.
Model performance metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R²) will also be displayed.
## Contributing
Feel free to fork the repository and make improvements. To contribute:

1. Fork the project.

```bash
Copy code
git checkout -b feature/your-feature
```
2. Commit your changes:

```bash
Copy code
git commit -m 'Add some feature'
```
3. Push to the branch:

```bash
Copy code
git push origin feature/your-feature
```
4. Open a pull request.