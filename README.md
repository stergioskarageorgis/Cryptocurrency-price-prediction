# Cryptocurrency-price-prediction
# Program Overview

 Data Retrieval: The program fetches historical daily price data for Bitcoin in CAD using the CryptoCompare API.

 Data Preprocessing: The obtained data is preprocessed, and unnecessary columns are dropped for model training.

 Model Building: An LSTM neural network model is constructed using Keras to predict future prices based on historical data.

 Training: The model is trained on a portion of the dataset, and training progress is visualized using loss plots.

 Evaluation: The trained model is evaluated on a test set, and metrics such as Mean Squared Error (MSE) and R-squared (R2) are calculated.

 Visualization: Actual vs. predicted prices are visualized using Matplotlib to assess model performance.


# Parameters
 window_len: Size of the historical window for training the LSTM model.
 test_size: Percentage of data to be used for testing.
 lstm_neurons: Number of neurons in the LSTM layer.
 epochs: Number of training epochs.
 batch_size: Batch size for training the model.
 loss: Loss function used in model compilation.
 dropout: Dropout rate to prevent overfitting.
 optimizer: Optimization algorithm used during training.


# Results
The model's performance is assessed using Mean Squared Error (MSE) and R-squared (R2) metrics. Actual vs. predicted prices are visualized to provide insights into the model's predictive capabilitie
