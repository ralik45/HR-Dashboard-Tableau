# HR Dashboard Project 🚀

Welcome to the **HR Dashboard Project**! This repository showcases an interactive HR dashboard built to provide data-driven insights for effective workforce management. The project aims to create a comprehensive tool for monitoring key HR metrics, understanding workforce composition, and identifying trends to support strategic decision-making.

## 📊 **Project Overview**

The goal of this project was to develop a dashboard that empowers HR managers with both high-level insights and the ability to perform detailed analysis on employee data. By leveraging a combination of summary views and detailed records, the dashboard addresses critical HR questions related to employee demographics, compensation, and performance.

### **User Story**

As an HR manager, I want a comprehensive dashboard to analyze human resources data, providing both summary views for high-level insights and detailed employee records for in-depth analysis.

## 🔍 **Analyze Requirements**

The dashboard is divided into two main views:

1. **Summary View**:
   - **Overview**: Provides a snapshot of overall HR metrics
   - **Demographics**: Offers insights into workforce composition
   - **Income Analysis**: Focuses on salary-related metrics

2. **Employee Records View**:
   - Comprehensive list of all employees with detailed information

## ⚙️ **Data Preparation**

The dataset includes various attributes such as Employee ID, Gender, State, City, Department, Job Title, Hire Date, Termination Date, Education Level, Performance Ratings, Overtime Status, and Salary.

1. **Data Generation**: Used a custom Python script to create synthetic data reflecting real-world HR scenarios.
2. **Data Cleaning**: Checked data types, handled missing values, and ensured data consistency.
3. **Calculated Fields**: Created calculated fields for metrics.

## 🛠️ **Building Charts**

### Overview Section
- Total number of hired employees, active employees, and terminated employees
- Visualization of hired and terminated employees over the years
- Breakdown of employees by department and job titles
- Comparison of employees between headquarters (HQ) and branches
- Distribution of employees by city and state
- ![overview](https://github.com/user-attachments/assets/853e2408-4ff4-4b29-bd80-7e1a0217aef8)

### Demographics Section
- Gender ratio in the company
- Distribution of employees across age groups and education levels
- Correlation between educational backgrounds and performance ratings
- ![Demographics](https://github.com/user-attachments/assets/3254ceae-2597-4721-8bb3-a6b65c4020b6)

### Income Analysis Section
- Salary comparisons across different education levels for both genders
- Correlation between age and salary for employees in each department
- ![Income](https://github.com/user-attachments/assets/c31308ec-63ed-4625-9d0a-7bcbbf2dcd78)

### Employee Record View Section
- Comprehensive list of all employees with necessary information such as name, department, position, gender, age, education, and salary
- Implement filters for all available columns to allow for detailed analysis and easy information retrieval
- ![image](https://github.com/user-attachments/assets/b071e8d2-28ed-4669-b54c-8a7cccca3812)

## 📊 **Building Dashboard**

### Planning
1. Draw mockup for dashboard
   - Overview:
   - ![Mockup Dashboard](https://github.com/user-attachments/assets/7fdf1631-6b72-486b-8504-55a94eaad4cc)
   - Details:
   - ![Mockup_HR Dashboard_Details](https://github.com/user-attachments/assets/894f90c2-ad89-4734-8ca7-3fb1297074d4)
2. Create container structure for dashboard
   - Overview:
   - ![image](https://github.com/user-attachments/assets/ac6e6769-6f7f-4975-ad71-395172c21e83)
   - Details:
   - ![image](https://github.com/user-attachments/assets/480a4156-2fbc-43d4-bc0e-1b8866e31550)

### Implementation
1. Develop the Overview section with key metrics and visualizations
2. Create the Details section with comprehensive employee records and filtering options

## 📈 **The Results**

The final dashboard provides:
- An Overview section with high-level HR metrics and visualizations
- ![HR_Dashboard_Overview](https://github.com/user-attachments/assets/94cd2277-693c-400d-ac13-6a528aa098f9)

- A Details section allowing for in-depth analysis of individual employee records
- ![HR_Dashboard_Details](https://github.com/user-attachments/assets/06bac282-135a-466e-998e-3ba9beef7b52)

- Explore the interactive HR dashboard on Tableau: [**HR Dashboard**](https://public.tableau.com/views/HRDashboard_17273434740000/HRSummary?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

## 🛠️ **Technologies Used**
- **Python** (Data Generation and Preparation)
- **Pandas** and **NumPy** (Data Manipulation)
- **Faker** (Synthetic Data Creation)
- **Tableau** (Data Visualization and Dashboard Creation)

## 🤝 **Acknowledgments**
I want to extend my gratitude to **Baraa Khatib Salkini** for his fantastic tutorial on YouTube, which greatly helped me throughout this process!

## 💻 **Project Repository**
You can find the complete code and dataset used for this project in this repository. Feel free to explore, fork, and contribute!

👉 **GitHub Repository**: [**HR Dashboard Project**](https://github.com/ralik45)

---

If you have any suggestions or feedback, feel free to open an issue or reach out. Let’s connect and discuss more about data-driven solutions for HR management! 😊

#HRAnalytics #DataAnalyst #Tableau #WorkforceManagement
