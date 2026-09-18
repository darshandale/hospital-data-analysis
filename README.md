# 🏥 Hospital Data Analysis Dashboard

> **Data Analytics | Excel / Python | Power BI | Data Cleaning | EDA | Data Visualization**

An end-to-end **Hospital Data Analysis Dashboard** project focused on transforming raw hospital patient data into meaningful insights through data cleaning, exploratory analysis, KPI development, and interactive visualizations.

The project analyzes patient demographics, payment methods, room types, feedback, and length of stay to understand hospital operations and patient satisfaction.

---

## 📊 Project Overview

Healthcare organizations generate large amounts of patient and operational data. However, raw data often contains duplicates, inconsistent values, and information that is difficult to interpret directly.

This project demonstrates a practical data analytics workflow:

```text
Raw Hospital Data
       ↓
Data Cleaning
       ↓
Data Validation
       ↓
Exploratory Data Analysis
       ↓
KPI Development
       ↓
Dashboard Development
       ↓
Business Insights
```

The final dashboard provides an interactive view of important patient and hospital-related metrics.

---

## 🎯 Project Objectives

The main objectives of this project are:

* Clean and prepare raw hospital patient data.
* Identify and remove duplicate records.
* Analyze patient demographics.
* Analyze payment methods used by patients.
* Analyze room-type distribution.
* Study patient feedback and satisfaction.
* Analyze patient length of stay.
* Develop meaningful KPIs.
* Create an interactive dashboard.
* Identify patterns that can support data-driven decision-making.

---

## 🗂️ Dataset

The original dataset contained:

| Metric                          | Value |
| ------------------------------- | ----: |
| Raw records                     |   971 |
| Raw columns                     |    14 |
| Records after duplicate removal |   951 |
| Duplicate records removed       |    20 |
| Final analytical records        |   951 |

The dataset contains patient and hospital-related attributes such as:

* Gender
* Payment Method
* Room Type
* Feedback
* Length of Stay
* Patient-related information

> **Note:** Dataset-specific values and field names should be updated if the source dataset is modified.

---

## 🧹 Data Cleaning

The raw dataset was inspected and cleaned before analysis.

### Main cleaning steps

1. Loaded the raw hospital dataset.
2. Checked the dataset structure and data types.
3. Identified duplicate records.
4. Removed duplicate records.
5. Checked missing and inconsistent values.
6. Standardized relevant categorical fields.
7. Validated the cleaned dataset.
8. Prepared the final dataset for analysis and visualization.

### Data transformation

```text
971 Raw Records
       ↓
Duplicate Detection
       ↓
20 Duplicate Records Removed
       ↓
951 Clean Records
       ↓
Analysis & Dashboard
```

---

## 📈 Key KPIs

The dashboard focuses on important hospital and patient metrics such as:

* 👥 Total Patients
* 😊 Patient Satisfaction
* 💳 Payment Method Distribution
* 🛏️ Room Type Distribution
* 📝 Patient Feedback
* ⏱️ Average Length of Stay
* 👨 Male vs Female Patients
* 📊 Patient Distribution by Relevant Categories

---

## 📊 Dashboard

The interactive dashboard provides visual analysis of the hospital dataset.

### Dashboard sections

#### 1. Patient Overview

Provides a high-level summary of:

* Total patients
* Gender distribution
* Patient categories
* Overall patient-related KPIs

#### 2. Payment Analysis

Analyzes:

* Payment method distribution
* Patient payment preferences
* Distribution across relevant patient segments

#### 3. Room Analysis

Analyzes:

* Room-type distribution
* Patient occupancy patterns
* Relevant room-level comparisons

#### 4. Patient Feedback & Satisfaction

Analyzes:

* Positive and negative feedback
* Patient satisfaction
* Feedback distribution
* Satisfaction patterns

#### 5. Length of Stay

Analyzes:

* Patient length of stay
* Average stay
* Distribution of patient stay durations
* Relationships between stay duration and other available variables

---

## 😊 Patient Satisfaction Analysis

One of the major analytical areas of the project is patient feedback and satisfaction.

The analysis identified an approximately **38.5% positive satisfaction rate** in the analyzed data.

This metric is used as an analytical KPI rather than as a claim about overall hospital performance.

---

## 🛠️ Tools & Technologies

### Data Analysis

* Python
* Pandas
* NumPy
* Jupyter Notebook

### Data Visualization

* Power BI
* Excel

### Data Processing

* Data Cleaning
* Duplicate Detection
* Data Transformation
* Exploratory Data Analysis
* KPI Development

### Version Control

* Git
* GitHub

---

## 🔍 Analytical Process

### Step 1 — Data Collection

Imported the raw hospital dataset containing patient and operational information.

### Step 2 — Data Understanding

Reviewed:

* Number of rows
* Number of columns
* Data types
* Categorical variables
* Numerical variables
* Missing values
* Duplicate records

### Step 3 — Data Cleaning

Removed duplicate records and prepared the dataset for analysis.

### Step 4 — Exploratory Data Analysis

Analyzed:

* Patient demographics
* Payment methods
* Room types
* Patient feedback
* Length of stay
* Satisfaction

### Step 5 — KPI Development

Created key metrics that summarize the hospital dataset.

### Step 6 — Dashboard Development

Built an interactive dashboard to allow users to explore the data through charts, filters, and KPIs.

### Step 7 — Insight Generation

Used the dashboard to identify patterns and trends within the available hospital data.

---

## 💡 Key Insights

The analysis provides visibility into:

* Patient demographic distribution.
* Distribution of different payment methods.
* Distribution of room types.
* Patient feedback patterns.
* Patient satisfaction levels.
* Length-of-stay patterns.
* Relationships between available patient and operational variables.

The dashboard is intended to demonstrate how raw healthcare-related data can be transformed into an understandable analytical view.

---

## 📸 Dashboard Preview

Add your dashboard screenshots here after uploading them to the `screenshots` folder.

### Dashboard Overview

![Hospital Dashboard](screenshots/dashboard_overview.png)

### Patient Analysis

![Patient Analysis](screenshots/patient_analysis.png)

### Satisfaction Analysis

![Satisfaction Analysis](screenshots/satisfaction_analysis.png)

---

## 📂 Project Structure

```text
hospital-data-analysis-dashboard/
│
├── data/
│   ├── raw/
│   │   └── hospital_raw_data.csv
│   └── cleaned/
│       └── hospital_cleaned_data.csv
│
├── dashboard/
│   └── Hospital_Dashboard.pbix
│
├── screenshots/
│   ├── dashboard_overview.png
│   ├── patient_analysis.png
│   └── satisfaction_analysis.png
│
├── analysis/
│   └── hospital_data_analysis.ipynb
│
├── documentation/
│   └── data_dictionary.md
│
├── README.md
└── LICENSE
```

---

## 🚀 How to Use

### Option 1 — Explore the Dashboard

Download the Power BI `.pbix` file from:

```text
dashboard/Hospital_Dashboard.pbix
```

Open it using **Microsoft Power BI Desktop**.

### Option 2 — Explore the Analysis

Open:

```text
analysis/hospital_data_analysis.ipynb
```

using Jupyter Notebook, JupyterLab, or VS Code.

### Option 3 — Explore the Dataset

The cleaned dataset is available at:

```text
data/cleaned/hospital_cleaned_data.csv
```

---

## 📌 Business Questions

This project addresses questions such as:

1. How many patients are included in the final dataset?
2. What is the gender distribution?
3. Which payment methods are most commonly used?
4. How are patients distributed across room types?
5. What percentage of analyzed feedback is positive?
6. What are the patterns in patient length of stay?
7. What patient-related categories show noticeable differences?
8. Which KPIs can help summarize the hospital dataset?
9. What patterns can be identified from patient feedback?
10. How can an interactive dashboard make hospital data easier to understand?

---

## 🎓 Skills Demonstrated

This project demonstrates practical skills in:

* Data Cleaning
* Data Validation
* Exploratory Data Analysis
* Data Visualization
* KPI Development
* Dashboard Design
* Business Question Formulation
* Data Interpretation
* Python / Pandas
* Power BI
* Excel
* Git & GitHub

---

## 👨‍💻 Author

**Darshan Dale**

Final-Year Information Technology Engineering Student

**Focus Areas:**
Data Analytics • Business Analytics • Power BI • SQL • Python • Excel

* 🔗 LinkedIn: [Darshan Dale](https://www.linkedin.com/in/darshan-dale/)
* 💻 GitHub: [darshandale](https://github.com/darshandale)

---

## 📜 License

This project is available for educational and portfolio purposes.

If the dataset belongs to a third-party source, its original licensing and attribution requirements should be followed separately.
