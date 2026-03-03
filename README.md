# 🚗 CO2 Emission Prediction Using Machine Learning

## 📌 Project Overview

This project analyzes **vehicle fuel consumption and CO₂ emissions in Canada** using **Python and Machine Learning**.
The goal is to understand how factors like **engine size, number of cylinders, and fuel consumption** affect vehicle **CO₂ emissions** and to build a **Linear Regression model** that predicts emissions.

This project demonstrates **data analysis, data preprocessing, machine learning modeling, and visualization** using Python.

---

# 📊 Dataset Information

The dataset contains information about different vehicles and their fuel consumption ratings.

### Dataset Features

* Make
* Model
* Vehicle Class
* Engine Size (L)
* Cylinders
* Transmission
* Fuel Type
* Fuel Consumption City (L/100 km)
* Fuel Consumption Highway (L/100 km)
* Fuel Consumption Combined (L/100 km)
* Fuel Consumption Combined (mpg)
* CO2 Emissions (g/km)

### Dataset Size

* **Rows:** 7385
* **Columns:** 12

The dataset is used to train a machine learning model to predict **CO₂ emissions**.

---

# 🧠 Machine Learning Model

This project uses **Linear Regression**, a supervised machine learning algorithm used for predicting continuous values.

### Input Features Used

* Engine Size (L)
* Cylinders
* Fuel Consumption Combined (L/100 km)

### Target Variable

* CO2 Emissions (g/km)

The model learns the relationship between these variables to estimate the amount of CO₂ emissions produced by a vehicle.

---

# ⚙️ Technologies Used

The project is built using the following tools and libraries:

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn

These libraries are used for **data manipulation, machine learning, and visualization**.

---

# 📈 Project Workflow

The project follows these steps:

### 1️⃣ Import Libraries

Import Python libraries needed for data analysis and machine learning.

### 2️⃣ Load Dataset

Load the vehicle emissions dataset using **Pandas**.

### 3️⃣ Data Exploration

Understand the dataset using:

* `head()`
* `info()`
* missing value checks

### 4️⃣ Data Cleaning

Remove missing values and prepare the dataset for modeling.

### 5️⃣ Data Encoding

Convert categorical variables into numerical format using **LabelEncoder**.

### 6️⃣ Feature Selection

Select the most relevant features affecting CO₂ emissions.

### 7️⃣ Feature Scaling

Normalize features using **StandardScaler**.

### 8️⃣ Train-Test Split

Split the dataset into:

* **80% training data**
* **20% testing data**

### 9️⃣ Model Training

Train a **Linear Regression model** using the training dataset.

### 🔟 Prediction

Use the trained model to predict CO₂ emissions.

### 1️⃣1️⃣ Model Evaluation

Evaluate the model using:

* R² Score
* Mean Squared Error (MSE)

### 1️⃣2️⃣ Visualization

Plot a graph comparing **actual vs predicted CO₂ emissions**.

---

# 📂 Project Structure

```
co2-emission-analysis
│
├── CO2 Emission canada.ipynb
├── CO2 Emissions_Canada.csv
├── requirements.txt
└── README.md
```

---

# ⚙️ Installation

Clone this repository:

```
git clone https://github.com/YOUR_USERNAME/co2-emission-analysis.git
```

Navigate to the project folder:

```
cd co2-emission-analysis
```

Install dependencies:

```
pip install -r requirements.txt
```

Run the Jupyter Notebook:

```
jupyter notebook
```

---

# 📊 Example Output

Model performance metrics may look like:

```
R2 Score: 0.86
Mean Squared Error: 150.23
Intercept: 120.45
Coefficients: [15.3, 10.7, 18.5]
```

The graph will show the relationship between **actual CO₂ emissions and predicted CO₂ emissions**.

---

# 🎯 Project Goal

The goal of this project is to:

* Understand the factors affecting vehicle emissions
* Apply machine learning for environmental data analysis
* Demonstrate a simple predictive model for CO₂ emissions

---

# 👨‍💻 Author

**Jain Leo**

GitHub:
https://github.com/jainleo2006jv-gif

---

# ⭐ Support

If you found this project helpful, please consider giving it a **⭐ star on GitHub**.
