# Titanic Data Preprocessing

This project demonstrates the data preprocessing workflow using the Titanic dataset. The objective is to clean and transform the raw data into a format that is ready for machine learning or further data analysis.

## 📌 Project Overview

The preprocessing steps include:

- Loading the Titanic dataset
- Exploring the dataset structure
- Checking summary statistics
- Identifying missing values
- Visualizing survival distribution
- Visualizing feature correlations
- Removing unnecessary columns
- Handling missing values
- Encoding categorical variables
- Exporting the cleaned dataset

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 📂 Project Structure

```
Titanic-Data-Preprocessing/
│
├── preprocessing
    ├── Eksperimen_NicholasGhonius.ipynb
    ├── titanic_preprocessing.csv
├── titanic_raw.csv
├── requirements.txt
└── README.md
```

## 📊 Data Preprocessing Steps

### 1. Data Exploration

- Display dataset information
- Generate descriptive statistics
- Check missing values

### 2. Data Visualization

- Survival distribution using Count Plot
- Correlation matrix using Heatmap

### 3. Data Cleaning

Removed columns that are not required:

- PassengerId
- Name
- Ticket
- Cabin

Handled missing values:

- Age → filled using Mean
- Embarked → filled using Mode

### 4. Feature Encoding

Categorical variables converted into numerical format using One-Hot Encoding:

- Sex
- Embarked

### 5. Export Processed Data

The cleaned dataset is saved as:

```
titanic_preprocessing.csv
```

## 📦 Requirements

Install the required libraries using:

```bash
pip install -r requirements.txt
```

Example `requirements.txt`

```text
pandas==2.2.2
numpy==1.24.3
matplotlib==3.9.2
seaborn==0.13.2
```

## 🚀 How to Run

1. Clone this repository

```bash
git clone https://github.com/yourusername/Titanic-Data-Preprocessing.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook

```
Eksperimen_NicholasGhonius.ipynb
```

## 📈 Output

The project produces:

- Data exploration report
- Missing value analysis
- Survival distribution visualization
- Correlation heatmap
- Cleaned dataset ready for machine learning

## 👤 Author

**Nicholas Ghonius**

- LinkedIn: https://www.linkedin.com/in/nicholasghonius-578882292
- GitHub: https://github.com/nooooooa
