# 🚗 Car Price Prediction using Machine Learning

A Machine Learning project that predicts the **price of used cars** based on historical car data. The project covers data preprocessing, exploratory analysis, feature preparation, model development, and price prediction using Python and machine learning techniques.

---

## 📌 Project Overview

Buying or selling a used car can be difficult because the market price depends on several factors such as:

* Car brand and model
* Year of purchase
* Kilometers driven
* Fuel type
* Transmission
* Seller information
* Vehicle condition and other characteristics

This project uses a used-car dataset to analyze these factors and build a machine learning-based approach for predicting car prices.

The complete workflow is implemented in a **Jupyter Notebook**.

---

## 🎯 Objectives

The main objectives of this project are:

* Understand the factors affecting used-car prices.
* Clean and preprocess raw car-price data.
* Perform exploratory data analysis.
* Prepare the dataset for machine learning.
* Build a regression-based prediction model.
* Predict the estimated price of a used car.
* Understand the complete machine learning workflow from data preprocessing to prediction.

---

## ✨ Key Features

* 📊 Data exploration and analysis
* 🧹 Data cleaning and preprocessing
* 🔍 Feature analysis
* 🤖 Machine Learning regression
* 🚗 Used-car price prediction
* 📓 Jupyter Notebook implementation
* 📁 Raw and cleaned datasets included
* 🐍 Python-based implementation

---

## 🧠 Machine Learning Workflow

```text
Raw Dataset
     ↓
Data Loading
     ↓
Data Cleaning
     ↓
Data Preprocessing
     ↓
Exploratory Data Analysis
     ↓
Feature Selection / Preparation
     ↓
Model Training
     ↓
Model Evaluation
     ↓
Car Price Prediction
```

---

## 📂 Dataset

The project uses a **Quikr used-car dataset**.

The repository contains both the original and processed datasets:

```text
Quikr car price prediction.csv
cleaned_data.csv
```

The raw dataset contains information related to used cars, while `cleaned_data.csv` contains the processed version used for analysis and modelling.

### Dataset Characteristics

The dataset contains information related to factors such as:

| Feature           | Description                    |
| ----------------- | ------------------------------ |
| Car Name          | Name/brand of the car          |
| Year              | Year of manufacture/purchase   |
| Selling Price     | Target price of the car        |
| Kilometers Driven | Distance travelled by the car  |
| Fuel Type         | Type of fuel used              |
| Transmission      | Transmission type              |
| Owner             | Previous ownership information |
| Seller Type       | Type of seller                 |

> The exact columns depend on the dataset version used in the notebook.

---

## 🛠️ Technologies Used

### Programming Language

* **Python**

### Libraries

* **Pandas** — Data manipulation and preprocessing
* **NumPy** — Numerical operations
* **Matplotlib** — Data visualization
* **Seaborn** — Exploratory data analysis
* **Scikit-learn** — Machine Learning

### Development Environment

* Jupyter Notebook
* Python Virtual Environment

---

## 📁 Project Structure

```text
car-price-prediction/
│
├── Quikr car price prediction.csv
│       # Original dataset
│
├── cleaned_data.csv
│       # Cleaned and processed dataset
│
├── prediction.ipynb
│       # Complete machine learning workflow
│
├── requirements.txt
│       # Python dependencies
│
└── README.md
        # Project documentation
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yasha-2006/car-price-prediction.git
```

Navigate into the project directory:

```bash
cd car-price-prediction
```

---

### 2. Create a Virtual Environment

Windows:

```powershell
python -m venv venv
```

Activate the environment:

```powershell
venv\Scripts\activate
```

For macOS/Linux:

```bash
source venv/bin/activate
```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

This project is implemented using Jupyter Notebook.

Start Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
prediction.ipynb
```

Run the notebook cells sequentially to:

1. Load the dataset
2. Inspect the data
3. Clean the data
4. Perform preprocessing
5. Analyze the features
6. Train the prediction model
7. Evaluate the model
8. Generate car-price predictions

---

## 🔬 Project Process

### 1. Data Collection

The project begins with the raw used-car dataset:

```text
Quikr car price prediction.csv
```

The dataset is loaded into Python using Pandas.

---

### 2. Data Cleaning

The raw data is inspected for:

* Missing values
* Duplicate records
* Incorrect data types
* Inconsistent values
* Unnecessary columns
* Irregular text/numerical representations

The cleaned dataset is saved as:

```text
cleaned_data.csv
```

---

### 3. Exploratory Data Analysis

The dataset is analyzed to understand relationships between different car attributes and their prices.

Examples of analysis include:

* Price distribution
* Relationship between year and price
* Effect of kilometers driven
* Fuel-type analysis
* Brand/model comparison
* Feature relationships

Visualization libraries such as **Matplotlib** and **Seaborn** are used for graphical analysis.

---

### 4. Feature Preparation

Relevant features are selected and transformed into a format suitable for machine learning.

Categorical features may require encoding before being provided to the regression model.

---

### 5. Model Training

A regression-based machine learning approach is used to learn the relationship between car attributes and their selling prices.

The model learns patterns from historical car-price data and uses those patterns to estimate the price of previously unseen vehicles.

---

### 6. Prediction

After training, the model can estimate the expected price of a car based on its available features.

Conceptually:

```text
Car Features
     ↓
Preprocessing
     ↓
Trained ML Model
     ↓
Predicted Car Price
```

---

## 📊 Model Evaluation

The trained model can be evaluated using common regression metrics such as:

### Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted prices.

### Mean Squared Error (MSE)

Measures the average squared difference between actual and predicted values.

### Root Mean Squared Error (RMSE)

Measures prediction error in the same unit as the target variable.

### R² Score

Measures how well the model explains the variation in car prices.

A higher R² score generally indicates better explanatory performance, while lower MAE/RMSE values indicate smaller prediction errors.

---

## 💡 Example Prediction Workflow

A user provides information about a used car:

```text
Car Model
Year
Kilometers Driven
Fuel Type
Transmission
Owner Information
```

The system processes these inputs and passes them to the trained regression model.

```text
Input Car Information
        ↓
Data Preprocessing
        ↓
Feature Transformation
        ↓
Regression Model
        ↓
Estimated Selling Price
```

---

## 📈 Expected Outcome

The project demonstrates how Machine Learning can be applied to a real-world regression problem.

The final model can be used as a foundation for applications such as:

* Used-car valuation
* Online car marketplaces
* Dealer price estimation
* Buyer decision support
* Vehicle resale analysis

---

## 🚀 Future Improvements

The project can be extended with:

* [ ] Compare multiple regression algorithms
* [ ] Hyperparameter tuning
* [ ] Cross-validation
* [ ] Feature importance analysis
* [ ] Advanced feature engineering
* [ ] Interactive prediction interface
* [ ] Flask-based web application
* [ ] REST API for predictions
* [ ] Cloud deployment
* [ ] Model monitoring
* [ ] Improved dataset with more recent vehicle listings

---

## 📚 Learning Outcomes

Through this project, the following concepts are demonstrated:

* Python programming
* Pandas and NumPy
* Data cleaning
* Exploratory Data Analysis
* Data visualization
* Feature preprocessing
* Regression
* Machine Learning model training
* Model evaluation
* Real-world price prediction
* Jupyter Notebook workflow

---

## 🔗 Repository

**GitHub Repository:**

https://github.com/yasha-2006/car-price-prediction

---

## 👩‍💻 Author

**Yashashree M**

B.E. Artificial Intelligence and Machine Learning

---

## 📄 License

This project is created for **educational and learning purposes**.

---

⭐ If you find this project useful, consider giving the repository a star!
