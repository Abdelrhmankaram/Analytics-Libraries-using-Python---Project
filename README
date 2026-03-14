# 📊 User Demographics & Exploratory Data Analysis (EDA)

### 🌟 Project Preview
This project involves a comprehensive exploratory data analysis (EDA) of a user dataset consisting of 208 records and 29 distinct features. The primary objective is to clean, process, and analyze user profiles—including demographics (age, gender, city), physical attributes (height, weight), and professional backgrounds—to uncover underlying patterns and trends within the user base.

---

### 📈 Charts and Analysis

#### 👥 Gender Demographics
* **User Count by Gender**
  ![Count by gender](<Plots/Count by gender.png>)
  *A breakdown of the dataset showing the total number of male versus female participants.*

* **Average Age by Gender**
  ![Average Age by Gender](<Plots/Average Age by Gender.png>)
  *A comparison of the mean age across genders to identify demographic balance.*

#### 📏 Physical Attributes & Trends
* **Height and Weight Distribution**
  ![Height and Weight distribution](<Plots/Height and Weight distribution.png>)
  *Visualizing the spread and frequency of physical metrics across the user base.*

* **Relationship Between Age, Height, and Weight**
  ![Relationship between age and height, weight](<Plots/Relationship between age and height, weight.png>)
  *Regression analysis exploring how age correlates with physical characteristics.*

#### 📍 Geographic Insights
* **Top 10 Cities with Most Users**
  ![Top 10 Cities with most users](<Plots/Top 10 Cities with most users.png>)
  *Identification of the primary urban hubs where the user population is most concentrated.*

---

### 💡 Business Questions Answered
* **What is the age profile of our users?** The average age of the user base is approximately **33.14 years**, indicating a predominantly millennial audience.
* **Are there physical attribute correlations?** Analysis shows a slight positive correlation between age and weight ($0.067$) but a negative correlation between height and weight ($-0.088$).
* **How complete is our user data?** While most fields are 100% complete, the `maidenName` field is missing for 148 users, suggesting it is a non-mandatory field for the majority of the population.

---

### 🛠️ What I Did
1. **Data Acquisition:** Fetched data through a multi-page API process and exported it to a local CSV format.
2. **Structural Audit:** Verified data shapes, column names, and data types (Integer, Float, and Object).
3. **Data Cleaning:** * Extracted the `city` field from nested JSON-like strings within the `address` column using `ast.literal_eval`.
    * Handled missing values in critical numeric columns (`age`, `height`, `weight`) by imputing them with the **median** values.
4. **Statistical Profiling:** Conducted descriptive statistics and duplicate checks to ensure data integrity.

---

### 🔑 Key Insights
* **Data Consistency:** The dataset contains no duplicate rows, indicating high-quality data collection.
* **Physical Metrics:** The average height in the dataset is **175.72 cm**, while the average weight is **75.04 kg**.
* **Age Range:** The user base is composed of young to middle-aged adults, ranging from **23 to 46 years old**.

---

### 📁 Project Structure
```text
├── Plots/               # Saved visualization images
├── Project.ipynb        # Main analysis notebook
├── user.csv             # Raw/Processed dataset
├── read.py              # Script for API data fetching
└── README.md            # Project documentation
```
---

### 💻 Tech Stack
* **Language:** Python

* **Data Manipulation:** Pandas, NumPy

* **Visualization:** Seaborn, Matplotlib

* **Data Parsing:** json, ast (for literal evaluation of nested strings)

---

### 🚀 How to Run
1. **Clone the Repository:**
    ```bash
    git clone https://github.com/Abdelrhmankaram/Analytics-Libraries-using-Python---Project
    ```
2. **Install Dependencies:**
    ```bash
    pip install pandas numpy seaborn matplotlib
    ```

3. **Fetch Data (Optional):**
    Run the `fetch_api_data()` function within the notebook or via the `read.py` script to update the `user.csv`.

4. **Launch Notebook:**
    Open `Project.ipynb` in Jupyter Notebook or VS Code to view the full analysis.