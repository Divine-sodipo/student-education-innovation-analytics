# student-education-innovation-analytics
Exploratory data analysis of student academic performance, innovation, entrepreneurship, internships, industry collaboration, and success using Excel, Python, and Power BI.
Student Education & Innovation Analytics

📌 Overview

This project is an exploratory data analysis of student education and innovation data, focusing on academic performance, course engagement, projects, innovation, entrepreneurship, internships, industry collaboration, startup funding, and student success.

The project demonstrates how raw student data can be transformed into meaningful insights using Microsoft Excel, Python, and Power BI.

The analysis combines exploratory data analysis with interactive dashboard development to provide a broader view of student academic and innovation-related activities.

⸻

🎯 Project Objective

The main objective of this project is to explore student-related data and identify patterns across academic performance, engagement, innovation, entrepreneurship, and industry exposure.

The analysis focuses on questions such as:

* How does student academic performance vary across the dataset?
* What patterns exist between course enrollment and completion?
* How are students distributed across internship statuses?
* What is the relationship between innovation scores and startup creation?
* Which students received the highest startup funding?
* How does project participation relate to student success?
* How does industry collaboration vary among students?
* What patterns can be observed across academic and innovation-related variables?

⸻

🗂️ Dataset

The dataset contains student-level information covering academic, innovation, entrepreneurship, and engagement-related attributes.

Dataset Features

Feature	Description
Student_ID	Unique identifier for each student
GPA	Student Grade Point Average
Courses_Enrolled	Number of courses enrolled
Completion_Rate	Percentage of courses completed
Quiz_Score	Student quiz performance
Project_Count	Number of projects completed
Innovation_Score	Student innovation score
Startup_Launched	Indicates whether a startup was launched
Funding_Received	Funding received by student startups
ILSTM-ACNN_Prediction	Prediction value provided in the dataset
Industry_Collab	Industry collaboration measure
Internship_Status	Student internship status
Success_Label	Recorded student/project success label

⸻

🛠️ Tools & Technologies

Microsoft Excel

Used for:

* Initial data inspection
* Data organization
* Preliminary analysis
* Understanding the structure of the dataset

Python

Used for exploratory data analysis and visualization.

Main Python libraries:

* Pandas — data manipulation and analysis
* Matplotlib — data visualization
* Seaborn — statistical visualization

Power BI

Used to create an interactive dashboard for presenting the findings and allowing users to explore the dataset visually.

SQL was not used in this project.

⸻

🔄 Project Workflow

Raw Dataset
     │
     ▼
Data Inspection
     │
     ▼
Data Cleaning & Validation
     │
     ▼
Exploratory Data Analysis
     │
     ▼
Python Visualizations
     │
     ▼
Power BI Dashboard
     │
     ▼
Insights & Data Storytelling

⸻

🔍 Exploratory Data Analysis

The analysis explored several major areas.

1. Academic Performance

Student GPA and quiz performance were examined to understand the distribution of academic achievement within the dataset.

2. Course Engagement

Course enrollment and completion rates were analyzed to explore student participation and completion behavior.

3. Project Participation

The number of projects completed by students was examined to understand levels of practical/project engagement.

4. Innovation

Innovation scores were explored across the student population and compared with startup activity.

5. Entrepreneurship

The analysis examined students who launched startups and explored the funding associated with those startups.

6. Internship Participation

Students were grouped according to internship status to understand internship participation within the dataset.

7. Industry Collaboration

Industry collaboration was analyzed as an indicator of students’ exposure to industry-related activities.

8. Student Success

The Success_Label variable was explored to understand the distribution of recorded success outcomes and its relationship with other variables.

⸻

📊 Visual Analysis

The Python analysis includes visualizations covering:

* Student GPA performance
* Course enrollment
* Completion rates
* Internship status
* Course enrollment by internship status
* Startup activity
* Innovation scores
* Startup funding
* Project participation
* Project participation vs. success
* Overall success distribution

⸻

📈 Power BI Dashboard

The Power BI dashboard converts the exploratory analysis into an interactive reporting experience.

It provides a visual overview of key student metrics and allows users to explore areas including:

* Academic performance
* Course engagement
* Innovation
* Project activity
* Startup creation
* Startup funding
* Internship participation
* Industry collaboration
* Student success

Dashboard Preview

Add your Power BI dashboard screenshot here.

![Power BI Dashboard](images/powerbi-dashboard.png)

⸻

🧹 Data Quality & Validation

Data quality was considered throughout the exploratory analysis.

The raw dataset contains 501 records, including an incomplete/anomalous record that requires attention when interpreting the data.

Missing values were also identified in some fields.

An unusually high value was observed within the Courses_Enrolled variable, which should be investigated as a possible data-entry or data-quality issue before using the variable for definitive conclusions.

These observations highlight the importance of validating real-world datasets before drawing conclusions from them.

⸻

💡 Key Analytical Areas

The project focuses on the relationship between several dimensions of student development:

                 Student Development
                         │
       ┌─────────────────┼─────────────────┐
       │                 │                 │
   Academics         Innovation       Engagement
       │                 │                 │
    GPA              Startups          Projects
    Quizzes          Funding           Courses
    Completion       Innovation        Internships
                                      Industry
                                      Collaboration

Rather than examining academic performance in isolation, the project considers multiple aspects of the student experience.

⸻

📂 Repository Structure

student-education-innovation-analytics/
│
├── README.md
│
├── data/
│   └── embedded_systems_students.csv
│
├── excel/
│   └── student_data.xlsx
│
├── python/
│   └── Innovation & Startup Insights EDA II.ipynb
│
├── powerbi/
│   └── Student Education Analytics.pbix
│
└── images/
    ├── powerbi-dashboard.png
    └── python-eda.png

Folder Description

Folder	Contents
data/	Raw dataset used for analysis
excel/	Excel version/workbook used during analysis
python/	Python notebook containing the EDA
powerbi/	Power BI dashboard file
images/	Screenshots and visual previews
README.md	Project documentation

⸻

🚀 Skills Demonstrated

This project demonstrates practical experience in:

* Data cleaning
* Data validation
* Exploratory Data Analysis
* Data manipulation
* Descriptive analysis
* Grouped analysis
* Data visualization
* Dashboard development
* Data storytelling
* Identifying data-quality issues
* Translating data into analytical questions
* Communicating insights visually

⸻

📌 Project Deliverables

The repository contains:

* 📄 Raw student dataset
* 📊 Excel analysis
* 🐍 Python EDA notebook
* 📈 Power BI dashboard
* 📝 Project documentation

⸻

🔮 Future Improvements

Possible extensions to the project include:

* Deeper statistical analysis
* Correlation analysis
* Student segmentation
* Additional Power BI drill-through pages
* More advanced dashboard interactivity
* Predictive modeling
* Feature engineering
* Deeper investigation of data-quality anomalies

⸻

📚 Conclusion

This project demonstrates an end-to-end approach to exploratory data analysis using Excel, Python, and Power BI.

The analysis brings together academic, innovation, entrepreneurial, project, internship, and industry-related variables to provide a broader perspective on student development.

The project also demonstrates the importance of data cleaning, validation, exploration, visualization, and communication when working with real-world datasets.

⸻

👤 Author

Jared Leto

Data Analytics Portfolio Project

Tools: Excel • Python • Pandas • Matplotlib • Seaborn • Power BI
