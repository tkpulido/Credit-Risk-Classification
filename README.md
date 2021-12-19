# Credit-Risk-Classification
This code analyzes the credit risk in regards to healthy loans and high-risk loans.  First, the orignal data is split to have a set of training and testing data which is then fitted to a logistical regression model used to predict the test data.  Next, a new set of data is generated to oversample the high-risk loan data to make up for the imbalance with the amount of healthy loans.  The same procedure is followed for this data.  Finally, the balanced accuracy score, confusion matrix, and imbalanced classification report is generated for both sets of data in which can be easily compared.

## Technologies
In order to run this code you will need scikit-learn and imbalanced-learn installed.

## Installation Guide

### Installing scikit-learn
pip install -U scikit-learn

### Installing imbalance-learn
conda activate dev
conda install -c conda-forge imbalanced-learn

### Importing Libraries and Dependencies
<img width="625" alt="Screen Shot 2021-12-19 at 12 30 20 PM" src="https://user-images.githubusercontent.com/89439442/146689845-a049ab2c-24d6-4861-a8c3-782b7ea18691.png">
<img width="625" alt="Screen Shot 2021-12-19 at 12 31 03 PM" src="https://user-images.githubusercontent.com/89439442/146689865-f48d0f1f-353c-4594-bdfe-5d7052b59acf.png">
<img width="625" alt="Screen Shot 2021-12-19 at 12 31 29 PM" src="https://user-images.githubusercontent.com/89439442/146689877-69d52a2a-ce9a-4368-b88f-0a161f060e71.png">
<img width="625" alt="Screen Shot 2021-12-19 at 12 32 32 PM" src="https://user-images.githubusercontent.com/89439442/146689904-d679e9fd-1245-425a-a215-a47ac0db7690.png">

## Usage

### Orignal Data
<img width="625" alt="Screen Shot 2021-12-19 at 12 28 16 PM" src="https://user-images.githubusercontent.com/89439442/146689786-f3ef6bf2-b9a3-4739-ac9f-48bb65c7a31b.png">

### Oversampled Data
<img width="625" alt="Screen Shot 2021-12-19 at 12 28 55 PM" src="https://user-images.githubusercontent.com/89439442/146689805-78244d9c-fcef-487d-b380-638e87877c43.png">

## Contributors

Tristen Pulido: tristenpulido@gmail.com
