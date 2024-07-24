This project demonstrates how to build a Long Short-Term Memory (LSTM) recurrent neural network model to predict energy consumption based on time series data.

## Project Overview

The project involves the following steps:

1. **Data Loading and Exploration:** Load the energy consumption dataset and perform exploratory data analysis (EDA) to understand the data's characteristics, including visualizing trends and distributions.
2. **Data Preprocessing:** Prepare the data for the LSTM model by:
    - Reformatting datetime features.
    - Handling missing values (if any).
    - Splitting the data into training and testing sets.
    - Scaling the data using MinMaxScaler.
3. **Model Building:** Construct an LSTM model with appropriate layers, dropout regularization, and an output layer for prediction.
4. **Model Training:** Train the LSTM model using the training data and optimize its parameters.
5. **Model Evaluation:** Evaluate the trained model on the test data using metrics such as Root Mean Squared Error (RMSE).
6. **Visualization:** Visualize the predicted energy consumption against the actual values to assess the model's performance.

## Results

The developed LSTM model achieved a RMSE of **813.324**, representing approximately 54% of the target variable's standard deviation and demonstrating its ability to effectively forecast energy consumption.

## Requirements

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow/Keras

## Usage

1. Clone the repository.
2. Install the required libraries.
3. Run the Jupyter notebook to execute the code and explore the analysis.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.
