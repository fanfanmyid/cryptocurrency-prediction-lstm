# Cryptocurrency Price Prediction using Long Short Term Memory (LSTM) short term cases (OnGoing Thesis)

Halo Semuanya, Saat ini saya sendang mengembangkan time series prediction untuk cryptocurrency dengan tujuan : 
- Menguji performa algoritma LSTM dan GRU dalam memprediksi harga cryptocurrency (BTC, ETH dan BNB terhadap BUSD) dalam jangka pendek yatu dengan timeframe 1m,5m dan 15m
- Menguji performa algoritma dengan data realtime

Untuk inputan sendiri saya menggunakan indikator teknikal yaitu Moving Average, Relative Strength Index, Moving Average Convergence/Divegence, Bollinger Bands dan juga inputan lain. 

link interface untuk sampel prediksi secara realtime
```sh
http://fanfan.my.id/crypto/
```
link api untuk sampel prediksi secara realtime
```sh
https://fanfan-api.deta.dev/docs

input :
timeframe : 1m, 5m dan 15m
limit : default 5 dan max 1000
```

dengan flowchart pembuatan model

![alt text](https://github.com/fanfanmyid/cryptocurrency-prediction-lstm/blob/master/image/flowchart.png?raw=true)

yang kemudian pada pengujian realtime data menggunakan api store dan juga untuk melihat prediksi terdapat api get yang dapat digunakan

![alt text](https://i.im.ge/2022/06/30/uSaXF0.png)

untuk performa saat ini 
![alt text](https://github.com/fanfanmyid/cryptocurrency-prediction-lstm/blob/master/image/lstm_btc_1m.png?raw=true)
![alt text](https://github.com/fanfanmyid/cryptocurrency-prediction-lstm/blob/master/image/gru_btc_1m.png?raw=true)


mohon maaf saat ini sourcecode belum dishare dikarenaka masih tahap developement. untuk yang mau coba prediksinya bisa ke link diatas


