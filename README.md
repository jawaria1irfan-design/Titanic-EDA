#  Titanic Survival Analysis — Python EDA

An exploratory data analysis project on the famous Titanic dataset,
investigating what factors influenced passenger survival.

##  Dataset

- **Source:** Kaggle Titanic Dataset
- **Size:** 891 rows × 12 columns
- **Key Columns:** Survived, Pclass, Sex, Age, Fare, SibSp, Parch, Embarked

##  Analysis Performed

| Area | Details |
|---|---|
| Data Loading | Loaded CSV using Pandas |
| Data Exploration | `.head()`, `.shape`, `.info()`, `.describe()` |
| Survival Rate | 38.4% survived (342), 61.6% did not (549) |
| Gender Analysis | Females had far higher survival — 233 vs 109 males |
| Class Analysis | Class 1 passengers had better survival odds |
| Age Analysis | 21–40 age group had the most casualties |
| Fare Analysis | 823 passengers paid fares in the 0–100 range |
| Binning | Age and Fare grouped into bins for pattern analysis |

##  Libraries Used

- Python 3.13
- Pandas
- Matplotlib

## ▶️ How to Run

1. Clone the repository
2. Download `Titanic-Dataset.csv` from [Kaggle](https://www.kaggle.com/c/titanic/data)
3. Update the file path in the notebook
4. Run all cells in Jupyter Notebook
