# California Hospital Discharge Analysis

## Project Overview
This project explores hospital discharge records from multiple healthcare facilities across California. Using Python and data analysis techniques, it processes and analyzes discharge data to uncover patterns in diagnosis categories, hospital charges, length of stay, and payer types.

## Objectives
- Clean and preprocess hospital discharge data  
- Perform Exploratory Data Analysis (EDA) to identify key trends  
- Determine the most common diagnosis categories and types of care  
- Analyze how different payer types affect hospital charges  
- Compare discharges and charges across hospitals and counties  

## Methodology
1. **Data Collection**  
   Imported hospital discharge data containing information on hospital, location, care type, diagnosis, payer, discharges, and charges.  
2. **Data Cleaning**  
   Handled missing values, standardized columns, and prepared data for analysis.  
3. **Feature Engineering**  
   Extracted relevant time periods and categorized diagnosis and care types for deeper insights.  
4. **Exploratory Data Analysis (EDA)**  
   Identified top diagnosis categories, analyzed discharge patterns by county and payer, and examined length of stay by type of care.  
5. **Data Visualization**  
   Created bar charts, heatmaps, and trend lines using Matplotlib and Seaborn to highlight key findings.  

## Key Insights
- Certain diagnosis categories dominate discharge counts  
- Payer types influence total hospital charges significantly  
- Variation in length of stay observed across different care types and hospitals  
- Geographic disparities in discharge volumes and charges across counties  

## Files Included
- Dataset with columns such as `Discharge_Yr`, `OSHPD_ID`, `FACILITY_NAME`, `Hospital_County`, `Hospital_Zip`, `TypeCare`, `Adjusted_Length_of_Stay`, `MDC`, `Payer`, `Discharges`, and `Valid_Charges`.  
- Jupyter notebooks containing data cleaning, EDA, and visualization scripts.  
- This README file documenting the project.  

## Technologies Used
- Python (Pandas, NumPy) for data processing and cleaning  
- Matplotlib, Seaborn for visualizations  
- Jupyter Notebook for interactive analysis and reporting  

## Conclusion
This project offers valuable insights into hospital discharge patterns and financial metrics in California. The findings can assist healthcare administrators and policymakers in understanding resource utilization and improving patient care strategies.

## Future Enhancements
- Extend the analysis with predictive modeling on hospital stays and costs  
- Perform advanced statistical testing for more rigorous insights  
- Develop interactive dashboards for real-time data exploration  

---

For questions or collaboration opportunities, please contact: [aswini.devadari@gmail.com]  
