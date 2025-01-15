# House Price Prediction

This repository contains a machine learning project aimed at predicting house prices based on various features. The project includes data preprocessing, feature encoding, scaling, model training, and evaluation using a Linear Regression model.

## Project Structure

### Data
- **Dataset**: `House_Price.csv` is used as the primary dataset.
- **Features**: Includes a mix of numerical and categorical variables.

### Steps
1. **Data Loading**: Load the dataset using Pandas.
2. **Data Cleaning**:
   - Handle missing values with appropriate strategies.
   - Encode categorical features using `LabelEncoder`.
3. **Feature Scaling**: Use `StandardScaler` to scale numerical features.
4. **Model Training**: Train a Linear Regression model on the processed data.
5. **Model Evaluation**:
   - Compute Mean Squared Error (MSE).
   - Visualize predictions vs. actual values.

## Installation

To run this project, ensure you have the following Python libraries installed:

```bash
pip install numpy pandas matplotlib scikit-learn
```

## Usage

1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd house-price-prediction
   ```

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook project.ipynb
   ```

4. Follow the cells sequentially to reproduce the results.

## Key Outputs

- **Preprocessing**:
  - Missing values are filled or encoded.
  - Features are scaled.
- **Model**:
  - Linear Regression model is trained and evaluated.
- **Visualization**:
  - Scatter plot comparing predicted vs. actual values.

## Results

- **Mean Squared Error**: The MSE of the model is computed and displayed in the notebook.
- **Visualization**: A plot showing the relationship between predicted and actual values is generated.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your improvements or suggestions.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgements

- The dataset was sourced from `House_Price.csv`.
- Libraries: [NumPy](https://numpy.org/), [Pandas](https://pandas.pydata.org/), [Matplotlib](https://matplotlib.org/), and [Scikit-learn](https://scikit-learn.org/).

# Team Members:
1. Anakn Bera
2. Subham Das
3. Abhishek Kumar
4. Aditya Kumar
5. Subhadeep Kar
6. Srinjoy Chakraborti
