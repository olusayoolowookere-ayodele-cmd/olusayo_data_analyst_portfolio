# Automated Student Report Card Generator
## Data Analytics Project Portfolio

**Organization:** Greenfield Academy  
**Project Type:** Spreadsheet Automation and Data Analytics  
**Tools:** Microsoft Excel / Spreadsheet Functions  
**Key Techniques:** Data Lookup, Formula Automation, Aggregation, Conditional Logic, and Attendance Analysis  

---

## Project Overview

Greenfield Academy required a more efficient and standardized approach to preparing student report cards. Manual compilation of academic records can be time-consuming and may result in calculation errors, inconsistent grading procedures, and delays in generating student performance reports.

This project developed an **Automated Student Report Card Generator**, a formula-driven spreadsheet system designed to retrieve student information dynamically and generate key academic and administrative performance indicators.

The system uses a **Student ID** as the primary input to automatically retrieve student details, aggregate subject scores, calculate attendance rates, and determine the student's overall academic status.

---

## Business Problem

The manual preparation of student report cards presents several administrative challenges, including:

- Time-consuming compilation of student records.
- Errors in score calculations and attendance computation.
- Inconsistent application of grading criteria.
- Delays in producing student performance reports.
- Difficulty maintaining standardized reporting across students.

The project addressed these challenges by creating a dynamic spreadsheet model capable of automatically generating student performance information from a single student identifier.

---

## Project Objectives

The objectives of the project were to:

1. Automate the retrieval of student information using a unique Student ID.
2. Calculate overall academic performance from subject scores.
3. Determine student pass or fail status using conditional logic.
4. Calculate attendance percentages automatically.
5. Reduce manual calculations and improve the consistency of report generation.

---

## Dataset

The project dataset was derived from:

`capstone_project 1(student report card) (1).csv`

The report card system contains information relating to student demographics, academic performance, attendance, financial records, and class administration.

### Key Variables

| Variable | Description |
|---|---|
| Student ID | Unique identifier for each student |
| Full Name | Student's name |
| Grade Level | Student's academic class |
| Math Score | Performance in Mathematics |
| English Score | Performance in English Language |
| Science Score | Performance in Science |
| Social Studies Score | Performance in Social Studies |
| Average Score | Overall academic average |
| Pass/Fail Status | Academic performance outcome |
| Days Present | Number of days attended |
| Total School Days | Total academic days in the term |
| Attendance Percentage | Percentage of school attendance |
| Official Tuition Fee | Recorded tuition fee |
| Class Teacher | Teacher responsible for the class |

---

## Analytical Approach

The automated report card system applies spreadsheet-based analytical techniques to transform raw student information into meaningful performance indicators.

### 1. Dynamic Data Retrieval

Student information is retrieved automatically based on the selected **Student ID**.

Lookup functions such as:

- `XLOOKUP`
- `VLOOKUP`
- `INDEX/MATCH`

can be used to retrieve student information, including:

- Full Name
- Grade Level
- Class Teacher
- Tuition Fee

---

### 2. Academic Performance Analysis

The system aggregates scores from four academic subjects:

- Mathematics
- English
- Science
- Social Studies

The overall academic average is calculated using:

\[
\text{Average Score} =
\frac{\text{Math + English + Science + Social Studies}}{4}
\]

---

### 3. Attendance Analysis

Attendance performance is calculated by comparing the number of days attended with the total number of school days.

\[
\text{Attendance Percentage} =
\left(
\frac{\text{Days Present}}{\text{Total School Days}}
\right)
\times 100
\]

---

### 4. Automated Performance Classification

Conditional logic is applied to classify the student's academic outcome as either:

- **PASS**
- **FAIL**

This ensures that academic evaluation is standardized and automatically generated.

---

# Student Performance Results

The automated system generated the following results for the selected student.

## Student Profile

| Indicator | Result |
|---|---|
| **Student ID** | GA-2026088 |
| **Student Name** | Halima Ibrahim |
| **Grade Level** | JSS2 |
| **Class Teacher** | Mr. Tunde Bello |

---

## Academic Performance

| Subject | Score |
|---|---:|
| Mathematics | 88 |
| English | 55 |
| Science | 60 |
| Social Studies | 52 |
| **Average Score** | **63.8** |

### Academic Outcome

**Pass/Fail Status: PASS**

The student achieved a total score of **255** across the four subjects, resulting in an average score of approximately **63.8**.

---

## Attendance Performance

| Attendance Indicator | Result |
|---|---:|
| Days Present | 117 |
| Total School Days | 120 |
| Days Absent | 3 |
| **Attendance Rate** | **97.5%** |

The student demonstrated excellent attendance, attending **117 out of 120 school days**.

---

## Financial Information

| Indicator | Result |
|---|---:|
| Official Tuition Fee | $27,000 |

---

# Key Insights

## 1. Strong Attendance Performance

The student recorded an attendance rate of **97.5%**, indicating consistent participation in school activities and strong attendance discipline.

The student was absent for only **3 days** during the academic period.

---

## 2. Significant Variation in Subject Performance

Academic performance differs considerably across subjects.

- **Mathematics:** 88
- **Science:** 60
- **English:** 55
- **Social Studies:** 52

Mathematics represents the student's strongest area, while Social Studies represents the lowest-performing subject.

This variation suggests that academic performance should be evaluated at both the overall and subject-specific levels.

---

## 3. Attendance Does Not Automatically Guarantee High Academic Performance

Despite the student's excellent attendance rate of **97.5%**, the overall academic average was **63.8**.

This demonstrates that consistent school attendance alone may not guarantee high performance across all subjects. Additional academic support may be required to improve weaker subject areas.

---

# Recommendations

Based on the analysis, the following recommendations are proposed:

### 1. Provide Targeted Academic Support

Additional academic support should be considered for weaker subjects, particularly:

- Social Studies
- English Language

Targeted tutoring and academic interventions may help improve performance in these areas.

---

### 2. Improve Student ID Validation

The Student ID input should include data validation, such as a dropdown list of valid Student IDs.

This can reduce errors and prevent invalid lookup results.

---

### 3. Expand the System for Multiple Students

The current model can be expanded into a centralized student database capable of:

- Generating report cards for multiple students.
- Producing class-level performance summaries.
- Comparing student performance.
- Identifying high-performing and struggling students.
- Supporting school-wide academic analysis.

---

### 4. Develop a Management Dashboard

A dashboard can be integrated into the system to provide visual summaries of:

- Average academic performance.
- Subject performance.
- Attendance rates.
- Pass and fail statistics.
- Student performance trends.

This would improve the ability of school administrators to make data-driven decisions.

---

# Project Impact

The Automated Student Report Card Generator demonstrates how spreadsheet analytics and automation can improve educational administration.

The system provides several benefits:

- **Efficiency:** Reduces the time required to prepare report cards.
- **Accuracy:** Minimizes manual calculation errors.
- **Consistency:** Applies standardized academic evaluation rules.
- **Automation:** Updates student information dynamically.
- **Decision Support:** Provides clear academic and attendance indicators.
- **Scalability:** Can be expanded to support larger student databases.

---

# Skills Demonstrated

This project demonstrates practical skills in:

- Spreadsheet Data Analysis
- Data Cleaning and Organization
- Data Lookup Functions
- Formula Development
- Conditional Logic
- Academic Performance Analysis
- Attendance Analysis
- Data Aggregation
- Automated Reporting
- Business Problem Solving
- Data-Driven Decision Making

---

# Conclusion

The Automated Student Report Card Generator provides a practical solution for improving the efficiency and accuracy of student performance reporting at Greenfield Academy.

By using formula-driven automation, the system can retrieve student information, calculate academic averages, analyze attendance, and determine academic outcomes from a single Student ID input.

The project demonstrates the value of data analytics and spreadsheet automation in educational administration. With further development, the system could be expanded into a centralized reporting and analytics platform capable of supporting multiple students, classes, and school-wide performance monitoring.
```


