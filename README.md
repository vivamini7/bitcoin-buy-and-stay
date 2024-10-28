# Bitcoin-prediction project

### 1 첫번째 방법 (first method)
Dataset list (e.g., Reddit, Twitter, news) used for sentiment analysis with a dataset of coin prices (e.g., Binance, Upbit). We use cross-validation to check if the variation is negative and apply momentum investment. However, there are challenges, including dataset limitations for precise prediction and poor predictability of price changes.

<p align="center">
  <img src="https://github.com/user-attachments/assets/94cffba7-6251-4dea-ac10-6f462df37f25" alt="1">
</p>

### 2 두번째 방법 (second method)
So we changed method using whitepapre of coin. First we download all whitepaper of coins and do crtpytoBERT model based text embedding. Next, we process k-means clustering of embedding value and find what is the center coin of all coins. Finally we train model(LSTM, BiLSTM, GRU, Bi GRU) for center coin and do tranfer learning of other coins in same cluster. You can see result of training and transfer learning next image.

<p align="center">
  <img src="https://github.com/user-attachments/assets/8568f471-89e4-49ef-8e9e-40bed880e414" alt="2">
</p>
