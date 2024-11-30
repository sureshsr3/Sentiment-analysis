# Sentiment-analysis of Redmine Issues

This project focuses on analyzing the sentiment of issues reported in Redmine by customers, clients, and staff. By leveraging advanced NLP techniques, including BERT, the system classifies and identifies the emotional tone of the reported issues, enabling better prioritization and decision-making.

Features
Sentiment Detection: Classifies text into various sentiment categories (e.g., Positive, Negative, Neutral).
BERT-based Analysis: Utilizes the BERT model for robust natural language understanding.
Multi-source Data Support: Handles diverse inputs from customers, clients, and staff.
Visual Insights: Generates graphs and charts to represent sentiment trends and distributions.



Methodology
Data Preparation:

Issues from Redmine are extracted and organized into CSV files (issue_emotions_detected.csv, issue_emotions_detected_old.csv, text.csv).
Preprocessed to clean and normalize the data for analysis.



Feature Extraction:

Uses BERT to extract contextual embeddings, capturing the nuanced meaning of the text.




Modeling:

Built sentiment classification models, including experiments with Logistic Regression (Logistic.ipynb).
Fine-tuned BERT for improved sentiment classification performance.
Evaluation and Visualization:

Evaluated model accuracy and generated visualizations to interpret results effectively.




Usage
Install Required Libraries:
Install dependencies by running:

pip install -r requirements.txt  
Run the Analysis:

Open and execute Logistic.ipynb to preprocess data, apply BERT embeddings, and train the sentiment analysis model.
Ensure all input files (issue_emotions_detected.csv, issue_emotions_detected_old.csv, text.csv) are placed in the working directory.



Output:

The output includes sentiment classifications and visualizations of sentiment trends in Redmine issues.





Applications
Customer Support Insights: Understand client emotions to improve service quality.
Staff Feedback Analysis: Analyze staff-reported issues to enhance internal processes.
Priority Setting: Identify critical issues based on sentiment for faster resolution.
Technologies Used
Python: For data processing and modeling.
BERT: For sentiment analysis and feature extraction.
Pandas/Numpy: For data manipulation.
Matplotlib/Seaborn: For visualizations.



Contributions
Contributions are welcome to enhance the model or extend the analysis to additional use cases.
