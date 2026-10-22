# Traffic Congestion Prediction using LSTM

## Problem Statement
Predict future traffic congestion using historical traffic observations to support emergency vehicle route planning.

## Model Used
LSTM (Long Short-Term Memory)

## Technologies
- Python
- Google Colab
- TensorFlow / Keras
- Pandas and NumPy
- Scikit-learn
- Matplotlib

## Methodology
1. Load the dataset.
2. Select the first 10,000 records.
3. Preprocess and normalize the data.
4. Create sequences using the previous 24 observations.
5. Split the sequences into 80% training and 20% testing.
6. Train the LSTM model.
7. Evaluate predictions using MAE and RMSE.
8. Plot actual versus predicted values.

## Results
Mean Absolute Error (MAE): 4.9386
Root Mean Squared Error (RMSE): 10.2489

## Execution
Open the notebook in Google Colab and run the cells in order.
