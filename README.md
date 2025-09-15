# Titanic Dataset Exploratory Data Analysis (EDA)

##  Objective
The goal of this project is to **explore the Titanic dataset using descriptive statistics and visualizations** in order to:

- Identify patterns  
- Detect anomalies  
- Uncover relationships among variables  
- Extract insights that inform predictive modeling with machine learning algorithms  

This repository contains both the **Jupyter Notebook** (`train_titanic.ipynb`) and a presentation summarizing the results.

---

## Key Analyses & Insights

### 1. Analysis of Fares Across Passenger Classes
- **First Class (Pclass 1):** Consistently the highest fares across embarkation ports.  
- **Second Class (Pclass 2):** Moderate fares.  
- **Third Class (Pclass 3):** Lowest fares with less variability.  

### 2. Fares by Embarkation Port
- **Cherbourg (Port C):** Highest fares for first-class passengers (150+).  
- **Southampton (Port S):** Lower fares compared to Cherbourg for the same class.  
- **Queenstown (Port Q):** Lowest overall fares across all classes.  

### 3. Variability in Fares
- **First Class:** Wide spread of fares → indicates flexible/variable pricing.  
- **Third Class:** Tightly clustered fares → standardized pricing.  
- **Outliers:** Observed particularly in first class fares.  

### 4. Economic Patterns
- **Cherbourg passengers:** Tended to be wealthier.  
- **Queenstown passengers:** Paid lower fares across classes.  
- **Overall pricing:** Clear class distinctions, regardless of port.  

### 5. Southampton Outlier Analysis
- **Possible reasons:** Family groups, last-minute bookings, dynamic pricing.  

### 6. Survival & Gender
- "Women and children first" protocol confirmed in survival rates.  

### 7. Survival & Family Size
- **Solo Travelers:** Young adults had higher survival chances; older or very young solo travelers fared worse.  
- **Small Families (2–4 people):** Children and women survived at higher rates.  
- **Large Families (5+ people):** Survival was difficult due to coordination challenges.  
- **Children:** Higher survival overall, but strongly influenced by family size.  

---

## Conclusion
- **Ticket Fares:** Reflected clear class distinctions, highest at Cherbourg and lowest at Queenstown.  
- **Fare Variability:** First-class fares varied widely, while third-class fares were standardized.  
- **Survival Patterns:** Followed the “women and children first” protocol.  
- **Family Dynamics:** Small families and children had higher survival chances; large families and older solo travelers had lower survival rates.  

---

##  How This Was Achieved
The notebook `train_titanic.ipynb` contains the step-by-step workflow:

1. **Data Loading & Cleaning**  
   - Handled missing values (e.g., age, embarkation port).  
   - Converted categorical variables for analysis.  

2. **Descriptive Statistics**  
   - Summary statistics (mean, median, standard deviation).  
   - Grouped analysis by passenger class and port.  

3. **Data Visualization**  
   - **Boxplots** to study fare variability across classes and ports.  
   - **Histograms/Distributions** for age, fares, and survival rates.  
   - **Survival Plots** segmented by gender and family size.  

4. **Insight Extraction**  
   - Identified economic patterns by port.  
   - Investigated outliers in Southampton.  
   - Analyzed family size effect on survival.  

---

# FeedBack:
This file clearly outlines the objective of using descriptive statistics and visualizations to find patterns and inform predictive modeling. The file's structure is well-organized with sections for key insights on passenger class, fares, gender, and family size, as well as a concluding summary and a breakdown of the technical workflow.
---