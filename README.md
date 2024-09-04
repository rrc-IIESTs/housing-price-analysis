# Housing Price Evaluation: Insights into the Real Estate Market

## Introduction
**Real Estate Insights: Housing Price Analysis** is a data science project that focuses on analyzing and predicting housing prices. The project covers the entire data science pipeline, including data gathering, preprocessing, exploratory data analysis (EDA), and model building. We utilize machine learning models like the Random Forest Regressor and Support Vector Machine (SVM) to develop predictive models. Principal Component Analysis (PCA) is applied for feature selection, followed by statistical analyses of the most significant features.

## Project Workflow

### 1. Data Collection
A comprehensive real estate dataset was collected, ensuring that it contains all relevant features for analysis and modeling.

### 2. Data Wrangling and Cleaning
The dataset underwent cleaning and preprocessing steps, including:
- Handling missing data.
- Removing outliers.
- Normalizing values for consistent scaling.

### 3. Exploratory Data Analysis (EDA)
Conducted thorough EDA to identify trends, patterns, and relationships in the dataset using:
- Univariate analysis: Summarizing individual variables.
- Bivariate analysis: Examining relationships between two variables.

### 4. Feature Selection (PCA)
Principal Component Analysis (PCA) was used to reduce dimensionality and isolate the features most influential in determining housing prices.

### 5. Statistical Analysis
Performed univariate and bivariate analysis on the principal components to better understand their impact on housing prices.

### 6. Model Development
Built machine learning models using:
- **Random Forest Regressor**
- **Support Vector Machine (SVM)**

### 7. Model Evaluation
Model performance was evaluated using various metrics to ensure accuracy and reliability of predictions.

## Technology Stack

- **Programming Language**: Python
- **Data Manipulation & Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Machine Learning**: Scikit-learn
- **Dimensionality Reduction**: Principal Component Analysis (PCA)
- **Machine Learning Models**: Random Forest Regressor, Support Vector Machine (SVM)

## Getting Started

### Prerequisites
- Python 3.8 or later

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rrc-IIESTs/housing-price-analysis.git
   cd housing-price-analysis

## Installation
    ```bash
    pip install -r requirements.txt
    
## Running the Project

You can execute the Jupyter notebooks or Python scripts provided in the repository to reproduce the project results.

- **Data Gathering & Cleaning**: Use the provided scripts to gather and preprocess the dataset.
- **Exploratory Data Analysis**: Generate visualizations and summaries to understand the data.
- **Feature Selection**: Apply PCA to identify the key features.
- **Model Training**: Train the models (Random Forest, SVM) using the relevant scripts.
- **Evaluation**: Evaluate and compare the models using performance metrics.

## Results
The project successfully identifies the most important features influencing housing prices. Predictive models, including Random Forest Regressor and SVM, have been built, evaluated, and provide insights into the dataset's key drivers.

## Contribution Guidelines
Contributions are welcome! You can fork the repository, report issues, or submit pull requests to enhance the project.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments
- **Pandas & NumPy** for data manipulation.
- **Matplotlib & Seaborn** for data visualization.
- **Scikit-learn** for machine learning models and PCA implementation.
