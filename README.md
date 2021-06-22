# LSTM_Stock_Prediction

**Introduction:**
This project uses a deep-learning Convolutional neural network (CNN) with Long short-term memory (LSTM) layer to try and comprehend the stock market patterns and price changes.

**Prediction Method:**
In order to predict the stock market trend and interest, We use deep learning model.
Model Input: 
The model learns for a specific stock its (normalized) price history and some of its financial indicators. Each data consists of predefined amount of days into the past, and the desired prediction value. 
Model Output: 
The models’ prediction value is the future normalized stock price.
Model Layers:
![image](https://user-images.githubusercontent.com/7150655/122877831-b6e82680-d33f-11eb-90e1-3f8b6d02ec0e.png)

**Evaluation:**
Our model uses Mean Square Error (MSE) as loss function. Therefore, in order to evaluate the models’ performance we convert the regression problem (Stock price prediction) to a binary problem (Will the price be higher or lower?).
![image](https://user-images.githubusercontent.com/7150655/122877882-c49dac00-d33f-11eb-80ac-9a2320e87230.png)

Next, we use Accuracy score to present how well our model performed. The score is calculated by the following formula:

(𝑇𝑁+𝑇𝑃)/(𝑇𝑃+𝐹𝑃+𝑇𝑁+𝐹𝑁)

The accuracy is compared between binary values so we had to transform our result into binary representation.
![image](https://user-images.githubusercontent.com/7150655/122877925-d2ebc800-d33f-11eb-9f41-15b66d0c374a.png)

**Conclusions:**
Learning different stocks produced varied learning curves, MSE values, and Accuracy scores.
Some of our model predictions and evaluations are presented in the table below:
![image](https://user-images.githubusercontent.com/7150655/122877950-db440300-d33f-11eb-98c3-71bed6b2857e.png)
