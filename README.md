Overview:

This repository contains an independent study project comparing machine learning classification
models for predicting NBA player positions using advanced statistics. The project evaluates k-Nearest Neighbors (kNN) and 
Support Vector Machine (SVM) classifiers on data from two distinct NBA seasons, 2003–04 and 2024–25, to assess model performance across different eras of play.

Data:

The datasets include per-game and advanced statistics for NBA players, merged on player name. Features include:
Per-game stats: Games played (G), minutes played (MP), field goal attempts (FGA), three-point attempts (3PA), three-point percentage (3P%), three-point attempt rate (3PAr)
Advanced stats: Offensive rebound percentage (ORB%), defensive rebound percentage (DRB%), total rebound percentage (TRB%), assist percentage (AST%), steal percentage (STL%),
block percentage (BLK%), turnover percentage (TOV%), usage percentage (USG%)
The target variable is the player's position (Pos), with classes including PG, SG, SF, PF, and C.

Models Compared:

k-Nearest Neighbors (kNN)
Support Vector Machine (SVM)

Dependencies:

Python 3
pandas
scikit-learn (for kNN, SVM, and preprocessing)

Future Work:

Experiment with additional classifiers (e.g., Random Forest, XGBoost)
Incorporate multiple seasons for longer-term analysis and finding more subtle changes
Perform hyperparameter tuning with cross-validation
Visualize decision boundaries for selected feature pairs
