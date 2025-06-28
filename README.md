## 📈 Sales Prediction Using Python

### 🧠 Task-4: Data Science Internship Project

This project involves building a **sales prediction model** using advertising data. By applying linear regression, we aim to predict product sales based on advertising budget across TV, Radio, and Newspaper channels.

---

### 👨‍💻 Author

* **Name:** Tushar Surja
* **Batch:** June 2025, B33
* **Domain:** Data Science

---

### 🎯 Objective

To develop a machine learning model using Python that predicts **sales revenue** based on different advertising expenditures.

---

### 📂 Dataset

**File:** `advertising.csv`
**Features:**

* `TV`: TV advertising budget
* `Radio`: Radio advertising budget
* `Newspaper`: Newspaper advertising budget
  **Target:**
* `Sales`: Units sold

---

### 🔧 Tools & Libraries

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

### 📊 Project Workflow

1. **Data Loading**

   * Load the `advertising.csv` file into a DataFrame using Pandas.

2. **Exploratory Data Analysis (EDA)**

   * Compute correlation matrix
   * Create scatter plots for each advertising medium vs. Sales

3. **Data Preparation**

   * Define features (`TV`, `Radio`, `Newspaper`)
   * Define target (`Sales`)
   * Split data into training and testing sets (80/20 split)

4. **Model Training**

   * Train a `LinearRegression` model using training data

5. **Model Evaluation**

   * Predict sales on the test set
   * Evaluate with:

     * Mean Squared Error (MSE)
     * R² Score

---

### ✅ Results

The model shows how different advertisement channels affect sales. With metrics like MSE and R² score, we assess the prediction performance.

---

### 📌 Conclusion

This project demonstrates how linear regression can be applied in real-world business scenarios, particularly for marketing budget optimization.
