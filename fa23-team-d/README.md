# Boston Permitting Analysis - Team D

## Introduction
This report presents an in-depth analysis of the Boston permitting process. It assesses the economic impact, compliance with regulations, and socio-political factors influencing urban development.

## Datasets and Cleaning
Data from the City of Boston and the State of Massachusetts were cleaned to provide a foundation for accurate analysis. This included reconciling discrepancies and standardizing formats across building permits, zoning appeals, and demographic data.

## Methodology
Our methodology integrated in-depth analysis, statistical modeling, and machine learning, employing a decision tree algorithm to derive insights from permit data, and spatial analysis to evaluate development patterns.

## Key Analyses
- **Trend Analysis**: Trends in permit approvals and valuations over time, which also revealed a dip in 2020 linked to the COVID-19 pandemic.
- **Geographic Distribution**: Analysis of permits by urban areas, indicating a concentration of activity in certain neighborhoods.
- **Economic and Demographic Disparities**: Utilizing Lorenz curves and Gini coefficients to highlight disparities in development distribution, with lower-income areas experiencing more permit rejections.

## Decision Tree Model Insights
Detailed insights from the decision tree model, explaining the influence of specific features on the likelihood of permit approval.

## COVID-19 Pandemic Analysis
Correlation analysis between pandemic data and permitting trends, showing how public health crises can significantly disrupt urban development.

## Conclusion
A synthesis of our findings, emphasizing the need for policy considerations to address the observed disparities and enhance urban planning.

## Team Members
David Kim, Lukas Werk, Richard Hao, Efim Sokolov, Jackson Fisk

## Files
- Inside Final Organized Files:
  - Deliverable
    - Deliverable 0.pdf
    - Deliverable 1 Presentation.pdf
    - Deliverable 1.pdf
    - Deliverable 2.pdf
    - Deliverable 3.pdf
    - Deliverable 4.pdf
    - Deliverable 5.pdf
  - Data (Only in Google Drive)
    - Raw_zba.csv
      - Raw Zoning Board of Appeal Data
    - Raw_covid.csv
      - Raw COVID19 Data
    - Raw_a80.csv
      - Raw Article 80 Permits Data
    - Raw_abp.csv
      - Raw Approved Building Permits Data
    - Cleaned_zba.csv
      - Cleaned Zoning Board of Appeal Data
    - Cleaned_covid.csv
      - Cleaned COVID19 Data
    - Cleaned_a80.csv
      - Cleaned Article 80 Permits Data
    - Cleaned_abp.csv
      - Cleaned Approved Building Permits Data
    - Census2020_BG_Neighborhoods.shp
      - Census Data 1
    - 2020_Census_Block_Groups_in_Boston.shp
      - Census Data 2
    - Covid_vs_zba.csv
      - Merged & combined covid dataset with zba
    - Covid_vs_abp.csv
      - Merged & combined covid dataset with abp
  - Cleaning
    - Cleaned_zba.ipynb
      - Python Code for Cleaning Zoning Board of Appeal Data
    - Cleaned_covid.ipynb
      - Python Code for Cleaning COVID19 Data
    - Cleaned_abp.ipynb
      - Python Code for Cleaning Approved Building Permits Data
    - Cleaned_a80.ipynb
      - Python Code for Cleaning Article 80 Permits Data
  - Analysis
    - Visualized_zba.ipynb
      - Python Code for Visualizing Zoning Board of Appeal Data
    - Visualized_abp.ipynb
      - Python Code for Visualizing Approved Building Permits Data
    - Visualized_a80.ipynb
      - Python Code for Cleaning Article 80 Permits Data
    - Extension_1.ipynb
      - Python Code for Extension Project 1
    - Extension_2.ipynb
      - Python Code for Extension Project 2

## Repository Link
For comprehensive access to our analysis scripts, data, and detailed findings, visit our GitHub repository:
[GitHub Repository](https://github.com/BU-Spark/ds-boston-permitting/fa23-team-d)

Youtube video for deliverable 2: [https://youtu.be/LeJDI1vmzSk](https://youtu.be/Q5J00lDXuQ4)

Youtube video for deliverable 3: [https://youtu.be/LeJDI1vmzSk](https://youtu.be/CMo4j0SoYOE)
