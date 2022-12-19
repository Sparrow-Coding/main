# U.S. Vaccination Analysis and Prediction

### Problem Statement and Background
Throughout 2020–2022, Covid-19 rampaged rampantly, putting many people’s lives and quality of life at risk.

According to a recent study published by CDC in August 2022, the estimated vaccine effectiveness of two doses of Pfizer-BioNTech vaccine in preventing MIS-C was 84%. Among children ages 5–11, vaccine effectiveness against MIS-C was estimated to be 78%, and among those ages 12–18, it was 90%.

Assuming the vaccine is helpful, we aim to use data to address the following questions in order to assist government officials in better allocating social resources and combating the COVID-19 situation:

Which state has the lowest/highest vaccination rate? How can we cater for the need of vaccination based on the state population and positive Covid-19 cases?
Which age group has the lowest/highest vaccination rate? If so, how can we better cater for the age group that has the lowest vaccination rate?
What is the vaccination trend looking like for the next 3 months?
Is there a high demand for booster doses throughout 2020–2022?
In which period did the demand for vaccination (administered dose / boosters) seem to decline?

### Source of the dataset

Data-driven decisions will be made through analysis of ‘COVID-19 Vaccination Age and Sex Trends in the United States, National and Jurisdictional’, which is a dataset collected by the Centers for Disease Control and Prevention between 12/13/2020 to 12/14/2022.

Reference: https://data.cdc.gov/Vaccinations/COVID-19-Vaccination-Age-and-Sex-Trends-in-the-Uni/5i5k-6cmh

Based on the data analysis, we will apply the Ridge regression model to (1) predict how many U.S. citizens have already completed the vaccination and (2) evaluate whether the current number of vaccinations is sufficient to put COVID-19 under control.

##  Data Description

This dataset contains demographic characteristics (age, sex, and age by sex) of people receiving COVID-19 vaccinations in the United States at the national and jurisdictional levels.

Data represents all vaccine partners including jurisdictional partner clinics, retail pharmacies, long-term care facilities, dialysis centers, Federal Emergency Management Agency and Health Resources and Services Administration partner sites, and federal entity facilities. 
