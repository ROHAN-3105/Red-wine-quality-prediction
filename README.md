# Sales Prediction with Advertising Data

### Project Overview

This project uses a multiple linear regression model to predict product sales based on advertising expenditure across TV, Radio, and Newspaper channels. The goal is to understand the impact of each advertising medium on sales and help businesses optimize their marketing budget for a better return on investment (ROI).

---

### Dataset

The dataset used is the "Advertising Sales" dataset, containing 200 records of advertising budgets for TV, Radio, and Newspaper, along with the corresponding sales figures. The data is located in the `/data` folder.

---

### Key Findings & Visualizations

The analysis revealed several key insights:

* **TV ads are the most impactful driver of sales.** The correlation analysis and model coefficients show a strong positive relationship between TV ad spending and sales.
* A model built without TV ad data performs poorly, confirming that TV advertising is a crucial predictor.

Here is the correlation heatmap of the features:
![Correlation Heatmap](image_e2bad3.png)

---

### Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- openpyxl

---

### How to Run This Project

1.  Clone the repository to your local machine:
    ```bash
    git clone [https://github.com/your-username/Sales-Prediction-Project.git](https://github.com/your-username/Sales-Prediction-Project.git)
    ```
2.  Navigate to the project directory:
    ```bash
    cd Sales-Prediction-Project
    ```
3.  Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
4.  Open and run the Jupyter Notebook:
    ```bash
    jupyter notebook "Sales Prediction Using Advertising Source Code.ipynb"
    ```