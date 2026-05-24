# ApexPlanet-Task1-Data-Immersion-Wrangling

## Project Description
This project was developed as part of the **ApexPlanet Data Analytics Internship Program**.

The purpose of this task was to work with a housing dataset and apply different data preprocessing techniques to improve data quality and prepare it for further analysis.

---

## Project Goals

- Study and understand the dataset
- Detect missing records
- Remove duplicate entries
- Fix data inconsistencies
- Identify and handle outliers
- Format column names properly
- Create useful new features
- Generate a final processed dataset

---

## Technologies Used

- Python
- Pandas
- NumPy
- CSV Files

---

## Project Contents

| File | Purpose |
|-------|----------|
| `housing_data_creator.py` | Creates the sample housing dataset |
| `data_cleaning_project.py` | Performs preprocessing operations |
| `housing_data.csv` | Original dataset |
| `cleaned_housing_data.csv` | Processed dataset |
| `README.md` | Project documentation |

---

## Process Followed

### Step 1: Dataset Import
Loaded the housing dataset into a Pandas DataFrame for processing.

### Step 2: Handling Missing Data
- Filled missing numerical values using median values
- Filled missing categorical values using mode values

### Step 3: Removing Duplicate Records
Duplicate entries were identified and removed to improve data accuracy.

### Step 4: Outlier Processing
Used the **IQR (Interquartile Range)** method to detect and control extreme values.

### Step 5: Feature Engineering
Added a new column:

```python
house_age = Current Year - Year Built
```

### Step 6: Saving the Final Dataset
Exported the cleaned dataset for future analysis and visualization.

---

## Knowledge Gained

- Data preprocessing techniques
- Data quality improvement methods
- Missing value handling
- Outlier detection methods
- Feature engineering concepts
- Practical use of Python for data analytics

---

## Final Output

✔ Clean and structured dataset

✔ Analysis-ready data

✔ Internship project completion

✔ Portfolio-ready GitHub project

---

## Internship Organization

**ApexPlanet Software Pvt. Ltd.**
