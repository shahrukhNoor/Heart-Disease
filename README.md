README - Heart Disease Prediction Project
-----------------------------------------------------

Project Title: Heart Disease Prediction using Logistic Regression
Dataset: UCI Heart Disease (Cleveland)
Source: https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci

-----------------------------------------------------
ABOUT THE PROJECT
This project predicts if a person has heart disease using basic medical data such as age, cholesterol, and blood pressure.
It uses Logistic Regression, a simple and easy-to-understand model.

-----------------------------------------------------
FILES INCLUDED
1. HeartDisease_Project.docx        - Report with research questions, model, and results
2. HeartDisease_Presentation.pptx   - PowerPoint summary of the project
3. heart_disease_project.py         - Python code for data preparation, training, and testing
4. preprocessed_heart_SAMPLE.csv    - Example of preprocessed dataset output
5. README.txt                       - This instruction file

-----------------------------------------------------
HOW TO RUN (Google Colab)
1. Create a folder named 'data' in your Colab environment.
2. Upload the dataset file (heart_cleveland_upload.csv) inside the 'data' folder.
3. Run this command in Colab:
   !python heart_disease_project.py
4. The outputs will appear in a folder named 'outputs'.

-----------------------------------------------------
HOW TO RUN (Local Computer)
1. Keep all files in one project folder.
2. Make a folder named 'data' and put heart_cleveland_upload.csv inside it.
3. Open a terminal or command prompt and run:
   python heart_disease_project.py
4. Check the 'outputs' folder for results:
   - preprocessed_heart.csv
   - metrics.txt
   - confusion_matrix.png

-----------------------------------------------------
NOTES
- If the dataset column for target is named 'condition', rename it to 'target' before running.
- Logistic Regression is used for binary classification (1 = heart disease, 0 = no heart disease).

-----------------------------------------------------
AUTHOR
Shahrukh Ali Noor
Business Intelligence and Data Science Course
