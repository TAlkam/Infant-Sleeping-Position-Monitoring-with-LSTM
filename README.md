
# Infant Sleeping Position Monitoring with LSTM

This project aims to enhance infant safety by monitoring their sleeping positions using an LSTM (Long Short-Term Memory) neural network. By analyzing various parameters such as leg movement, tag visibility, and time, we predict safe sleeping positions and contribute to preventing SIDS (Sudden Infant Death Syndrome).

## Project Structure

- **Step 1:** Import necessary libraries for data manipulation, machine learning modeling, and visualization.
- **Step 2:** Load and preprocess the dataset to structure it for analysis, including datetime conversions and feature extraction.
- **Step 3:** Data preprocessing, including feature scaling and splitting the dataset into training and testing sets for model training.
- **Step 4:** Define, compile, and train the LSTM model with the processed dataset.
- **Step 5:** Evaluate the model's performance on the test set and make predictions.
- **Step 6:** Perform K-Fold Cross-Validation to assess the model's reliability across different subsets of the data.
- **Step 7:** Export the results and predictions for further use or analysis.

## Setup

To run this project, ensure you have Python and the necessary libraries installed:

- pandas
- scikit-learn
- TensorFlow/Keras
- numpy
- matplotlib

You can install these libraries using pip:

```bash
pip install pandas scikit-learn tensorflow numpy matplotlib
```

## Dataset

The dataset used in this project, named 'GD for IoT device infant safe prediction.csv', contains various features related to infant movement and environmental factors influencing sleeping safety.

## Usage

- **Data Loading**: Upload the dataset using the provided code snippet for Google Colab users.
- **Preprocessing**: Execute the data preprocessing steps to clean and prepare the data for modeling.
- **Model Training**: Run the LSTM model training code, adjusting parameters as necessary for your dataset.
- **Evaluation**: Evaluate the model's performance using the provided metrics.
- **Cross-Validation**: Optionally, perform K-Fold Cross-Validation to further validate the model's effectiveness.

## Exploratory Data Analysis (EDA)

Before diving into model training, performing EDA helps us understand the dataset's characteristics, identify patterns or anomalies, and make informed decisions during model development.

### EDA Objectives

- Understand feature distributions.
- Identify correlations between features and the target variable.
- Detect outliers or anomalies.
- Visualize trends over time with 'DeviceDateTime'.

### EDA Steps

1. **Data Overview**: Familiarize with the dataset's structure and summary statistics.
2. **Univariate Analysis**: Analyze individual variable distributions.
3. **Bivariate/Multivariate Analysis**: Explore relationships between variables.
4. **Time Series Analysis**: Investigate patterns over time.
5. **Feature Engineering Insights**: Identify opportunities for new features.

### Tools and Libraries

- **pandas**, **matplotlib**, **seaborn**, and **numpy** for data manipulation and visualization.

### Performing EDA in Google Colab

We recommend using Google Colab for interactive data analysis. Sample code snippets are provided for basic EDA tasks, such as data overview, visualization, and summarizing findings.

## Contributing

Contributions to improve the model or extend the project's capabilities are welcome. Please feel free to fork the repository and submit pull requests.

## License

This project is open-sourced under the MIT License. See the LICENSE file for more details.

