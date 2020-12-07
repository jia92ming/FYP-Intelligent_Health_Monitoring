# FYP-Intelligent_Health_Monitoring

### The jupiter codes are included in this site.
### I had also created a webite for callback instead of using Local Host:
https://1jia99ming2.wixsite.com/finalyearproject


### READ ME:

- Each Stage of the Data analytics process is split into different notebooks.

- "FYP_SUBJECTS_CLASS.ipynb" is the Class definition for SUBJECTS (required for having split note books)

- Pickle files (for data) are in the PERSON 1 / PERSON 2 folder, uploaded in Google Drive: 
https://drive.google.com/drive/folders/1YHyTqTRSiZ-qcHZ31pZXXFXkUtbdjfIy?usp=sharing

- I am currently using PICKLE file as i see it is
   easier to index different person's DFs and Data under a single instance of the SUBJECT class.

- Currently fitness data are taken from FITBIT, however, the API fetch code for other companies
  can be add to the Class:SUBJECT (.Authorise, .Fetch) methods. 

- The company name of tracker is used to differentiate the API calls. 
  This can be done when defining an instance of Class:SUBJECT.
    - eg. PERSON_X = SUBJECT("Fitbit") 
       or PERSON_X = SUBJECT("Withings")

### Other iPython Notebook Files in this Project:

1. "FYP_FITBIT_0_Introduction & Data_Acquisition_Cleaning_Steps.ipynb"
  - Read this for steps and explaination for fetching data from API.

2. "FYP_FITBIT_1_Data_Acquisition_PERSON#.ipynb"
  - For Fetching fitness data from FITBIT for each individual.

3. "FYP_FITBIT_2_Feature_Extraction_PERSON#.ipynb"
  - For Calculating the HRV for each individual.

4. "FYP_FITBIT_3-#_Data_Exploration_Trend_Analysis_PERSON#"
  - For exploring the data trends gotten from the first 2 step for each individual.

5. "FYP_FITBIT_4-#_Correlation in xxx and yyy.ipynb"
  - Correlation analysis of fitness data and health indicators.

6. "FYP_FITBIT_5-#_Fuzzy_xxx.ipynb"
  - Implementation of Fuzzy Logic System.

7. "DATA FROM OTHER SOURCES.ipynb"
  - Exploration of data from the paper "Beyond Fitness Tracking", by Weng et al, dated 2018 Feb 27.
  
8. "FYP_FITBIT_6-#DATA FROM OTHER SOURCES.ipynb"
  - Implemetation of Fuzzy Logic using Data from the paper "Beyond Fitness Tracking", by Weng et al, dated 2018 Feb 27.  

### Python Version and Libraries Used:
1. python 3.0
2. pandas (Version 1.0.5)
3. seaborn
4. scipy
5. sklearn
6. matplotlib.pyplot
7. pickle
8. numpy
9. For fuzzy logic, use scikit-fuzzy (Version 2.0): 
pip install scikit-fuzzy
