# California House Price Prediction

##  Project Overview

This project predicts the **median house price in California** using Machine Learning techniques.
The model is trained on housing dataset features such as location, population, number of rooms, and median income.

The objective of this project is to build a regression model that can accurately estimate house prices based on given input features.

---

##  Dataset

This project uses the **California Housing Dataset**.

🔗 Dataset Link:
https://www.kaggle.com/datasets/camnugent/california-housing-prices

The dataset contains information about housing in California districts.

### Features

* Longitude
* Latitude
* Housing Median Age
* Total Rooms
* Total Bedrooms
* Population
* Households
* Median Income
* Ocean Proximity (Categorical Feature)

**Target Variable**

* Median House Value

---

##  Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Jupyter Notebook

---

##  Machine Learning Model

Model used in this project:

* Random Forest Regressor

### Steps Involved

1. Data Preprocessing
2. Handling Categorical Data using One-Hot Encoding
3. Train-Test Split
4. Model Training
5. Model Prediction

---

##  How to Run the Project

1️⃣ Clone the repository

```
git clone https://github.com/Mahakchoudhari/California_House_price_prediction_project.git
```

2️⃣ Install dependencies

```
pip install -r requirements.txt
```

3️⃣ Run the notebook or Python script

---

##  Example Prediction

Example Input:

* Median Income: 8.3252
* Total Rooms: 880
* Ocean Proximity: NEAR BAY

Output:

**Predicted House Price: ~$452,600**

---

##  Project Structure

```
California_House_price_prediction_project
│
├── housing.csv
├── house_prediction.ipynb
├── requirements.txt
└── README.md
```

---

##  Author

**Mehak Choudhari**
Machine Learning Student
