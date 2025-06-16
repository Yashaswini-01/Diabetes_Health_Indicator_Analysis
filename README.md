# 🏥 Diabetes Health Indicators Analytics Dashboard

## 📖 Project Overview

This project presents a comprehensive analysis of diabetes health indicators using the 2023 Behavioral Risk Factor Surveillance System (BRFSS) dataset from the CDC. The analysis transforms raw survey data into actionable insights through systematic data preparation, advanced Excel analytics, and interactive dashboard visualization.

**Key Project Components:**
- Systematic data preparation and mapping of coded variables
- Advanced Excel analytics with pivot tables and formulas
- Interactive multi-page dashboard visualization
- Identification of key risk factors and demographic patterns
- Analysis of behavioral trends associated with diabetes prevalence

## 📊 Dashboard & Visualization

The project features a comprehensive three-page interactive dashboard that transforms complex health survey data into actionable insights through advanced Excel visualization techniques. The dashboard provides executive-level KPIs, behavioral trend analysis, and demographic risk assessments with intuitive charts and real-time data filtering capabilities.

**🔗 [View Live Dashboard](<iframe width="402" height="346" frameborder="0" scrolling="no" src="https://northeastern-my.sharepoint.com/personal/tadishetty_y_northeastern_edu/_layouts/15/Doc.aspx?sourcedoc={e772ac07-bdf1-42e7-8f50-5e856872e814}&action=embedview&wdAllowInteractivity=False&wdHideGridlines=True&wdHideHeaders=True&wdDownloadButton=True&wdInConfigurator=True&wdInConfigurator=True"></iframe>)**

## 📋 Dataset Information

**Dataset Overview:**
- **Original Dataset:** 2023 CDC Behavioral Risk Factor Surveillance System (BRFSS)
- **Total Respondents:** 433,323 U.S. adults
- **Original Features:** 330+ variables
- **Selected Features:** 20 diabetes-related indicators
- **Data Collection Method:** Telephone interviews across all U.S. states

**Feature Categories:**
- **Health Conditions:** Diabetes status, hypertension, cholesterol, heart disease, stroke
- **Physical & Mental Health:** BMI, physical health days, mental health days, mobility issues
- **Behavioral Factors:** Physical activity, smoking history
- **Healthcare Access:** Insurance coverage, medical cost barriers
- **Demographics:** Age, gender, education, income level

## 🛠️ Tools & Technologies

**Development Environment:**
- **Python:** Data mapping and standardization using Pandas
- **Google Colab:** Cloud-based Python development environment

**Analysis Platform:**
- **Microsoft Excel:** Data cleaning, analysis, and visualization
- **Excel Advanced Features:** Pivot tables, advanced formulas, conditional formatting
- **Data Visualization:** Excel charts, interactive dashboards with multiple pages

## 🎯 Business Problems Solved

The project addresses critical healthcare challenges through data-driven insights:

- **Risk Factor Identification:** Identifying key demographic and behavioral factors that correlate with higher diabetes prevalence rates
- **Healthcare Access Analysis:** Examining how insurance coverage and income levels impact diabetes outcomes and healthcare accessibility
- **Population Health Insights:** Providing insights into which population segments require targeted health interventions and preventive care programs
- **Behavioral Pattern Recognition:** Revealing relationships between lifestyle factors like physical activity, smoking, and diabetes risk
- **Resource Allocation Guidance:** Helping healthcare organizations prioritize resources for high-risk demographic groups and geographic areas

## 🔄 Step-wise Implementation

### 1. Data Codebook Mapping and Standardization (Python)
**Process Overview:**
- Transformed cryptic survey codes into human-readable labels using Python and Pandas
- Mapped over 20 variables from numeric codes to descriptive text
- Created standardized age groups, income brackets, and BMI categories
- Handled missing values and "Don't know/Refused" responses according to CDC codebook specifications
- Applied categorical mapping functions for consistent data interpretation

### 2. Data Cleaning (Excel)
**Cleaning Activities:**
- Removed incomplete responses and invalid data entries
- Standardized categorical variables across all features
- Created calculated fields for enhanced analysis capabilities
- Applied data validation rules to maintain data integrity
- Ensured consistency in data formatting and structure

### 3. Data Analysis (Excel Formulas and Pivot Tables)
**Analytical Framework:**
- Implemented advanced Excel formulas to calculate key performance indicators
- Created pivot tables for cross-tabulations and demographic breakdowns
- Calculated diabetes prevalence rates by various demographic segments
- Analyzed correlations between behavioral factors and health outcomes
- Generated statistical measures and trend analyses

### 4. Data Visualization (Excel Dashboard)
**Dashboard Development:**
- Created comprehensive three-page dashboard using Excel's advanced charting capabilities
- Incorporated multiple chart types with interactive elements
- Implemented color-coded KPIs for immediate insight recognition
- Designed user-friendly navigation between dashboard pages
- Ensured accessibility and clarity in data presentation

## 📈 Data Visualizations

### Page 1: Executive Overview
**Key Performance Indicators:**
- **Total Respondents:** 433,318 survey participants
- **Diabetes Cases:** 63,039 confirmed cases
- **Pre-Diabetes Rate:** 2.45% of total population
- **Average BMI:** 28.48 (overweight category)
- **Gender Risk Factor:** Females show higher diabetes prevalence
- **Uninsured Rate:** 5.48% lack health coverage

**Primary Visualizations:**
- **Diabetes Breakdown by Gender:** Horizontal bar chart comparing male vs female diabetes cases
- **Age Group Distribution:** Horizontal bar chart showing diabetes prevalence across age ranges
- **BMI Category Distribution:** Donut chart displaying weight category percentages
- **General Health Rating by Age:** Stacked bar chart showing health status across age groups
- **Insurance Type Analysis:** Column chart illustrating coverage types and prevalence

### Page 2: Behavioral Trends
**Key Performance Indicators:**
- **Physically Inactive Population:** 24.73% lack regular exercise
- **Smoking Population:** 158,774 individuals with smoking history
- **Mobility Issues:** 16.13% report difficulty walking
- **Average Poor Health Days:** 11.02 days per month
- **High-Risk BMI Category:** Obese individuals most affected
- **Hypertension Rate:** 40.85% have elevated blood pressure

**Primary Visualizations:**
- **Difficulty Walking by Age:** Line chart showing mobility issue progression
- **Physical Activity Patterns:** Horizontal bar chart displaying activity levels by gender and age
- **Cholesterol Screening Compliance:** Pie chart showing screening participation rates
- **BMI vs Physical Health Days:** Scatter plot correlating weight status with health outcomes
- **Smoking Behavior by Gender:** Grouped column chart comparing smoking rates

### Page 3: Demographic Risks
**Key Performance Indicators:**
- **Diabetic Comorbidity Rate:** 24.69% have multiple chronic conditions
- **Highest Risk Age Group:** 70+ years show peak diabetes rates
- **Education Factor:** College graduates have highest pre-diabetes rates
- **Income-Insurance Gap:** 38.51% uninsured in $25K-$50K income bracket
- **Primary Uninsured Group:** Middle-income families most affected

**Primary Visualizations:**
- **Chronic Disease by Age:** Horizontal bar chart showing disease prevalence across age groups
- **Uninsured Rates by Income:** Area chart displaying coverage gaps across income levels
- **Pre-diabetes by Education:** Column chart showing rates across educational attainment
- **Comorbidity Rate Progression:** Line chart tracking multiple condition prevalence by age
- **Education-Diabetes Breakdown:** Stacked column chart showing diabetes distribution by education level

## 🔍 Key Insights

- **Age-Related Risk:** Diabetes prevalence increases dramatically with age, reaching 54.95% in individuals over 70 years
- **Gender Disparity:** Women demonstrate slightly higher diabetes prevalence compared to men across all age groups
- **Insurance Coverage Gap:** Middle-income families ($25K-$50K) face the highest uninsured rates at 38.51%, creating healthcare access barriers
- **Physical Inactivity Impact:** 24.73% of the population lacks regular exercise, showing strong correlation with diabetes risk
- **Comorbidity Burden:** Nearly 25% of diabetic individuals have multiple chronic conditions, requiring comprehensive care management
- **Education Paradox:** College graduates show higher pre-diabetes rates, indicating that education alone doesn't guarantee optimal health outcomes

## 🎯 Conclusion

- **Data-Driven Insights:** Successfully transformed complex BRFSS survey data into actionable healthcare intelligence for decision-making
- **Risk Factor Identification:** Identified critical demographic and behavioral patterns that correlate with higher diabetes prevalence rates
- **Healthcare Access Gaps:** Revealed significant insurance coverage disparities affecting middle-income populations ($25K-$50K bracket)
- **Evidence-Based Framework:** Created a reusable analytical model for ongoing diabetes surveillance and public health monitoring
- **Policy Guidance:** Provided comprehensive evidence to support targeted intervention strategies and resource allocation decisions
- **Population Health Impact:** Enabled healthcare organizations to prioritize high-risk demographic groups for preventive care programs

## 🚀 Future Enhancements

- **Machine Learning Integration:** Incorporate predictive algorithms to calculate personalized diabetes risk scores for proactive healthcare interventions
- **Geographic Expansion:** Add state-level and regional analysis to identify diabetes hotspots and enable location-specific health programs
- **Interactive Web Platform:** Migrate dashboard to Tableau or Power BI for broader accessibility and real-time data updates
- **Economic Impact Assessment:** Include healthcare cost analysis to quantify diabetes expenditure and inform budget allocation decisions
- **Real-Time Monitoring:** Develop automated data pipeline for continuous health surveillance and early warning systems
