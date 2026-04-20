# Student-Performance-Dashboard
A comprehensive dataset capturing academic, behavioural, and socio-economic attributes of university students to analyse and predict academic performance.
---
📌 Overview
This dataset contains survey and academic records of 1,194 undergraduate students enrolled in a Bachelor of Computer Science & Engineering (BCSE) program. It is designed to support research and machine learning projects focused on understanding the factors that influence student academic outcomes.
---
📂 Dataset Details
Attribute	Value
Total Records	1,194
Total Features	34
Program Covered	BCSE (Bachelor of Computer Science & Engineering)
Admission Years	2018 – 2022
Student Age Range	18 – 27 years
CGPA Range	0.0 – 4.0
File Format	`.xlsx`
---
🗂️ Features / Column Descriptions
🧑‍🎓 Student Demographics
Column	Description
`University Admission year`	Year the student was admitted
`Gender`	Male / Female
`Age`	Current age of the student
`H.S.C passing year`	Year of Higher Secondary Certificate completion
`Program`	Academic program (BCSE)
`Current Semester`	Semester the student is currently in
`With whom you are living with`	Living arrangement (Family / Bachelor / etc.)
`What is your relationship status`	Single / Relationship / Married / Engaged
📚 Academic Information
Column	Description
`How many hour do you study daily?`	Daily study hours
`How many times do you seat for study in a day?`	Number of daily study sessions
`What is your preferable learning mode?`	Online / Offline
`Average attendance on class`	Attendance percentage
`Did you ever fall in probation?`	Yes / No
`Did you ever got suspension?`	Yes / No
`Do you attend in teacher consultancy for any kind of academical problems?`	Yes / No
`What was your previous SGPA?`	Semester GPA from the previous term
`What is your current CGPA?`	Cumulative GPA
`How many Credit did you have completed?`	Total completed credit hours
💡 Skills & Interests
Column	Description
`What are the skills do you have?`	Primary skill area (e.g., Software Development, Networking)
`How many hour do you spent daily on your skill development?`	Hours per day on skill development
`What is you interested area?`	Area of professional/academic interest
🌐 Lifestyle & Habits
Column	Description
`Do you play mobile games?`	Yes / No
`Do you have personal Computer?`	Yes / No
`How many hour do you spent daily in social media?`	Social media usage hours per day
`Status of your English language proficiency`	Basic / Intermediate / Advance
`Are you engaged with any co-curriculum activities?`	Yes / No
🏫 Institutional & Socio-Economic
Column	Description
`Do you have meritorious scholarship?`	Yes / No
`Do you use University transportation?`	Yes / No
`What is your monthly family income?`	Family income in local currency
🏥 Health
Column	Description
`Do you have any health issues?`	Yes / No
`Do you have any physical disabilities?`	Yes / No
🎯 Target Variables
Column	Description
`Performance`	Academic performance label: `Low`, `Medium`, `High`
`Risk Flag`	Whether the student is `At Risk` or `Normal`
`Engagement Score`	Numeric score reflecting student engagement level
---
📊 Class Distribution
Performance
Category	Count	Percentage
Medium	665	55.7%
High	438	36.7%
Low	91	7.6%
Risk Flag
Category	Count
Normal	1,192
At Risk	2
Gender
Gender	Count
Male	672
Female	522
---
🔍 Potential Use Cases
Academic Performance Prediction — Build classification models to predict whether a student will perform at a Low, Medium, or High level.
Early Warning Systems — Identify at-risk students early in the semester using behavioural and academic indicators.
Engagement Analysis — Explore how study habits, attendance, and co-curricular activities correlate with engagement scores.
Socio-Economic Impact Study — Analyse how family income, scholarship status, and living arrangements affect academic outcomes.
Gender & Lifestyle Studies — Investigate differences in performance across gender, relationship status, and social media usage.
