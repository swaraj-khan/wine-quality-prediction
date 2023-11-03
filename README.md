# wine-quality-prediction

Data Analysis
In the initial stages, we perform data analysis to understand the dataset better. We explore the dataset's structure, check for missing values, generate summary statistics, and visualize correlations between features using heatmaps.

Data Preprocessing
Data preprocessing is a crucial step in any machine learning project. We create a new binary target variable, "goodquality," which equals 1 if the wine quality is 7 or higher and 0 otherwise. We split the data into input features (X) and the target variable (y) and prepare it for model training.

Model Building
We build two classification models to predict wine quality: Logistic Regression and K-Nearest Neighbors (KNN). The models are trained on the dataset, and their predictions are evaluated using accuracy scores. We compare the performance of both models to assess their classification capabilities.

Results
The project provides the following results:

Accuracy scores for Logistic Regression and K-Nearest Neighbors models, indicating how well they classify wine quality.
