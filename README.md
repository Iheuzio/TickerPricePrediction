# TickerPricePrediction
The code implements a neural network model, PricePredictor, trained on historical stock price data to predict future stock prices, visualizing the predictions alongside historical prices and calculating the average of the predicted prices.

The graph produced will either show the plotted points, the average after the historical days from january or the historical prices for the year with the forecasted days added onto it.

## Instructions

1. Swap `ticker="INTC"` for whatever ticker you want to check
2. Swap `future_days=30` for the amount of days you want to forecast
3. Ensure that you have a cuda device before running and you have the libraries installed except for yfianance since kaggle and colab don't have it.

## Viewing plotted points

This model is trained by adjusting its internal parameters based on historical stock price data and observed outcomes. It uses a forward pass to make predictions and calculates the difference between the predicted and actual prices using a loss function. Through multiple iterations and parameter updates, the model learns patterns in the data and improves its ability to make accurate predictions. Once trained, the model can take input values and generate predictions for future stock prices based on the patterns it has learned.

# Example of plotted points with graph

![image of plotted points generated by model with historical price lines](https://github.com/Iheuzio/TickerPricePrediction/assets/97270760/e01f611e-dc8d-4452-be87-a1b743925aa5)


# Example of average line shown
![Average line of the plotted points showing a linear line averaging from the previous image](https://github.com/Iheuzio/TickerPricePrediction/assets/97270760/877aefd2-4b18-4567-9354-67cc7fdf8dc6)


# Example of finalized output
![Finalized output showing an average line with the historical values and their predicted line for it amongst the historical prices for that year](https://github.com/Iheuzio/TickerPricePrediction/assets/97270760/e994f0d6-65f4-4add-bdcb-c35b18feae82)

