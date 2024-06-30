# 🎓 SMVITM Admission Prediction using ARIMA and LSTM Models

Welcome to our project on predicting SMVITM admissions using time series analysis with ARIMA and LSTM models. This project is a collaborative effort by our team to leverage the power of machine learning and statistical methods to forecast the number of college admissions.

## 🚀 Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Results](#results)
- [Team](#team)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## 📚 Introduction

Predicting college admissions is a critical task for educational institutions to manage resources and plan effectively. In this project, we have utilized two powerful models for time series forecasting:

1. **ARIMA (AutoRegressive Integrated Moving Average)**: A popular statistical method for time series analysis.
2. **LSTM (Long Short-Term Memory)**: A type of recurrent neural network well-suited for sequence prediction.

## 🏗 Project Structure

The project is organized as follows:

```
college-admission-prediction/
├── data/
│   ├── raw_data.csv
│   ├── processed_data.csv
├── notebooks/
│   ├── data_preprocessing.ipynb
│   ├── arima_model.ipynb
│   ├── lstm_model.ipynb
├── src/
│   ├── data_preprocessing.py
│   ├── arima_model.py
│   ├── lstm_model.py
├── results/
│   ├── arima_results.png
│   ├── lstm_results.png
├── README.md
├── requirements.txt
├── LICENSE
```

## ⚙️ Installation

To run this project, you'll need Python 3.x and the necessary packages listed in `requirements.txt`. You can install them using the following command:

```bash
pip install -r requirements.txt
```

## 🧰 Usage

1. **Data Preprocessing**: Run the data preprocessing script to clean and prepare the data.

```bash
python src/data_preprocessing.py
```

2. **Train ARIMA Model**: Train the ARIMA model using the preprocessed data.

```bash
python src/arima_model.py
```

3. **Train LSTM Model**: Train the LSTM model using the preprocessed data.

```bash
python src/lstm_model.py
```

## 🧠 Models

### ARIMA Model

The ARIMA model is a widely used statistical method for time series forecasting. It combines AutoRegression (AR), Integrated (I), and Moving Average (MA) components to predict future values based on past data.

### LSTM Model

The LSTM model is a type of recurrent neural network that can learn long-term dependencies in sequence data. It is particularly effective for time series forecasting due to its ability to retain information over long periods.

## 📈 Results

We have obtained promising results with both models. The ARIMA model provides a solid statistical approach, while the LSTM model leverages deep learning to capture complex patterns in the data. Below are the results of our models:

- **ARIMA Results**: ![ARIMA Results](results/arima_results.png)
- **LSTM Results**: ![LSTM Results](results/lstm_results.png)

## 👥 Team

- **Teammate 1**: [https://github.com/Omikar243]
- **Teammate 2**: [https://github.com/01Anu-sha]
- **Teammate 3**: [https://github.com/03shravya]
- **Teammate 4**: [https://github.com/Ramachandra-2k96]

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgements

We would like to thank our mentors and professors for their guidance and support throughout this project.
