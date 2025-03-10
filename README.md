# Linear Regression Model for Ecommerce Customers

## Overview
This project builds a **Linear Regression Model** to analyze and predict customer spending behavior based on various factors. Using an ecommerce dataset, the model identifies relationships between key features such as **time spent on the website, length of membership, and annual income** to forecast customer purchases.

## Dataset
The dataset (`Ecommerce Customers.csv`) contains customer information, including:
- **Avg. Session Length** – Time spent on the site per session  
- **Time on App** – Duration of app usage  
- **Time on Website** – Time spent browsing  
- **Length of Membership** – How long a customer has been a member  
- **Yearly Amount Spent** – The target variable (amount spent per year)

## Objectives
- Perform **exploratory data analysis (EDA)** to understand patterns  
- Build and train a **Linear Regression Model**  
- Evaluate model performance using **R-squared, RMSE, and residual analysis**  
- Derive insights to optimize ecommerce strategies  

## Technologies Used
- **Python**  
- **Jupyter Notebook** for interactive analysis  
- **Libraries:**
  - NumPy  
  - Pandas  
  - Matplotlib  
  - Seaborn  
  - Scikit-learn  

## Requirements
Make sure you have Python 3.9+ installed. The recommended library versions are:

| Package        | Version |
|----------------|---------|
| numpy          | 1.24.2  |
| pandas         | 1.5.3   |
| matplotlib     | 3.7.1   |
| seaborn        | 0.12.2  |
| scikit-learn   | 1.2.2   |
| jupyter        | 1.0.0   |

### Installation
Install the dependencies using pip:  
```bash
pip install numpy==1.24.2 pandas==1.5.3 matplotlib==3.7.1 seaborn==0.12.2 scikit-learn==1.2.2 jupyter==1.0.0
```

## Results & Insights
- **Length of Membership** is the strongest predictor of customer yearly spending  
- **Time on App** has a stronger correlation to spending than **Time on Website**  
- The model achieved a high **R-squared** score, indicating reliable predictions  

## How to Run
1. Clone the repository or download the project files  
2. Install the required packages (see above)  
3. Open `Untitled.ipynb` in Jupyter Notebook  
4. Run each cell in order to replicate the analysis and results  
