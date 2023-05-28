Here I have forecasted future stock prices of stocks. I have used different models like Long Short Term Memory, Bidirectional Long Short Term Memory, Gated Recurrent Unit and Facebook's Prophet model.
So the frist step here is first you need to import the required libraries.
Then you need to load your data.
After that create the training set and testing set and also check if there are any missing values.
Then you need to scale the data.
Then you should define the training and testing sizes of the input.
After that split the data into training set and testing set.
Then create the dataset in time series for the specific models(LSTM, BiLSTM, GRU).
Then take previous 100 days record for training for the prediction of future.
Then Reshape the data to fi into that specific model(LSTM, BiLSTM, GRU).
After that Create the model and compile the model.
Then plot the loss.
Then you need to predicting on train and test data.
Then inverse transform it to get the actual value and visualize the data.
Combine the predicted data to create uniform data visualization.
Get last 100 days record and create the list of that data.
Predict next 10 days price using the current data. You may change it also
It will predict in sliding window manner (algorithm) with stride 1.
Create a dummy plane to plot graph one after another.
Then extend it. Extends helps us to fill the missing value with approx value.
Create the final data for plotting and plot it.
