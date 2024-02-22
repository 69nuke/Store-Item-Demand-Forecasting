Jupyter notebook regarding my take on the 'Store Item Demand Forecasting' challenge, as posted by Python.
I used this dataset to train with data analytics, dealing with time series data, performing and evaluating machine learning modeling using Facebook Prophet model, creating 90 days-ahead sales forecasts. On top of that, I considered the forecasts as the future demand, so I was able to generate basic Inventory Metrics ass well in order to acquire extra knowledge on strategies to be deployed on stockroom management.

I set myself multiple goals for this notebook :
- taking a dataset considering 50 items sold in 10 stores through time;
- producing Exploratory Data Analysis, so to understand better the nature of data and gain valuable insights;
- splitting the time series into train/test sets, in order to train a Prophet model and evaluating its performance;
- generating 90-days ahead aggregate daily sales forecasts per item sold.

After this, I enquired about the possibility of creating functions that would return plots and forecasts values by calling the specific item.

Later, I realized the forecasts can be considered as future demand, so I could eventually calculate safety stock, lead time demand, reorder point per item (again using a function).

Everything is fully described in the .ipynb file in the repository.

Please hit me up in case of anything! I am more than happy to discuss and receive feedback.

And thank you for taking the time to check this project ;)
