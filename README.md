# Data Analysis and Visualization using Apache Spark

##  Project Overview
This project demonstrates how to perform **data analysis and visualization** using **Apache Spark**.  
The dataset contains employee records including ID, name, age, department, and salary.  
Through Spark DataFrame APIs, we perform data cleaning, aggregation, transformations, and visualizations.

---

##  Features Implemented
The notebook is structured into multiple tasks (cells), each covering an aspect of analysis:

1. **Import Required Libraries & Initialize Spark**  
   - Setup SparkSession and required PySpark libraries.  

2. **Define Schema & Load Data**  
   - Load `employees.csv` with a predefined schema.  
   - Clean and cache the dataset for further processing.  

3. **Generate Summary Statistics**  
   - Compute count, mean, min, max, and standard deviation of numeric columns.  

4. **Department-Wise Analysis**  
   - Calculate average salary, average age, and employee count by department.  

5. **Find Highest and Lowest Salaries**  
   - Identify top 5 highest and lowest paid employees.  

6. **Salary Distribution**  
   - Categorize salaries into Low, Medium, and High ranges.  

7. **Employees Above Average Salary**  
   - Filter employees earning more than the average salary.  

8. **Add 10% Bonus to Salaries**  
   - Create a new column `SalaryAfterBonus` with a 10% increase applied.  

9. **Top 3 Salaries per Department**  
   - Use Window functions to rank and select top 3 employees in each department.  

10. **Age Distribution**  
    - Categorize employees into Young, Mid, and Senior groups.  

11. **Export Processed Data**  
    - Save cleaned and enriched data as CSV.  

12. **Visualization**  
    - Convert Spark DataFrame to Pandas and create visualizations (bar chart of average salary by department).  

13. **Stop Spark Session**  
    - Gracefully terminate the Spark session.  

---

##  Dataset
- **File**: `employees.csv`  
- **Columns**:  
  - `Emp_No` (Employee Number)  
  - `Emp_Name` (Employee Name)  
  - `Salary` (Annual Salary in INR)  
  - `Age` (Employee Age)  
  - `Department` (Employee Department)  

> Sample dataset is included in the project.  

---

##  Tech Stack
- **Apache Spark (PySpark)** — Data processing  
- **Python 3.x** — Programming language  
- **Matplotlib** — Visualization  
- **Pandas** — Conversion for visualization  

---

##  Example Visualizations
- **Average Salary by Department**  
- **Salary Distribution by Range**  
- **Age Group Distribution**  

---

##  How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/data-analysis-using-spark.git
   cd data-analysis-using-spark
   
2. Install required dependencies (if not already installed):

   pip install pyspark pandas matplotlib


3. Place the dataset (employees.csv) in the project root folder (or update the file path in code).

4. Run the notebook FinalProject.ipynb step by step.

---

## Results

~ Clean and enriched employee dataset with salary bonus applied.

~ Insights into salary ranges, department averages, and employee demographics.

~ Exported processed dataset for reuse.

~ Visual representation of employee statistics.

---

##  Author

Rosheni S.R
B.Tech in Artificial Intelligence & Data Science
Email: rosheniramesh@gmail.com
