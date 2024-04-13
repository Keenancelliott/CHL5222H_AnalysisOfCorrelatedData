# CHL5222H_AnalysisOfCorrelatedData

## Data Source and Description
The data were provided as part of the course requirements for CHL5222H: Analysis of Correlated Data at the Dalla Lana School of Public Health, University of Toronto. The data were obtained from the University of California, Los Angeles (UCLA) Nurse Blood Pressure Study, which collected information from registered nurses in the Los Angeles area. The study aimed to determine physical and psychological characteristics that may be predictive of BP among nurses aged 24 to 50. Some factors included in the dataset are family history, personality, mood changes, activity level, and working status; a full list of the variables included in the dataset can be seen in the *Report* file included in this repository (Table 1). The dataset can be found in this repository (nursebp.csv).
The primary outcome we were interested in predicting was systolic BP measured in millimetres of mercury (mmHg). An initial BP reading was taken 30 minutes before the start of the nurse’s shift, and BP readings were taken every 20 minutes thereafter for the remainder of the workday. Subjects rated their mood and activity level at the time of each BP reading.


## Model Construction
A Linear Mixed effect model was fit to the dataset. A full report on the findings of our analysis can be seen in the *Report* file. The necessary code to recreate the model and figures included in the report can be seen in *CHL5222_Final_Project-Group-D.rmd*. To recreate this analysis, download the dataset and the .rmd file, change the filepath in the rmd file to the location of the nurse dataset on your computer, and run the code. The result will provide the model effect measures and the figures reported in our analysis. 

