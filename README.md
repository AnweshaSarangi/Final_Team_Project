# Final_Team_Project_10
## Supply Chain Data Analysis
 This project is a part of the AAI-501-A1: Introduction to Artificial Intelligence course in the Applied Artificial Intelligence Program at the University of San Diego (USD).

### Description
 This project aims to develop an AI-driven model for product-wise sales forecasting using the DataCo Smart Supply Chain dataset. The project aims to understand the structure and contents of the DataCo Smart Supply Chain dataset, perform data cleaning and preprocessing, conduct exploratory data analysis (EDA) to identify key features and patterns in the data, perform featureengineering, train, cross-validate and evaluate different models of regression and time series forecasting, and select the best performing model.

### Methods Used
- Outlier Analysis
- Correlation Analysis
- Data Preparation
- Principal Component Analysis (PCA)
- Variance Inflation Factor (VIF) Analysis
- Model Evaluation and Interpretation

### Technology Used
The project utilizes the following technologies and libraries:
 - Python: The primary programming language used for data analysis and modeling.
 - Pandas: A powerful library for data manipulation and analysis.
 - NumPy: A library for numerical operations.
 - Scikit-learn: A machine learning library used for model building, evaluation, and feature engineering.
 - XGBoost: A robust and efficient library for gradient boosting, used for predictive modeling.
 - ARIMA/Prophet/LSTM: Libraries and models used for time series forecasting.
 - Jupyter Notebook: An interactive environment for developing, presenting, and sharing data analysis workflows.

### Installation 
 1. Clone the repository: `https://github.com/AnweshaSarangi/Final-Team-Project.git`
 2. Navigate to the project directory: `cd Final-Team-Project`
 3. Install dependencies: `pip install -r requirements.txt`

### Usage
 1. Open the Jupyter Notebook: `Jupyter Notebook`
 2. Run the analysis scripts in the provided order.
    - `1. Data Preparation.ipynb`
      This notebook contains all the steps necessary to clean and preprocess the data. It should be run first to ensure that the data is in the correct format for analysis.
      Ensure the prepared data is saved correctly.
    - `2. Data Analysis.ipynb`
      This notebook performs the analysis of the prepared data. It should run after `1. Data Preparation.ipynb`.
    - `3. Model Tuning.ipynb`
      This notebook focuses on training machine learning models and tuning their hyperparameters. It includes model evaluation and selection to achieve the best performance. It should run after `2. Model Tuning.ipynb`.

### Team Members
- A: [Anwesha Sarangi](https://github.com/AnweshaSarangi)
Led the planning phase and initial approach, reviewed the project reports, supported model implementation
- B: [Rajesh Sharma](https://github.com/Rajesh-Sharma-git)
Conducted Research, data transformations, project documentation, and model analysis validation
- C: [Soumi Ray](https://github.com/DrSoumiz)
Executed data cleaning and EDA, and implemented and analyzed the model.

### License
This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

### Acknowledgments
We would like to express our sincere gratitude to the following individuals for their invaluable support and contributions to this project:

Professor Dr. Rakesh Das: For his guidance, support, and invaluable feedback throughout the course. His insights and expertise were instrumental in shaping this project.
