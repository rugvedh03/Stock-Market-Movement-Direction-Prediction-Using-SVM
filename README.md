# Stock-Market-Movement-Direction-Prediction-Using-SVM
Here is the text from your PDF:

Major Project – II (Review 1)

Presented By: M koushik rugvedh
Project Name: Stock Market Movement Direction Predictor using SVM

---

Contents

Project/Problem Identification

Introduction

Abstract

Project Analysis

Functionality

Requirement Analysis

Literature Review



---

Project/Problem Identification

Title

Stock Market Movement Direction Predictor

Problem

Stock markets are highly volatile.

Investors face difficulty in predicting price movements.

Manual prediction is unreliable.


Challenges

Noisy and complex data

Non-linear patterns

Time-series dependency


Solution

Use Machine Learning (SVM).

Predict whether the stock price will move UP or DOWN.



---

Introduction

Stock market prediction is widely used in finance. Stock prices depend on many hidden factors, making prediction difficult. Technical indicators help analyze market trends.

Problems

Large volume of data

Difficult to identify patterns manually


Approach

Use the Support Vector Machine (SVM) algorithm with technical indicators such as:

RSI (Relative Strength Index)

MACD (Moving Average Convergence Divergence)

Bollinger Bands



---

Abstract

This project predicts the next day's stock market direction using Machine Learning.

Dataset

Historical stock market data (Kaggle)


Features Used

RSI

MACD

Bollinger Bands

Moving Averages

Volume


Models Used

Linear SVM

RBF SVM


Evaluation Metrics

Accuracy

Precision

Recall



---

Project Analysis

The dataset consists of historical stock market time-series data, which is noisy and non-linear. Predicting stock movements is challenging due to market volatility and randomness.

Technical indicators such as RSI, MACD, Bollinger Bands, and Moving Averages are used to identify patterns related to trend, momentum, and volatility. These features improve prediction performance, although stock markets remain inherently unpredictable.

Dataset Contains

Open Price

High Price

Low Price

Close Price

Volume



---

Functionality

Input

Historical stock market data


Preprocessing

Data Cleaning

Normalization


Feature Engineering

RSI

MACD

Bollinger Bands


Models

Linear SVM

RBF SVM


Output

UP (1)

DOWN (0)


Pipeline

Input → Technical Indicators → SVM Model → Prediction → Evaluation


---

Requirement Analysis

Functional Requirements

Predict stock market direction.

Handle time-series data.

Provide accurate results.


Non-Functional Requirements

Fast processing

Scalable system

Easy visualization


Tools & Technologies

Python

Pandas

NumPy

Scikit-learn

TA (Technical Analysis) Library

Matplotlib



---

Literature Review

Study 1: SVM for Stock Prediction

Models: Linear SVM and RBF SVM

Result: RBF performs better but may overfit.


Study 2: Machine Learning in Financial Prediction

Models: Random Forest and SVM

Accuracy: Approximately 55%–65%


Study 3: Deep Learning Models

Model: LSTM

Better performance but more complex.



---

Conclusion

SVM can predict stock market direction.

RBF SVM captures non-linear patterns effectively.

Linear SVM provides more stable performance.


Reference

https://www.sciencedirect.com/science/article/pii/S1877050921009516
