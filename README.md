# 🚢 Titanic Survival Predictor

A mini machine learning project that predicts whether a Titanic passenger survived or not, based on features like age, gender, class, and fare — built using a **Random Forest Classifier**.

## 📌 Overview

This project uses the classic Titanic dataset to train a Random Forest model that predicts passenger survival. It covers the full ML workflow: data cleaning, preprocessing, model training, and evaluation.

## 🛠️ Tools & Libraries

- Python
- Pandas
- Scikit-learn
- Random Forest Classifier
- Jupyter Notebook

## 🔍 Project Workflow

1. **Data Loading** – Loaded the Titanic dataset.
2. **Handling Missing Values** – Filled missing values in `Age` and `Embarked` columns.
3. **Encoding Categorical Data** – Converted `Sex` and `Embarked` columns into numerical values.
4. **Train/Test Split** – Split the dataset into 80% training and 20% testing data.
5. **Model Training** – Trained a Random Forest Classifier on the processed data.
6. **Evaluation** – Checked model accuracy on the test set.

## 📊 Results

- **Accuracy:** 82.12%
- **Most important features:** `Sex`, `Fare`, and `Pclass`
- **Sample prediction:** A 25-year-old male passenger in 3rd class was predicted to **not survive**.

Feature importance is visualized in [`Feauture importance.png`](./Feauture%20importance.png).

## 📁 Repository Structure

```
titanic-project/
├── titanic.ipynb                                  # Main notebook with code
├── Project Titanic Survival Predictor.txt         # Project summary
├── Titanic_Survival_Predictor_Documentation.docx  # Detailed documentation
├── Feauture importance.png                        # Feature importance plot
├── output.png                                     # Model output/result screenshot
└── README.md
```

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/krishRathiDev/titanic-project.git
   ```
2. Open `titanic.ipynb` in Jupyter Notebook / VS Code / Google Colab.
3. Install the required libraries:
   ```bash
   pip install pandas scikit-learn numpy matplotlib
   ```
4. Run all cells to reproduce the results.

## 📄 Documentation

For a more detailed explanation of the project, check out [`Titanic_Survival_Predictor_Documentation.docx`](./Titanic_Survival_Predictor_Documentation.docx).

## 👤 Author

**Krish Rathi**
[GitHub Profile](https://github.com/krishRathiDev)
