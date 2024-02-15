# Crime-Severity-Prediction
Prediction severity of crime based on LA crime dataset

Overview:
This repository contains code for predicting the severity of crimes based on the Los Angeles (LA) crime dataset. The goal is to develop machine learning models that can accurately classify crimes into categories based on their severity. The severity prediction can assist law enforcement agencies and policymakers in allocating resources more effectively and implementing targeted crime prevention strategies.

Dataset:
The LA crime dataset used in this project consists of various features related to each reported crime, including location, time, type of crime, and other relevant attributes. The dataset is preprocessed and cleaned to ensure data quality and consistency before being used for model training and evaluation.

Models:
Several machine learning models are implemented and evaluated for crime severity prediction. These models include decision trees, logistic regression, and potentially others depending on the performance and requirements of the task. The models are trained on historical crime data and tested on unseen data to assess their predictive accuracy and generalization capability.

Evaluation Metrics:
The performance of each model is evaluated using standard classification metrics such as precision, recall, F1-score, accuracy, and area under the ROC curve (AUC). These metrics provide insights into the model's ability to correctly classify crimes into different severity categories and its overall predictive performance.

Code Structure:
- `data/`: Contains the LA crime dataset and any additional data files used in the project. Since the dataset is large, It is not uploaded in reposiroty however can be downloaded from Data.gov Site "https://catalog.data.gov/dataset/crime-data-from-2020-to-present"
- `notebooks/`: Jupyter notebooks for data exploration, preprocessing, model training, and evaluation.
- `src/`: Source code files for preprocessing, modeling, and evaluation.
- `reports/`: Generated reports, including model evaluation summaries, visualization outputs, and any other relevant documentation.
- `README.md`: This file, providing an overview of the project, dataset, models, and code structure.

Usage:
1. Clone the repository to your local machine.
2. Navigate to the `notebooks/` directory to explore the Jupyter notebooks for data analysis and model development.
3. Use the provided scripts in the `src/` directory for data preprocessing, model training, and evaluation.
4. Refer to the documentation and comments within the code for detailed explanations of each step and function.

Requirements:
- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- scikit-learn
- Matplotlib
- Seaborn

Contributing:
Contributions to the project are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.

License:
This project is licensed under the MIT License. See the LICENSE file for more details.
