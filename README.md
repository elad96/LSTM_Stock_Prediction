# LSTM_Stock_Prediction

**Project Video:**
https://www.youtube.com/watch?v=jq7yurfSSzU

**Introduction:**
This project uses a deep-learning Convolutional neural network (CNN) with Long short-term memory (LSTM) layer to try and comprehend the stock market patterns and price changes.

**Prediction Method:**
In order to predict the stock market trend and interest, We use deep learning model.
Model Input: 
The model learns for a specific stock its (normalized) price history and some of its financial indicators. Each data consists of predefined amount of days into the past, and the desired prediction value. 
Model Output: 
The models’ prediction value is the future normalized stock price.
Model Layers:

![ללא שם](https://user-images.githubusercontent.com/7150655/122878541-8bb20700-d340-11eb-8047-df9965d9b44a.png)


**Evaluation:**
Our model uses Mean Square Error (MSE) as loss function. Therefore, in order to evaluate the models’ performance we convert the regression problem (Stock price prediction) to a binary problem (Will the price be higher or lower?).

![MSE](https://user-images.githubusercontent.com/7150655/122878281-41308a80-d340-11eb-8e0a-597eb77dfcfc.JPG)

Next, we use Accuracy score to present how well our model performed. The score is calculated by the following formula:
(𝑇𝑁+𝑇𝑃)/(𝑇𝑃+𝐹𝑃+𝑇𝑁+𝐹𝑁)

The accuracy is compared between binary values so we had to transform our result into binary representation.

![BlueGraph](https://user-images.githubusercontent.com/7150655/122878361-59080e80-d340-11eb-967b-03290652d43e.JPG)

**Conclusions:**
Learning different stocks produced varied learning curves, MSE values, and Accuracy scores.
Some of our model predictions and evaluations are presented in the table below:

![Conclusions](https://user-images.githubusercontent.com/7150655/122878392-62917680-d340-11eb-9333-091f1fcc65ca.JPG)
