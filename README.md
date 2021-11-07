# Time_series_data_analysis

Time series simply represent data points over time. They are thus everywhere in nature and in business: temperatures, heartbeats, births, population dynamics, internet traffic, stocks, inventories, sales, orders, factory production — you name it. In countless cases, efficient processing and forecasting of time series has the potential to provide decisive advantages. It can help businesses adapt their strategies ahead of time (e.g. if production can be planned in advance), or improve their operations (e.g. by detecting anomalies in complex systems). Although there exist many models and tools for time series, they are still often nontrivial to work with, because they each have their own intricacies and cannot always be used in the same way. At Unit8, we often work with time series and thus we started developing our own tool to make our lives simpler. We also decided to contribute to the community by open-sourcing it. In this article, we introduce Darts, our attempt at simplifying time series processing and forecasting in Python.![image](https://user-

If you are a data scientist working with time series you already know this: time series are special beasts. With regular tabular data, you can often just use scikit-learn for doing most ML things — from preprocessing to prediction and model selection. But with time series, the story is different. You can easily end up in situations where you need one library for pre-processing (e.g. Pandas to interpolate missing values and re-sample), another to detect seasonality (e.g. statsmodels), a third one to fit a forecasting model (e.g. Facebook Prophet), and finally more often than not you’ll have to implement your own backtesting and model selection routines. This can be quite tedious, as most libraries use different APIs and data types. And that’s not even mentioning cases involving more complex models based on neural networks, or problems involving external data and more dimensions. In such cases you’d likely have to implement the models yourself for your use-case, for instance using libraries such as Tensorflow or PyTorch. Overall, we feel that the experience of doing machine learning on time series in Python is just not really smooth, yet


images.githubusercontent.com/59999074/140640304-46587137-511b-4197-a46e-84503aaa58f9.png)
