

---

# Stock Market Prediction Project

## Overview

This project focuses on predicting stock market prices using a deep learning model based on historical stock data. The code is implemented in Python using TensorFlow and pandas libraries.

## Project Structure

- **`stock_market_prediction.ipynb`**: Jupyter Notebook containing the code for the project.
- **`AAPL.csv`**: CSV file containing historical stock data for the Apple Inc. (AAPL) stock.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/TejParmar10/stock_market_prediction.git
   cd stock_market_prediction
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook:**
   Open the `stock_market_prediction.ipynb` notebook in Jupyter and run each cell to train the model and make predictions.

## Data Source

The historical stock data is fetched using the Tiingo API. You can obtain your API key [here](https://api.tiingo.com/).

## Model Architecture

The neural network model used for stock prediction consists of multiple LSTM layers followed by a Dense output layer. The model is trained using the Adam optimizer and Mean Squared Error (MSE) loss function.

## Results

The model is trained and validated on historical stock data, and the predictions are visualized alongside the actual stock prices using matplotlib.

## Future Work

- Fine-tune model parameters for improved performance.
- Explore the use of different deep learning architectures.
- Experiment with additional features or technical indicators.

## Acknowledgments

- This project is for educational purposes and is not financial advice.
- Special thanks to Tiingo for providing financial market data through their API.

## License

This project is licensed under the [MIT License](LICENSE).

---
