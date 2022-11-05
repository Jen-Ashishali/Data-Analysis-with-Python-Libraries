# Project Overview

This dataset was downloaded manually from Udacity's servers, with its original source from [Kaggle](https://www.kaggle.com/datasets/joniarroba/noshowappointments). Here, questions are brainstormed by understanding the variables in the data to see what insight it provides using Pandas and Matplotlib. The scope of this analysis doesn't cover inferential statistics or machine learning, hence findings are tentative. 

# Dataset
The dataset collects information from 100k medical appointments in Brazil and is focused on whether or not patients show up for their appointment. The following variables are present in the dataset;
 - ScheduledDay - what day the patient set up their appointment. 
 - AppointmentDay - the fixed date of the appointment
 - Neighborhood - the location of the hospital.
 - Scholarship - whether or not the patient is enrolled in Brasilian welfare program Bolsa Família. 
 - No-show has two distinct observations, 'No' and 'Yes'. No indicates completed appointment, and 'Yes' indicates a missed appointment
 - SMS received - number of messages sent to the patient
 - Other variables are self explanatory. Each observation represented as 0 and 1, indicates False and True values respectively
 
 # Data Wrangling and Analysis
 The steps taken to clean the data can be found in the Jupyter notebook attached to this repository. The notebook also reports the analysis, and steps taken to answer the questions stated below;
 
**Questions**
 - What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment?
 - Is a certain type of health condition associated with gender?
 - What kind of health condition is common with each age group?
 - What kinds of properties are associated with patients with scholarships?
 
 # Summary of Findings
- There was an increase in successful appointments, during shorter wait periods. Older Adults have more succesful appointments, than the other age classes while Young Adults have the most failed appointment, and Female have more successful appointments than male. Based on these observations, factors to consider with an aim of successful appointment include, the age of the patient, gender of the patient, and appointment wait periods.
- More females are diagnosed with hypertension and diabetes, while alcholism is common within the Male Patients
- Hypertension is relatively high in Older Adults
- Disability (handicap) is common with Children

### Limitations
- Unavailable timestamp on appointment day, limits analysis for appointment pattern by hour of the day 
- Patient Location data limits analysis of distance to Hospital Neighbourhood
