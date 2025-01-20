# California Housing Price Prediction 🏠

This project uses the California Housing dataset to analyze and predict median house values through various regression models, including simple linear regression, multiple linear regression, and locally weighted linear regression (LWLR). The analysis evaluates model performance using metrics like R², MAE, and RMSE.

## Features

- **Exploratory Data Analysis (EDA):**  
  - Visualized pairwise relationships, correlation heatmaps, and histograms to uncover key predictors.  
  - Identified **median income** as the strongest predictor for house prices.

- **Linear Regression Models:**  
  - **Simple Linear Regression:** Focused on median income as a single predictor, achieving an R² score of **0.459**.  
  - **Multiple Linear Regression:** Leveraged multiple features to improve performance, achieving an R² score of **0.576**.

- **Locally Weighted Linear Regression (LWLR):**  
  - Tuned the `tau` parameter to optimize predictions, achieving an R² score of **0.473** on test data.

## Dataset

- **Source:** California Housing Dataset  
- **Size:** 20,640 records  
- **Features:**  
  - Median Income  
  - House Age  
  - Average Rooms  
  - Average Bedrooms  
  - Population  
  - Average Occupancy  
  - Latitude and Longitude  
  - Median House Value  

## Results

- **Simple Linear Regression:**  
  - MAE: **0.630**, RMSE: **0.842**, R²: **0.459**  
- **Multiple Linear Regression:**  
  - MAE: **0.533**, RMSE: **0.746**, R²: **0.576**  
- **LWLR:**  
  - MAE: **0.553**, RMSE: **0.797**, R²: **0.473**  

## Key Insights

- Median income is the most significant predictor of housing prices.  
- Multiple linear regression outperformed simple linear regression and LWLR in terms of accuracy and computational efficiency.  
- LWLR offers flexibility in capturing non-linear relationships but is computationally intensive.

## Installation

1. Clone the repository:  
   ```bash
   git clone https://github.com/YourUsername/HousingPricePrediction.git
   ```

2. Navigate to the project directory:  
   ```bash
   cd HousingPricePrediction
   ```

3. Install required Python libraries:  
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run Notebook:** Launch the Jupyter Notebook to execute the regression models:  
   ```bash
   jupyter notebook ML_Project1.ipynb
   ```

2. **Data Analysis:** Use the notebook to explore data visualizations, evaluate regression models, and analyze key predictors.

## Skills Demonstrated

- Regression Analysis (Simple, Multiple, LWLR)  
- Exploratory Data Analysis (EDA)  
- Feature Engineering and Model Optimization  
- Python Libraries: NumPy, Pandas, Matplotlib, Scikit-learn  

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
