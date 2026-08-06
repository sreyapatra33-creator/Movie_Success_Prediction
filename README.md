# 🎬 Movie Success Prediction using Machine Learning

# 📖 Project Overview

The Movie Success Prediction project is a Machine Learning classification system that predicts whether a movie is likely to be a:

- 🎯 HIT
- ⭐ AVERAGE
- ❌ FLOP

The prediction is based on various movie-related features such as budget, Facebook likes, cast information, genres, reviews, and other metadata.

The project follows a complete end-to-end Machine Learning pipeline starting from raw data preprocessing to model evaluation and selection.

---

# 🎯 Project Objectives

✔ Clean and preprocess movie data

✔ Perform Exploratory Data Analysis (EDA)

✔ Handle missing values

✔ Encode categorical variables

✔ Remove multicollinearity

✔ Scale numerical features

✔ Train multiple Machine Learning models

✔ Perform Hyperparameter Tuning

✔ Compare model performance

✔ Select the Best Performing Model

---

# 📂 Project Structure

```
Movie-Success-Prediction/
│
├── Data_cleaning_Movie_Success.ipynb
├── EDA_Movie_Success.ipynb
├── Model_Traning_Movie_Success.ipynb
│
├── README.md
├── requirements.txt
│
└── Dataset
```

---

# 📊 Dataset Description

The dataset contains information related to movies, including:

- Movie Budget
- Director
- Actor Information
- Genres
- Facebook Likes
- Number of Reviews
- IMDB Score
- Language
- Country
- Duration
- Gross Collection
- Content Rating
- Release Year
- Aspect Ratio
- Movie Facebook Likes

Target Variable

IMDB Score
```
Classify

Flop
Average
Hit
```

---

# ⚙ Data Preprocessing

The following preprocessing techniques were performed:

### ✔ Missing Value Handling

- Median Imputation
- Mode Imputation

### ✔ Duplicate Removal

Duplicate records were checked and removed.

### ✔ Encoding

- Label Encoding
- Target Encoding

### ✔ Feature Engineering

- Feature Selection
- Removing Multicollinearity
- Data Transformation

### ✔ Feature Scaling

- RobustScaler

---

# 📈 Exploratory Data Analysis (EDA)

EDA includes:

- Scatter Plots
- Box Plots
- Heatmaps
- Correlation Matrix


The analysis helps understand feature relationships and identify important variables influencing movie success.

---

# 🤖 Machine Learning Models Used

The following classification models were trained and evaluated:

| Model |
|--------|
| Logistic Regression |
| Decision Tree |
| Random Forest |
| AdaBoost |
| Gradient Boosting |
| XGBoost|

---

# 🔧 Hyperparameter Tuning

The project includes hyperparameter tuning to improve model performance.

Techniques used:

- GridSearchCV
- Cross Validation

---

# 📊 Model Evaluation

Each model was evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

The best-performing model was selected based on evaluation metrics.

---

# 📌 Technologies Used

| Category | Libraries |
|-----------|-----------|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-Learn |
| Encoding | Category Encoders |
| Model Saving | Joblib |

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Movie-Success-Prediction.git
```

Move into the project folder

```bash
cd Movie-Success-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶ How to Run

Open Jupyter Notebook

```bash
jupyter notebook
```

Run notebooks in the following order:

```
1. Data Cleaning
        ↓
2. Exploratory Data Analysis
        ↓
3. Model Training
        ↓
4. Hyperparameter Tuning
        ↓
5. Model Evaluation
```

---

# 📊 Machine Learning Workflow

```
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
EDA
      │
      ▼
Feature Engineering
      │
      ▼
Encoding
      │
      ▼
Scaling
      │
      ▼
Train-Test Split
      │
      ▼
Model Training
      │
      ▼
Hyperparameter Tuning
      │
      ▼
Model Evaluation
      │
      ▼
Best Model
```

---

# 📌 Key Features

✅ End-to-End Machine Learning Project

✅ Well Structured Code

✅ Data Cleaning

✅ Exploratory Data Analysis

✅ Feature Engineering

✅ Multiple Classification Models

✅ Hyperparameter Tuning

✅ Model Comparison

✅ Professional Visualizations

---

# 🔮 Future Improvements

- Deep Learning Models
- Flask API Deployment
- Real-time Movie Prediction
- Feature Importance Dashboard

---

# 👨‍💻 Author

**Sreya Patra**

Machine Learning Enthusiast

---

# ⭐ Support

If you found this project helpful,

⭐ Star this repository

🍴 Fork this repository

📢 Share it with others

---

## Thank You ❤️
