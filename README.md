Dynasty Prediction using Machine Learning

Project Overview

This project predicts the historical dynasty of Indian monuments based on architectural and historical features using a Machine Learning model. It demonstrates how ML can be applied to cultural and historical data.

Tech Stack
1)Python

2)Pandas, NumPy

3)Scikit-learn

4)Dataset

The dataset contains information about Indian monuments and their characteristics such as type, architecture, and historical context.

Features:

Monument_Type
Year_Built
Patron_Ruler
State
Architectural_Style
Material
Religion
Target: Dynasty

Methodology

Data preprocessing and label encoding of categorical features

Model training using Random Forest Classifier

Prediction based on user input

How to Run

1)Ensure all files are in the same folder:
   predict_dynasty.py
   monuments.csv
   
2)Install required libraries:
    pip install pandas scikit-learn
    
3)Run the script:
    python predict_dynasty.py
    
4)Enter input values when prompted

Sample Output

Input:
Monument_Type: Temple
Year_Built: 1570

Output:
Predicted Dynasty: Vijayanagar

Key Learnings

Handling categorical data using Label Encoding

Training and evaluating ML models

Building interactive prediction systems

Note

This project was developed as part of the TNSkill Vetri Nichayam Machine Learning Program.
