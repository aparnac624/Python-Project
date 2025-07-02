# Python-Project
ABC Company – Employee Data Analysis Project
-------------------------------------------------------------------
🎓 Python Module End Project

📁 Project Overview
--------------------------------------------------------------------
This project involves analyzing an employee dataset from ABC Company as part of the Python module’s final assessment. The dataset includes 458 rows and 9 columns with employee details such as age, team, position, salary, etc.

The project includes:
1. Data preprocessing
2. Exploratory data analysis (EDA)
3. Graphical representation
4. Key insights and a final data story

🛠️ Technologies Used
1. Python
2. Pandas
3. NumPy
4. Matplotlib
5. Seaborn
6. Jupyter Notebook

🔄 Preprocessing 
1. Replaced incorrect or missing values in the height column with random values between 150 and 180 cm using NumPy.
2. Checked for and handled missing or duplicate values.
3. Saved the cleaned dataset as cleaned_data.csv.

📈 Analysis Tasks 
1️⃣ Distribution of Employees by Team
1. Used value_counts() to count employees in each team.
2. Calculated percentage share of each team.
3. Created a bar chart and a clean pie chart (top 5 + Others) for visual clarity.

2️⃣ Employee Count by Position
1. Counted how many employees are in each position using value_counts().
2. Visualized with a horizontal bar chart for readability.

3️⃣ Predominant Age Group
1. Segmented ages into bins: 18–25, 26–35, 36–45, 46–60.
2. Identified the most common age group using pd.cut() and value_counts().
3. Plotted a bar chart for comparison.

4️⃣ Highest Salary Expenditure (Team & Position)
1. Used groupby().sum() to find total salary by team and by position.
2. Identified the top team and position in terms of salary cost.
3. Represented data using bar charts.

5️⃣ Correlation Between Age and Salary
1. Calculated correlation using df['age'].corr(df['salary']).
2. Plotted a scatter plot with a regression line to visualize the relationship.

📊 Graphical Representations 
- Each analysis above is supported with:
    1. Bar Charts
    2. Pie Chart
    3. Scatter Plot with Regression Line
- Visualizations made using Matplotlib and Seaborn

🧠 Data Story / Insights 
1. Most employees are in the Development and Sales teams.
2. The 26–35 age group is the most common among employees.
3. Managers have the highest salary cost among positions.
4. Development is the team with the highest salary expenditure.
5. There is a moderate positive correlation between age and salary, indicating that salary generally increases with experience.

📂  Repository Structure
----------------------------------
Python Project - ABC Company Employee Analysis/
├── dataset.xlsx
├── end_project.ipynb
└── README.md
 
✅ How to Run
1. Clone this repo or download as ZIP.
2. Open end_project.ipynb in Jupyter Notebook.
3. Run the cells step-by-step.
4. View charts and results interactively.



