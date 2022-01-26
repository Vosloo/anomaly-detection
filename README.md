<center><h1>Anomaly detection</h1></center>

<h2>About</h2>

This project is a simple implementation of anomaly detection for syntethic time series data. We've used simple neural network model to detect anomalies for a set of three separate time serieses. We've used mix of LSTM and Dense layers to build the model with. The project was done with tensorflow and keras.

There was also created a second model that is responsible for detecting  a place where each anomaly is located. The model is basically a wrapper around the first one.