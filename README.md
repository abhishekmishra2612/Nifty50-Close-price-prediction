# Nifty50-Close-price-prediction

Developed a deep learning model which can predict the closing price of next 3 days given the records of last 15 days data, the features of data are "Low Price", "High Price", "Last Traded Price", "Closing Price" and "Volume".
### Source of data https://www.kaggle.com/rohanrao/nifty50-stock-market-data

We trained the model on Nifty50 data which contain more than 230K datapoints from 2001 to 2020.
The evaluation on unseen data of AXIS Bank, TataMotors and Britannia data are fairly good 
#### Some of the predicted results on unseen data.(Predict close price of next 3 days), Here Green dots are actual closing price of next 3 days while Red dots are predicted closing price for corresponding next 3 days.
### For Axis Bank
![Screenshot (241)](https://user-images.githubusercontent.com/41646536/88663384-25edd880-d0f9-11ea-9f3a-1c1ed6d83f82.png)
### For Tata Motors
![Screenshot (242)](https://user-images.githubusercontent.com/41646536/88663570-75340900-d0f9-11ea-854d-3bcc39227eee.png)
### For Britannia
![Screenshot (243)](https://user-images.githubusercontent.com/41646536/88663716-a44a7a80-d0f9-11ea-8d8f-bc4c1123f84b.png)
