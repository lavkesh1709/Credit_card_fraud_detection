# Credit_card_fraud_detection
This project utilizes machine learning techniques to detect fraudulent transactions in credit card datasets. The dataset used is highly imbalanced, containing a small percentage of fraud cases, so techniques like resampling are applied to handle this.

Key Features
Dataset: Credit card transactions dataset with a high imbalance between fraudulent and non-fraudulent transactions.
Data Preprocessing: Handling missing values, normalization, and dealing with class imbalance using resampling.
Model Training: Logistic regression model trained using gradient descent.
Evaluation: Performance metrics including F1 score, accuracy, precision, and recall to evaluate the model.
How to Use
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/credit-card-fraud-detection.git
cd credit-card-fraud-detection
Install the required packages:

bash
Copy code
pip install -r requirements.txt
Run the Jupyter Notebook to follow the step-by-step implementation and visualization of the results.

Results
The logistic regression model, trained on the preprocessed and balanced dataset, showed significant performance improvements in detecting fraudulent transactions, as demonstrated by key metrics such as F1 score, accuracy, precision, and recall.

Acknowledgements
Dataset provided by Kaggle, originally from the research paper "Credit Card Fraud Detection with a Neural Network" by Andrea Dal Pozzolo, Olivier Caelen, Reid A. Johnson, Gianluca Bontempi.
License
This project is licensed under the MIT License. See the LICENSE file for more details.
