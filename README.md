# 🏎️ Formula 1 Race Result Classification Challenge

Machine Learning project developed for the Formula 1 Race Result Classification Challenge hosted by Team Ascent on Kaggle.

## 📌 Overview

This project predicts Formula 1 driver finishing positions using over 70 years of historical Formula 1 data spanning from 1950 to 2022.

The challenge required participants to forecast race outcomes for the 2023–2024 seasons using pre-race information such as qualifying performance, championship standings, driver history, constructor performance, circuit characteristics, and recent race form.

## 🏆 Achievement

* Top 25 Finalist
* Competition Score (MAE): **2.705**
* Outperformed the baseline benchmark (~3.5–4.5 MAE)
* Competed against 348 entrants and 145 teams

## 📊 Dataset

The dataset contained:

* 25,840 training records
* 919 test records
* 26 engineered features

Key features included:

* Grid Position
* Driver Age
* Qualifying Times (Q1, Q2, Q3)
* Rolling Average Position
* Career Wins
* Championship Points
* Constructor Performance
* Circuit Characteristics
* Historical Driver Performance

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## 🔍 Machine Learning Workflow

### 1. Data Preprocessing

* Handled missing values
* Feature selection
* Data exploration
* Data validation

### 2. Feature Engineering

Created and analyzed features related to:

* Driver performance trends
* Constructor strength
* Qualifying pace
* Championship momentum
* Track characteristics

### 3. Model Development

Built and evaluated machine learning models to predict finishing positions while minimizing Mean Absolute Error (MAE).

### 4. Prediction & Submission

Generated race outcome predictions for the 2023–2024 Formula 1 seasons and submitted results to the competition leaderboard.

## 📈 Evaluation Metric

Mean Absolute Error (MAE)

Lower scores indicate better prediction accuracy.

Final Score:

MAE = 2.705

## 📂 Repository Structure

```text
formula1-race-result-classification/
│
├── f1-prediction.ipynb
├── submission.csv
├── requirements.txt
├── README.md
```

## 🚀 How to Run

```bash
git clone https://github.com/yourusername/formula1-race-result-classification.git

cd formula1-race-result-classification

pip install -r requirements.txt

jupyter notebook
```

Open:

```text
f1-prediction.ipynb
```

and run all cells.

## 📖 Competition Details

Goal:
Predict the finishing position of Formula 1 drivers using historical race, qualifying, championship, and constructor data.

Target:

```text
finishing_position
```

Evaluation:

```text
Mean Absolute Error (MAE)
```

## 👨‍💻 Author

Mukul

Aspiring Data Scientist | Machine Learning Enthusiast | Python Developer
