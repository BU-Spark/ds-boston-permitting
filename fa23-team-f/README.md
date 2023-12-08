This must summarize what the project is, what the team did, how to navigate the different files in the repo, and the information any future users would need to have in order to get the code running

What the project is
  We worked on the Boston Permitting Project. The goal of this project is to analyze trends in the approval and denial of the City of Boston building permits. When a project is denied in the City of Boston, it must go to the Zoning Board of Appeals to get a variance, or an exception, in order to get approval for the original permit. Because so many projects have to go through the Zoning Board of Appeals, this creates a great deal of unpredictability for the process. So, our motivation through this project is to understand the data around approvals and denials for permits and appeals in the City of Boston to ensure that residents and commercial entities are receiving equitable treatment. 

What the team did
The team worked with the following datasets: 
  Zoning Board Appeals Data
  Article 80 Development Projects Data
  Approved Building Permit Data
  Income and other demographic data pulled from the MA voter roll and census data
  GDP data pulled from the federal government

We did the following on this project
  1. Data cleaning - We removed incomplete data points by filtering out various “N/A”, “NaN”, etc values in the data. We filtered out obvious outliers from the datasets to prevent them from skewing means and other measurements of central tendency.
    
  2. Exploratory Data Analysis - We answered the following question to get a good understanding of the problem: 
      What type of building permits are approved each year by type (worktype), description, valuation (declared valuation), square footage, occupancy type?
      How have work type approvals changed over the past 5 years i.e. a year-over-year analysis?
      Who is applying for building permits by geography (neighborhood, zip code, zoning district)?
      What are the year over year trends visible in the zoning board of appeal approvals and denials by geography (neighborhood - listed as city, zip code, zoning  district)? You’ll want to normalize the data, perhaps ratio of permits to approvals or denials, etc. 
      What are the geographic profiles of the census tracts of the addresses for the permits submitted and zoning board approvals and denials (use project address and match to census data)?
     
  3. Extension Project - We wanted to analyze why certain areas have a lower or higher permit approval rate, based on demographics and economic data (i.e. commercial vs residential zoning), specifically looking at heavily gentrified areas. We answered the following questions: 
      What economic indicators have a strong correlation with high approval rates, or approval rates changing drastically over time?
      What features of the data about a given neighborhood, especially economic or demographic data, are best predictors of approval/denial rate?
     
Repo files
  workbooks folder: contains all the .ipynb files which have the data analysis
  team-info-page: names and contact information of the team members
  team-f-deliverable-zero.pdf: Deliverable 0 file
  CS506_Permitting_Team_F_Deliverable_1.pdf: Deliverable 1 file
  workbooks/Zachary_Census.ipynb: answers questions which type of building permits that are approved each year by type (worktype), description, valuation (declared valuation), square footage, occupancy type, Who is applying for building permits by geography (neighborhood, zip code, zoning district), How have work type approvals changed over the past 5 years i.e. a year-over-year analysis?
  workbooks/model.ipynb: modeling of the permit approval process and identification of features most important in predicting the outcome of a permit approval process.
  workbooks/timevdo_workbook.ipynb: year over year trends visible in the zoning board of appeal approvals and denials by geography (neighborhood - listed as city, zip code, zoning district) and GDP trends, geographic profiles of the census tracts of the addresses for the permits submitted and zoning board approvals and denials (use project address and match to census data)
  workbooks/voterdata.ipynb: Preliminary analysis on trends between voter file data and several data.boston.gov datasets

How to get the code running
  In order to run all the files in the workbooks folder, you must have the following datasets in a data folder
  [Approved Building Permits](https://data.boston.gov/dataset/approved-building-permits/resource/6ddcd912-32a0-43df-9908-63574f8c7e77)
  [Article80 Development Projects - Datasets - Analyze Boston](https://data.boston.gov/dataset/article80-development-projects)
  [Zoning Board of Appeal Tracker - Datasets - Analyze Boston](https://data.boston.gov/dataset/zoning-board-of-appeal-tracker)
  [Data Dictionary](https://data.boston.gov/dataset/zoning-board-of-appeal-tracker/resource/e11dcfa5-6f6f-4999-abc3-741f53c6731f)
  [Census data for demographics](https://www.census.gov/programs-surveys/acs/data.html)

Then run the .ipnyb files in the workbooks in the github.
