# Anomaly Detection Experiment

A notebook detailing a "proof of concept" applying autoencoders in a traditional IoT architecture to achieve two important results:
  1. Compress data sent to the gateway to improve network throughput.
  2. Detect potential anomalies or tampering before data is broadcast.

We use the following data set: http://db.csail.mit.edu/labdata/labdata.html
to train a traditional autoencoder using discrete methods.

## Future Work

We intend to find time-series data to train an LSTM-based autoencoder to prove that this concept can be extended to non-discrete data sets.
