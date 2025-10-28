# Fitness Data Analysis Project

## Project Overview

This project demonstrates data cleaning, exploration, and analysis skills using a fitness and health metrics dataset. I analyzed 5,000 records to identify patterns in BMI categories, body fat percentages, exercise recommendations, and demographic differences.

**Key Skills Demonstrated:**
- Data cleaning and validation in Excel
- Summary statistics and pivot tables
- Data visualization (pie charts, column charts, scatter plots)
- Business insight generation
- Documentation and reporting

---

## Dataset Information

**Source:** Fitness exercises using BFP & BMI dataset

**Records:** 5,000 individuals

**Key Columns:**
- Weight (kg)
- Height (meters)
- BMI (Body Mass Index)
- Body Fat Percentage
- Gender (Male/Female)
- Age (18-65 years)
- BMI Category (Normal, Overweight, Obese, etc.)
- Body Fat Category (Athletes, Fitness, Acceptable, Obese)
- Exercise Recommendation Plan (Levels 1-7)

**Data Quality:**
- ✓ No missing values
- ✓ All numeric fields validated
- ✓ No duplicates detected
- ✓ All values within expected ranges

---

## Analysis Performed

### 1. BMI Category Distribution
Analyzed how the population breaks down by BMI classification:
- Normal: 29.2%
- Overweight: 24.6%
- Severe Obese: 17.2%
- Obese: 16.9%
- Other categories: 12.1%

**Key Finding:** Over 60% of the dataset falls into overweight or obese categories.

### 2. Body Fat Percentage Analysis
Categorized individuals by body fat levels:
- Obese: 60.7%
- Acceptable: 23.9%
- Fitness: 9.4%
- Athletes: 6.1%

### 3. Gender Comparison
Compared fitness metrics between males and females:
- **Average Age:** Males 41.8 years, Females 41.7 years
- **Average BMI:** Males 26.0, Females 26.0
- **Average Body Fat %:** Males 29.2%, Females 30.8%
- **Exercise Recommendation:** Both averages ~4.87 (slightly higher intensity)

### 4. Exercise Recommendations by Category
Mapped exercise intensity levels to BMI and body fat categories:
- Normal BMI individuals: Average level 4
- Overweight individuals: Average level 5
- Obese individuals: Average level 6-7

---

## Visualizations

The project includes 4 key charts:

**Chart 1: BMI Category Distribution (Pie Chart)**
- Shows breakdown of population by BMI classification
- Highlights that majority are overweight or obese

**Chart 2: Body Fat Percentage Categories (Column Chart)**
- Compares count of individuals in each body fat category
- Visual representation of fitness population distribution

**Chart 3: Age vs. BMI Relationship (Scatter Plot)**
- Examines potential correlation between age and BMI
- Shows slight trend of increasing BMI with age

**Chart 4: Average Exercise Recommendation by Gender (Column Chart)**
- Compares recommended exercise intensity for males vs. females
- Shows minimal gender difference in recommendations

---

## Key Insights

1. **Health Concern:** Over 60% of the dataset is overweight or obese, indicating significant health concerns in this population and need for fitness interventions.

2. **Exercise Needs:** Most individuals receive exercise recommendation levels 4-5, suggesting moderate to high-intensity fitness programs are needed for this group.

3. **Gender Parity:** Males and females have similar average metrics and exercise recommendations, indicating fitness needs are comparable across genders.

4. **Age Factor:** There's a slight positive correlation between age and BMI, suggesting weight management becomes more challenging with age.

5. **Body Composition:** Nearly 61% of the population falls into the "Obese" body fat category, highlighting the importance of targeted fitness and nutrition programs.

---

## Files in This Repository

- `Fitness_Data_Analysis.xlsx` - Main Excel workbook with all analysis, pivot tables, and charts
- `README.md` - This file

---

## Tools Used

- **Microsoft Excel** - Data analysis, pivot tables, formulas (COUNTIF, AVERAGEIF), visualization
- **Excel Formulas:** 
  - `=COUNTIF()` for categorical counts
  - `=AVERAGEIF()` for gender-based comparisons
  - `=IF()` for age group categorization

---

## Process & Methodology

### Phase 1: Data Exploration
- Loaded 5,000 records into Excel
- Validated data types and ranges
- Checked for missing values and duplicates
- Documented data quality findings

### Phase 2: Data Summarization
- Created pivot tables for categorical analysis
- Calculated summary statistics by gender
- Used Excel formulas to aggregate data
- Organized findings in clear summary tables

### Phase 3: Visualization
- Designed 4 complementary charts
- Ensured charts tell clear story
- Added appropriate titles and axis labels
- Positioned visuals for easy interpretation

### Phase 4: Insight Generation
- Analyzed patterns and trends
- Drew business-relevant conclusions
- Documented findings for stakeholders
- Created actionable recommendations

---

## How to Use This Project

1. **Review the Excel file** - Open `Fitness_Data_Analysis.xlsx` to see all analysis, formulas, and charts
2. **Check the sheets:**
   - "Project Overview" - Quick summary
   - "Raw Data" - Original 5,000 records
   - "Data Quality Report" - Validation findings
   - "Analysis Summary" - All pivot tables and formulas
   - "BMI DISTRIBUTION", "BFP DISTRIBUTION","EXERCISE DISTRIBUTION","AGE VS BMI SCATTERPLOT"
   - "Key Insights" - Summary of findings



---

## What I Learned

- How to validate and clean data systematically
- Excel formulas for data aggregation and analysis
- Effective data visualization techniques
- Communicating insights to non-technical stakeholders
- Importance of documenting data quality assumptions
- Creating reproducible analysis workflows

---

## Future Enhancements

- Expand analysis to include age group segmentation
- Create predictive models for exercise recommendations
- Add weight loss projection analysis
- Incorporate dietary data for comprehensive health analysis
- Compare results across different demographic populations

---

## Contact & Portfolio

This project is part of my data analyst portfolio demonstrating:
- Data cleaning and validation
- Excel proficiency
- Analytical thinking
- Business insight generation
- Clear communication of findings

For questions or feedback, feel free to reach out!

---

**Project Completion Date:** [Your Date]  
**Status:** ✓ Complete
