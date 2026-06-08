# DecodeLabs-Internship-project-2
🌸 Project 2 — KNN Iris Classifier
#Overview
A K-Nearest Neighbors classification model trained on the classic Iris dataset. The model classifies flowers into 3 species — Setosa, Versicolor, and Virginica — based on 4 features.
Tech Stack
Python · scikit-learn · pandas · matplotlib · seaborn
Dataset
FeatureDescriptionSepal LengthLength of sepal (cm)Sepal WidthWidth of sepal (cm)Petal LengthLength of petal (cm)Petal WidthWidth of petal (cm)TargetSetosa / Versicolor / Virginica
Pipeline
Load Iris Dataset
      ↓
Feature Scaling (StandardScaler)
      ↓
Train-Test Split (80/20)
      ↓
Train KNN Model (k=5)
      ↓
Predict on Test Set
      ↓
Evaluate (F1 Score + Confusion Matrix)
