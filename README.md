# XRP Cryptocurrency Closing Price Prediction using LSTM Neural Network

This is the final project of a machine learning class that focuses on predicting the closing price of XRP, a popular cryptocurrency. The project uses a Long Short-Term Memory (LSTM) neural network, a form of Recurrent Neural Network (RNN) that is particularly well-suited to time series data. 

## Project Objective
The primary objective of this project is to forecast XRP cryptocurrency's closing prices using an LSTM model and evaluate its performance using various measures. The accurate price predictions can help individual and institutional investors in making informed investment decisions.

## Dataset and Preprocessing
The dataset contains daily XRP/USD prices from the past. It has options like Date, Open, High, Low, Close, and Volume. The data is separated into three sets: training, validation, and testing. Using a window of prior prices, the LSTM model predicts the closing price. To improve training efficiency, the input features are normalized using a zero-base normalization or a min-max normalization.

## Model Selection and Evaluation
To prevent overfitting, an LSTM model with 50 neurons is utilized, along with a dropout layer. The loss function is the mean squared error (MSE), and the Adam optimizer is used for training. The model's performance is evaluated using metrics such as mean absolute error (MAE), mean squared error (MSE), and R-squared (R2). 

## Results and Discussion
The LSTM model shows reasonable performance in predicting the closing prices of XRP, as demonstrated by the model's predictions compared to the actual prices in the test set. However, further tuning of the model's hyperparameters and feature engineering could potentially improve the results. Future research could focus on optimizing the model's hyperparameters, enhancing feature engineering, and comparing the model's performance to that of other machine learning approaches in order to determine the best strategy for predicting cryptocurrency prices.

## Repo Contents
- `README.md`: Description of the project and its contents
- `XRP-USD.csv`: The dataset used in the project
- `FinalProjectCS414.ipynb`: Colab Notebook containing the code used for the project that needs to be downloaded
- `FinalProjectCS414(can be accessed directly on google colab).ipynb`: Colab Notebook containing the code used for the project that can be opened directly in google colab
- [Project Website](https://omardrira.github.io/CS414FinalProject/) : the Github static website for the project
- [Cs414FinalProjectYoutubeTutorial](https://youtu.be/aZnYOdqEge0): A recorded video tutorial explaining how to run the code.
- `Cs414FinalProjectExecutiveReport.pdf`: an executive report for the project
- `Section1.png`,`Section2.png`,`Section3.png`: Model perfomance graphs
- `index.html`: the html file for the project website
- `style.css`: the css file for the project website

## How to Run the Code
To run the code, you need to upload the notebook `Cs414FinalProjectExecutiveReport.ipynb` into Google Colab, along with the dataset `XRP-USD.csv`. You can follow the steps in the recorded video tutorial in this link [Cs414FinalProjectYoutubeTutorial](https://youtu.be/aZnYOdqEge0) to execute the code step-by-step. The video tutorial explains the necessary packages to import, data preprocessing, LSTM model building, training, and evaluation, and finally, the visualization of the model's performance.

### Note
This project was inspired by [Cryptocurrency-Prediction-with-Artificial-Intelligence](https://github.com/emirhanai/Cryptocurrency-Prediction-with-Artificial-Intelligence).
