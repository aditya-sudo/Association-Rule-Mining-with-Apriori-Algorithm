# Association Rule Mining with Apriori Algorithm

This project implements the Apriori algorithm to mine association rules from a movie-watching dataset, treating users as transactions and movies as items. The goal is to discover interesting patterns in user behavior based on their watched movies.

## 📌 Objectives

- Understand and implement the Apriori algorithm from scratch.
- Transform raw movie-watching data into transactions.
- Generate frequent itemsets with minimum support threshold.
- Derive strong association rules using confidence metrics.
- Analyze and interpret the resulting rules to uncover patterns in user preferences.

## 🛠 Tools and Technologies

- Python 3
- Pandas
- Numpy
- Custom implementation (no external ML libraries used for mining)

## 📊 Dataset

- **Source**: Provided by the course (George Mason University, CS 584)
- **Format**: Two-column CSV (user ID, movie ID)
- **Preprocessing**: Transformed into a transaction list (movies watched per user)

## 📈 Results

- Frequent itemsets discovered with **minimum support = 0.2**
- Association rules derived with **minimum confidence = 0.8**
- Patterns reveal common co-watched movies among users
- Results validate the correctness and efficiency of the Apriori implementation

## 🎓 Learning Outcomes

- Gained hands-on experience with association rule mining techniques
- Learned how to preprocess transactional data for pattern discovery
- Reinforced understanding of support, confidence, and lift in rule mining
- Practiced writing clean, modular Python code for data mining

## 📁 File Structure

- `Association Rule Mining with Apriori Algorithm.ipynb` – Jupyter notebook containing code, results, and explanations
