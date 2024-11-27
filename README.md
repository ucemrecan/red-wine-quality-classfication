# **Red Wine Quality Prediction**

A machine learning project to predict the quality of red wine using physicochemical properties and sensory data.

## **Overview**

This project utilizes a dataset of Portuguese "Vinho Verde" red wine to explore the relationship between physicochemical attributes and wine quality. By applying machine learning algorithms, the goal is to predict wine quality on a scale of 0 to 10.

The dataset is sourced from Kaggle and contains physicochemical measurements (e.g., acidity, pH) as input variables and wine quality scores as the target variable. These tasks can be approached as regression or classification problems.

[Dataset on Kaggle](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009?datasetId=4458&sortBy=voteCount)

## **Technologies Used**

The project leverages the following Python libraries:

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib & Seaborn**: For data visualization and exploratory analysis.
- **Scikit-learn**: (Optional, if used later) For implementing machine learning models.

Additional tools include **Jupyter Notebooks** for an interactive coding environment.

## **Dataset Description**

The dataset includes physicochemical input variables and one output variable:

### **Input Variables**

- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol

### **Output Variable**

- **Quality**: A score between 0 (poor) and 10 (excellent) based on sensory evaluation.

## **How to Use**

### **Step 1: Clone the Repository**

```bash
git clone https://github.com/your-username/red-wine-quality-prediction.git
cd red-wine-quality-prediction
```

### **Step 2: Install Dependencies**

Ensure you have Python installed, then install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

### **Step 3: Run the Notebook**

The analysis and visualizations are in the Init.ipynb file. Open the file in Jupyter Notebook or Jupyter Lab:

```bash
jupyter notebook main.ipynb
```

### **Step 4: Explore the Code**

Inside the notebook, you’ll find:

- Data loading and preprocessing steps.
- Exploratory data analysis (EDA) with visualizations.
- Basic insights derived from the dataset.

## References

- [Cortez et al., 2009]
- Dataset available at Kaggle.
