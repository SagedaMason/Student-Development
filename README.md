# Project Student-Development
# Introduction
 In March 2022, I decided to pursue a career in Data Science. I've operated a tutoring business for 8 years and taught math for 3 years. I am currently seeking a job in Data Science while re-branding my business. My goals follow: 
1. Determine student deficiency in order to target specific needs for growth and predict outcomes. 
2. Merge the student's evaluation with new Data Science skills to practice creating a project while marketing evidence of my growth to recruiters and potential clients.

Phase 1: Project Overview

Phase 2: Collect and Clean Data

Phase 3: Analyze Data

Phase 4: Data Model

Phase 5: Deploy Project
# Phase 1: Project Overview
During this phase, I’ll identify the project’s problem and discuss the action plan. For privacy, I’ll call the student Bill, although that is not the student’s legal name. 
Bill is an 8th-grade student who takes Algebra. I’ve tutored him for two years, and during that time, I discovered that he struggles to grasp and retain complex mathematical concepts. Moreover, he lacks foundational arithmetic skills. Bill is an eager learner who wants to develop but also struggles to stay engaged in a typical math classroom setting. After I hesitated to undergo a complete analysis of him, I decided that it was necessary for him to reach his full potential while maximizing time. I hypothesize that the results from this analysis will allow me, the student, his parents, and teachers to anticipate his upcoming struggles and gain a precise understanding of the skills he needs to improve in math. 

# Phase 2: Part One-Collect Data
Over eight weeks, Bill completed fifteen 6th-8th grade, math diagnostic assessments on Edulastic. During our weekly, virtual tutoring sessions, the following domains were examined.

NBT- Numbers & Operations in Base Ten

M & D- Measurement and Data 

NF- Number and Operations-Fractions

OA- Operations & Algebraic Thinking 

RP- Ratios and Proportions 

EE- Expressions and Equations 

G- Geometry 

SP- Statistics and Probability 

In order to identify the information I needed for Bill's individual analysis report, I had to consider the information I wanted to present. Therefore, I asked myself a questions; Some are listed below. This report will provide quantative and qualatative data.

A. Quantatative Data: Numerical 

1. At what grade level did I notice a gap in Bill's math retention and how large is this descrepency? 
2. What is his accuracy for each domain at each grade level?
3. What is his average accuracy for every domain through grade levels?
4. What is his average accuracy for each standard?
5. How much time does it take him to complete each exam? each question?
6. How many questions does he answer correctly/incorrectly for each exam?
7. How many different standards are being tested within each exam?
8. How many questions are on each test?
9. How many columns will there be?


B. Qualatative Data: Categorical 

1. What specific domains are being tested?
2. What specific standards are being tested?
3. What will be the headings for each column?

C. Other Questions: While the aboved questions primarily focus on inputing data, the following questions focus on data output. They highlight the uses of Bill's analysis. 

1. How can I present Bill's report visually, clearly and quickly? I want the student, teachers and parents to have an at-glance look at Bill's specific strengths, weaknesses and needs. 
2. How can this be usesul outside of the classroom, at home, or during everyday life?
3. How can this information help him stay engaged and interested in learning math?
4. In which standard(s) did I notice the greatest or least gap?
5. Can I make predictions about his performance in future math classes based off of these findings?
6. How can I quickly target Bill's specific needs after I have his report?
7. Is bill struggling or accelerating within the same standard throughout grade levels?
8. Can I hypothesis why the student has not been performing well within a specific grade level, domain or standard?
9. Do we see the same trends in other subjects?

https://docs.google.com/spreadsheets/d/1-1cyhR_83vV6k1KQBRlekau0TLh0IJWKE04QCZ5lhzI/edit#gid=0 

Here is a link to the data. Please note that the data is not clean yet. 

# Phase 2: Part Two-Clean Data
At this stage I was a bit stuck on the proccess for cleaning my data, so I used a few resources.

Attempt 1- https://www.youtube.com/watch?v=-Bnw-9ivbeo

Here is a link to a short video that explains what clean "good" data is in less than 15 minutes. Because I found this information very useful, I will be undergoing my first attempt to clean the data located in the spreadsheet posted above. This video stands out to me because it is short, clear and concise. I want to test if the information I learned in this video will suffice in my data cleaning stage. In other words, will I be able to upload "good" data into a database, Power BI, after my first cleaning attempt? 


During this attempt, I focused on the following.

Remove "totals." The database will calculate those.

Remove null cells by deleting rows/columns and filling in informatuon that needed to be repeated. 

Results are here https://docs.google.com/spreadsheets/d/1oElXtanXMpARm0_FkpQjBjKVrR6ZHwU2Hq74l2dCx-Q/edit?usp=sharing. This spreadsheet is being cleaned currently.
# Attempt 2: Create and Insert Data into Table using SQL.
Although I've inserted the data into a spreadsheet, I'm going to create a table and insert the data into SQL. Below is the code.

CREATE TABLE student

test_id INT PRIMARY KEY

grade level VARCHAR(3),

test type VARCHAR(30), 

standards VARCHAR(10),

accuracy INT, 

total points INT,

correct points INT,

incorrect points INT,

domaind VARCHAR(3),


