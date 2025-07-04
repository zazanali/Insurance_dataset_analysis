
# 📊 Insurance Dataset - EDA, Data Cleaning, Data Preprocessing, & Feature Extraction

This project contains **Exploratory Data Analysis (EDA)** , **Data Cleaning**, **data preprocessing** and **Feature Extraction** on a medical insurance dataset. The main goal is to understand the features affecting insurance charges and prepare the data for machine learning tasks.

---

## 📁 Project Structure

```
├── insurance.csv            # Original dataset
├── clean_insurance.csv      # Cleaned & preprocessed dataset for ML
├── insurance.ipynb          # Jupyter Notebook with EDA and cleaning code
└── README.md                # Project documentation
```

---

## 📌 Dataset Description

The dataset contains demographic and medical details of individuals along with their medical insurance charges.

### Features in `insurance.csv`:
- `age`: Age of the individual
- `sex`: Gender
- `bmi`: Body Mass Index
- `children`: Number of children/dependents
- `smoker`: Smoking status (yes/no)
- `region`: Residential region in the US
- `charges`: Individual medical costs billed by health insurance

---

## 🧼 What’s in `clean_insurance.csv`?

The cleaned dataset has been:
- Checked and cleaned for missing values
- Encoded categorical variables (`sex`, `smoker`, `region`)
- Outliers handled (where applicable)
- Ready for machine learning models

---

## 📒 Notebook: `insurance.ipynb`

This notebook includes:
- 📌 Descriptive statistics
- 📊 Visualizations (distributions, boxplots, heatmaps)
- 🧼 Data cleaning and encoding steps
- 💾 Saving the final clean dataset to `clean_insurance.csv`

---

## 🚀 How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/insurance-dataset-analysis.git
   cd insurance-dataset-analysis
   ```

2. **Open the notebook**:
   ```bash
   jupyter notebook insurance.ipynb
   ```

3. **Run all cells** to perform EDA and generate the cleaned dataset.

---

## 📦 Requirements

Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## ✅ What's Next?

You can now use `clean_insurance.csv` for:
- Regression modeling (e.g., predicting `charges`)
- Exploratory ML experiments
- Statistical feature analysis

---

## 🤝 Contributions

Feel free to fork the repo and submit pull requests if you want to improve this project or add ML models on top of the cleaned data.

---

## 📄 License

This project is open-source and available under the MIT License.
