# Wine Quality Prediction

### Project Overview

This project uses machine learning to predict the quality of wine based on its chemical properties. The goal is to classify wine as either "good" or "bad" quality. Two different models, a **Decision Tree** and a **Random Forest**, are built and compared to determine which performs better for this classification task.

---

### Dataset

The dataset used is the "Wine Quality" dataset, which contains 11 chemical features for different wines, such as `fixed acidity`, `citric acid`, and `alcohol`, along with a `quality` score. The data is located in the `data/` folder. For this project, a wine with a quality score of 7 or higher is classified as "good" (1), and a wine with a quality score below 7 is classified as "bad" (0).

---

### Key Findings & Conclusion

The analysis and model comparison provided the following insights:

* **Model Performance:** The Random Forest Classifier consistently outperformed the Decision Tree Classifier in predicting wine quality.
* **Accuracy:** The Random Forest model achieved a higher accuracy score, making it the more reliable model for this dataset.
* **Conclusion:** Based on the results, the Random Forest model is recommended for classifying wine quality in this context.

---

### Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

### How to Run This Project

1.  Clone the repository to your local machine.
2.  Navigate to the project directory.
3.  Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
4.  Open and run the Jupyter Notebook:
    ```bash
    jupyter notebook "Project2 Source code.ipynb"
    ```
