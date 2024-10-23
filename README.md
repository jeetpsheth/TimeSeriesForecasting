This Problem is about time series forcasting for store sales. The data comes from an Ecuador company as known as Corporación Favorita and it is a large grocery retailer. Also, the company operates in other countries in South America.

If you wonder the company, you can [click here](https://www.corporacionfavorita.com/en/) to learn something about it.

<img width="169" alt="image" src="https://user-images.githubusercontent.com/64805962/164993288-18df351b-e0d1-4693-9a39-7426317cff7f.png">

<p>There are 54 stores and 33 prodcut families in the data. The time serie starts from 2013-01-01 and finishes in 2017-08-31. However, you know that Kaggle gives us splitted two data as train and test. The dates in the test data are for the 15 days after the last date in the training data. Date range in the test data will be very important to us while we are defining a cross-validation strategy and creating new features.</p>

<img width="349" alt="image" src="https://user-images.githubusercontent.com/64805962/164993391-db5cd81c-e656-408e-937a-ba5d6dbf87c1.png">

You can access the data from [here](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data).

<hr>

**Our main mission in this competition is, predicting sales for each product family and store combinations.**

When you look at the data description, you will see **"Additional Notes"**. These notes may be significant to catch some patterns or anomalies. I'm sharing them with you to remember.
<br>
(1) Wages in the public sector are paid every two weeks on the 15 th and on the last day of the month. Supermarket sales could be affected by this.
<br>
(2) A magnitude 7.8 earthquake struck Ecuador on April 16, 2016. People rallied in relief efforts donating water and other first need products which greatly affected supermarket sales for several weeks after the earthquake.

<hr>
