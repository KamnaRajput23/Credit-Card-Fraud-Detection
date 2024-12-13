# Credit Card Fraud Detection

Detect credit card fraud using machine learning techniques to enhance transaction security and minimize fraudulent activities.

## Overview
This project aims to classify fraudulent and non-fraudulent credit card transactions using machine learning algorithms. The dataset used contains anonymized transaction data with features such as transaction amount, timestamp, and engineered principal components.

## Features
- Data preprocessing, including handling imbalanced datasets.
- Implementation of machine learning models (e.g., Logistic Regression, Random Forest, etc.).
- Evaluation metrics like accuracy, precision, recall, F1 score, and ROC-AUC.
- Visualization of results and insights from the dataset.

## Dataset
The dataset used is the [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). It contains:
- 284,807 transactions.
- 492 fraudulent transactions (0.172%).

## Installation
1. Clone the repository:
   bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
   
2. Navigate to the project directory:
   bash
   cd credit-card-fraud-detection
   
3. Install the required Python packages:
   bash
   pip install -r requirements.txt
   

## Usage
1. Preprocess the dataset:
   bash
   python preprocess.py
   
2. Train the model:
   bash
   python train.py
   
3. Evaluate the model:
   bash
   python evaluate.py
   
4. Visualize results:
   bash
   python visualize.py
   

## Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machines (SVM)

## Results
- Logistic Regression Accuracy: 0.9985253326779256
- Decision Tree Accuracy: 0.996892665285629
- Random Forest Accuracy: 0.9985253326779256
- SVM Accuracy: 0.9985253326779256

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

## License
This project is licensed under the MIT License. 

## Acknowledgements
- Dataset provided by [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
- Inspired by various open-source machine learning projects.

---

Feel free to reach out for any queries or collaboration opportunities.
