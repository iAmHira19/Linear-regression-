# Height vs. Weight Linear Regression

This project demonstrates the application of linear regression using a small dataset of heights and weights. The goal is to predict an individual's weight based on their height.

## Dataset

The dataset used in this project, `weight-height.csv`, contains two columns:

- `Height`: Height of individuals in inches.
- `Weight`: Weight of individuals in pounds.

## Project Structure

- `weight-height.csv`: The dataset file.
- `Linear_Regression_Height_Weight.ipynb`: The Jupyter notebook containing the code for data analysis, model training, and evaluation.
- `README.md`: This file.

## Requirements

To run this project, you'll need the following Python libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`

You can install the required libraries using the following command:

```bash
pip install pandas numpy matplotlib scikit-learn
```

## How to Run

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/hiraamanat/height-weight-linear-regression.git
   cd height-weight-linear-regression
   ```

2. Upload the `weight-height.csv` file to your Google Colab environment or run the project locally in your preferred Python environment.

3. Open the Jupyter notebook `Linear_Regression_Height_Weight.ipynb` and run all cells to perform data analysis, model training, and evaluation.

## Results

The linear regression model predicts the weight based on the height of individuals. The notebook includes a plot showing the actual vs. predicted weights along with model evaluation metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² score.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

