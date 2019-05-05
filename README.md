# Breast-Cancer-Prediction
A highly accurate machine learning model to predict breast cancer
- The data was stored in aws S3 bucket.
- The Model was trained using AWS ML and integrated with Python using Boto AWS API.
- Used PCA for dimensionality reduction.
- For installing boto aws api - pip install boto3
- Create authentication keys using AWS IAM serivce for user.
- The Notebook consist of-
1. Data Exploration
2. Data Preprocessing
3. Feature Scaling
4. Dimensionality Reduction-PCA
5. AWS connection via boto3.
6. Training the ML Model to classify the cancer as benign or malignant.
7. Getting prediction response from the aws ml model in json format.
8. Plotting the accuracy graph.
