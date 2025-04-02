# 🎬 Movie Recommender & Knowledge Base — Python + Prolog Hybrid Project

This project implements a hybrid movie recommendation system using both **logical rules (Prolog)** and **data analysis in Python**.  
It was developed as part of a university assignment exploring **logic programming** and **collaborative filtering** techniques.

---

## 📂 Components

- `2ο Θέμα.ipynb`: Main notebook — processes ratings, computes recommendations, evaluates accuracy
- `PrologIntro.ipynb`: Introduction to Prolog syntax and logic queries
- `db.pl`: Prolog knowledge base with `genre/2` facts and similarity rules
- `movies_metadata.csv`: Movie information (titles, genres, IDs, etc.)
- `train_ratings.csv`: Training set of user ratings
- `test_ratings.csv`: Test set for evaluation

---

## 🧠 Objectives

- Understand Prolog's logic-based reasoning for content similarity
- Apply basic recommender system logic using pandas
- Combine symbolic and statistical AI methods
- Evaluate recommendations with precision-based metrics

---

## 🛠️ Technologies

- Python 3 (Jupyter Notebook)
- Pandas, NumPy
- Prolog (SWI-Prolog syntax)
- CSV Data handling

---

## 🔍 How It Works

- Prolog rule: `find_sim_1(X, Y) :- genre(X, G), genre(Y, G), X \= Y.`  
  Finds movies with shared genres.
- Python processes rating data and applies simple collaborative filtering.
- Final evaluation compares predicted recommendations with test set ratings.

---

## 🧪 Run Instructions

To run:
1. Open the notebooks in Jupyter or Google Colab.
2. For Prolog logic:
   - Load `db.pl` into SWI-Prolog
   - Query using `find_sim_1/2`, `genre/2`, etc.
3. For recommendation logic:
   - Run `2ο Θέμα.ipynb`

---

## 📚 Educational Use

This project is part of an AI course focused on **logic programming and data-driven systems**.  
All content is intended for learning and experimentation.

