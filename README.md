# AdTracking-Fraud-Detection

- Analyzed dataset of over 200 million ad clicks and used machine learning techniques such as Logistic Regression, Random Forest, XGboost, SVM, and Recurrent Neural Network (RNN) to build model that could predict probability of an ad click being fraudulent.

- Performed exploratory data analysis (EDA), feature engineering, feature selection, latent dirichlet allocation (LDA), modeling, hyperparameter tuning and evaluated using area under receiver operating characteristics curve (AUCROC).


## Dataset Description

- For this project the objective is to predict whether a user will download an app after clicking a mobile app advertisement.

### Data fields

- Each row of the training data contains a click record, with the following features.

ip: ip address of click.
app: app id for marketing.
device: device type id of user mobile phone (e.g., iphone 6 plus, iphone 7, huawei mate 7, etc.)
os: os version id of user mobile phone
channel: channel id of mobile ad publisher
click_time: timestamp of click (UTC)
attributed_time: if user download the app for after clicking an ad, this is the time of the app download
is_attributed: the target that is to be predicted, indicating the app was downloaded
