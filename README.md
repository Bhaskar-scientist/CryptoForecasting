# CryptoForecasting

## Overview
CryptoForecasting is a web-based cryptocurrency price prediction system integrating multiple machine learning models, including LSTM, SVR, Decision Tree, and Linear Regression. The project leverages real-time and historical data to forecast crypto price movements with high accuracy.

## Features
- **Multi-Model Prediction**: Implements LSTM, SVR, Decision Tree, and Linear Regression models for precise forecasting.
- **Real-Time Market Tracking**: Fetches live data using Yahoo Finance for up-to-date predictions.
- **Data Analysis & Visualization**: Processes over 5 million historical price data points with PostgreSQL, Pandas, and NumPy.
- **Performance Optimization**: Achieved an RMSE of 1.12 and 88% accuracy by refining feature selection and data scaling.
- **Interactive Dashboard**: Developed using Streamlit to analyze trends, compare models, and export data.

## Technologies Used
- **Programming Language**: Python
- **Machine Learning**: TensorFlow, scikit-learn
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib, Plotly, Streamlit
- **Database**: PostgreSQL
- **Data Source**: Yahoo Finance

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- PostgreSQL
- Required Python libraries (install via `requirements.txt`)

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/CryptoForecasting.git
   cd CryptoForecasting
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```sh
   streamlit run ⚡Forecasting.py
   ```

## Usage
1. Select a cryptocurrency from the sidebar.
2. View live market statistics and historical trends.
3. Compare price predictions across different ML models.
4. Download historical data for further analysis.

## Contribution
Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License.

---

Feel free to update this README with your actual GitHub repository link and additional details!

