# Credit Card Fraud Detection
Two machine learning models: one built with a Convolutional Neural Network and the other implementing K-Nearest Neighbor were designed to detect fraudulent Credit Card Transactions. 

## About
This project was made as a final requirement for a course on machine learning. It was run on google colab and the models were trained using  [this dataset from Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## How to use

### Download the files
A python notebook with all the details separated into sections is provided as well as .csv files with the datasets fit for both models.

### Google Drive
Once all the files are downloaded, place them in a google drive folder while taking note of the location of the folder in your google drive.

### Google Colab
Open the python notebook in a google colab, then edit the file path in the data set up portion of the code. Here's an example.

```python
#Read data from CSV Files
from google.colab import drive
drive.mount('/content/drive')
data_3 = pd.read_csv('drive/MyDrive/creditcard_3.csv')
data_28 = pd.read_csv('drive/MyDrive/creditcard_28.csv')
data_demo = pd.read_csv('drive/MyDrive/demo_set.csv')
knn_data_demo = pd.read_csv('drive/MyDrive/creditcard.csv')
```

### Finish
Run each section of the code. Both models would display their respective confusion matrices by the end of their demos.
