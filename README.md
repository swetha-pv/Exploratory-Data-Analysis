#Exploratory-Data-Analysis 
This project performs an in-depth Exploratory Data Analysis (EDA) on the famous Titanic dataset using Python libraries such as **Pandas**, **Matplotlib**, and **Seaborn**. The goal is to uncover patterns, relationships, and anomalies that help understand survival rates.

## 📁 Dataset

- Source: [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data)
- File used: `train.csv`

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📊 EDA Highlights

- Data overview using `.info()`, `.describe()`, `.value_counts()`
- Missing value analysis and visualizations
- Categorical analysis (`Sex`, `Pclass`, `Embarked`) vs. `Survived`
- Distribution plots for `Age`, `Fare`
- Correlation matrix and heatmap
- Boxplots and histograms to explore numerical variables
- Pairplots for multivariate trends

## 📌 Key Findings

- Females had significantly higher survival rates
- Passengers in 1st class had better survival chances
- Young children and infants were more likely to survive
- Fare amount showed a positive correlation with survival

## 📂 Files Included

- `Titanic_EDA.ipynb`: Jupyter Notebook with full code and visualizations
- `Titanic_EDA_Report.pdf`: PDF version with explanations and summary (optional)
- `README.md`: Project description

## 📄 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/titanic-eda.git
   cd titanic-eda
