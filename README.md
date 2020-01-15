# Address-validator-and-classifier

## Address Validation and Classification Using Text Classification & Real Time Web Results

Collection, cleaning and analyzing civic addresses open datasets for the Halifax region to classify them as Residential or Non-residential by creating a classification model and performing real-time web scraping to supplement the prediction.

### Classification Model

Implemented Random Forest Algorithm to classify address into Residential and Non Residential. To improve the performance and accuracy of the model hyperparameter tuning has been implemented.

### Real Time Web Results

To be more specific with the addresses a web scraper was added as a layer which scrapes the top 10 pages result from web. The text data extracted is cleaned and preprocessed using NLP methods. 

### Google API

To get the real time map view and street images google API's are add on in the code.

### Quick Links
1. [dataset](https://github.com/dintellect/Address-validator-and-classifier/blob/master/TestData_v8.csv)
2. [RF_Model Code](https://github.com/dintellect/Address-validator-and-classifier/blob/master/building_model.ipynb)
3. [Pretrained_Model](https://github.com/dintellect/Address-validator-and-classifier/blob/master/model.pkl)
3. [Final_Code](https://github.com/dintellect/Address-validator-and-classifier/blob/master/finalcode.ipynb)
