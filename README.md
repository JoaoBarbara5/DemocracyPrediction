# Democracy Classification: Analysis and Prediction from the United Nations General Debate Corpus 1946- 2024

## Description

 This study examines UN General Debate speeches from 1946 to 2024 using Natural Language Processing (NLP) methods to investigate their connection to democratic values, including government accountability as measured by the Worldwide Governance Indicators. It employs NLP to identify patterns that classify countries as democratic, autocratic, or transitional. The methodology involves text preprocessing, exploratory analysis to find mentions related to democracy, and SVM, SGD, Logistic Regression, and KNN machine learning models to assess predictability. The questions of how different types of government are mentioned in UN speeches over this period and, if and how it might be possible to predict a country’s democracy class from the speeches held at the yearly UN General Debate.

 ## Context

 The presented assignment was developed by the authors in the context of the course of Fundamentals of Data Science at the University of Amsterdam.

## Key Findings

The exploratory analysis demonstrates key patterns found in speeches of similar nature, as expressions and words from the lexical field of democracy and derivated terms.
The implementation of the machine learning model proved a positive classification effort, achieving maximum accuracy of 88% when classifying said countries according to their speeches.

## Contents

-DemocracyPrediction_NB.ipynb - The notebook containing the implemented methodologies for both anbalysis and prediction
-DemocracyPrediction.pdf - The report containing the description of methodologies and findings
-requirements.txt - A txt file with the libraries required to run the notebook
-DATA - A folder with the necessary data files in csv format

## How to Run the Project

1. Clone the repository
2. Create a virtual environment (e.g., python -m venv .venv).
3. Install the required packages: pip install -r requirements.txt.
4. Launch Jupyter Lab/Notebook and open DemocracyPrediction_NB.ipynb.