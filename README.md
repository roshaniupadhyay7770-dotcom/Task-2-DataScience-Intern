# Task-2-DataScience-Intern

## 📊 Operations Performed in the Project

### 1️⃣ Importing Libraries

The notebook starts by importing required Python libraries such as:

* **Pandas** → for handling data
* **NumPy** → for numerical operations
* **Matplotlib** → for visualization
* **Scikit-learn** → for building and evaluating the machine learning model

### 2️⃣ Loading the Dataset

* The dataset is loaded using `pandas.read_csv()`.
* Initial inspection is done using:

  * `.head()` → to view first few rows
  * `.info()` → to check data types
  * `.describe()` → to see statistical summary

### 3️⃣ Data Preprocessing

* Checking for missing values using `.isnull().sum()`
* Handling missing data (if present)
* Encoding categorical variables (if any)
* Selecting input features (X) and target variable (y)
* Splitting data into:

  * Training set
  * Testing set

### 4️⃣ Model Training

* A regression model (commonly Linear Regression) is created.
* The model is trained using `.fit()` on training data.

### 5️⃣ Making Predictions

* The trained model predicts sales using `.predict()` on test data.

### 6️⃣ Model Evaluation

The model performance is evaluated using:

* **MAE (Mean Absolute Error)**
* **MSE (Mean Squared Error)**
* **R² Score**

These metrics measure how accurate the predictions are.

### 7️⃣ Visualization

* Graphs are plotted using Matplotlib.
* Actual vs Predicted sales are compared visually.

## ✅ Overall Workflow

Data → Preprocessing → Train Model → Predict → Evaluate → Visualize Results
