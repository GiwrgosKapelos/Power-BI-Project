# Power-BI-Project

This repository contains a Power BI project that analyzes data from an Excel source file.  
The report provides insights on what the survey participants have answered in a survey.

## Repository Structure
- `data/` → Source Excel file(s)
- `reports/` → Power BI `.pbix` file and exported visualizations
- `docs/` → Documentation and screenshots
- `README.md` → Project overview
- `requirements.md` → Dependencies (if applicable)

## How to Use
1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/powerbi-final-project.git
2. Open reports/Final Project.pbix in Power BI Desktop.

3. Ensure the Excel source file is in data/Power BI - Final Project.xlsx.

4. Refresh the data to view the latest insights.

## Dashboard Highlights

The report includes six main dashboards:

1. Geographic spread of participants

2. Most popular programming languages by the participants

3. Salary hierarchy across different job titles

4. Difficulty breaking into data roles

5. Work/life balance across different jobs

6. Salary satisfaction

## Data Cleaning

   - Grouped uncommon responses into "Other" (job roles, programming languages, age, and countries)

   - Cleaned salary column by removing symbols and converting to numeric values

   - Created a new Average Salary column


## Requirements
Power BI Desktop (latest version recommended).

Excel (for viewing/editing the dataset).

## This project was built to practice Power BI data visualization and analysis using real-world survey data.
