# U.S. Vaccination Analysis and Prediction

### Problem Statement and Background
Throughout 2020–2022, Covid-19 rampaged rampantly, putting many people’s lives and quality of life at risk.

According to a recent study published by CDC in August 2022, the estimated vaccine effectiveness of two doses of Pfizer-BioNTech vaccine in preventing MIS-C was 84%. Among children ages 5–11, vaccine effectiveness against MIS-C was estimated to be 78%, and among those ages 12–18, it was 90%.

Assuming the vaccine is helpful, we aim to use data to address the following questions in order to assist government officials in better allocating social resources and combating the COVID-19 situation:

1. Which state has the lowest/highest vaccination rate? How can we cater for the need of vaccination based on the state population and positive Covid-19 cases?

2. Which age group has the lowest/highest vaccination rate? If so, how can we better cater for the age group that has the lowest vaccination rate?

3. What is the vaccination trend looking like for the next 3 months?

4. Is there a high demand for booster doses throughout 2020–2022?

5. In which period did the demand for vaccination (administered dose / boosters) seem to decline?

### Source of the dataset

Data-driven decisions will be made through analysis of ‘COVID-19 Vaccination Age and Sex Trends in the United States, National and Jurisdictional’, which is a dataset collected by the Centers for Disease Control and Prevention between 12/13/2020 to 12/14/2022.

Reference: https://data.cdc.gov/Vaccinations/COVID-19-Vaccination-Age-and-Sex-Trends-in-the-Uni/5i5k-6cmh

Based on the data analysis, we will apply the Ridge regression model to (1) predict how many U.S. citizens have already completed the vaccination and (2) evaluate whether the current number of vaccinations is sufficient to put COVID-19 under control.

##  Data Description

This dataset contains demographic characteristics (age, sex, and age by sex) of people receiving COVID-19 vaccinations in the United States at the national and jurisdictional levels.

Data represents all vaccine partners including jurisdictional partner clinics, retail pharmacies, long-term care facilities, dialysis centers, Federal Emergency Management Agency and Health Resources and Services Administration partner sites, and federal entity facilities. 
<<<<<<< HEAD
=======

## Data Dictionary 
LOCATION VALUES:
'ME':1,'NC':2,'NY':3,'NM':4,'HI':5,'OK':6,'WI':7,'CA':8,'RI':9,'ID':10,'VT':11,'CT':12,'TN':13,'US':14,'IA':15,'FL':16,
'MP':17,'WV':18,'MN':19,'PW':20,'NV':21,'TX':22,'WY':23,'LA':24,'LA':25,'NH':26,'IL':27,'OH':28,'VA':29,'DE':30,'DC':31,'OR':32,
'KY':33,'AS':34,'KS':35,'MS':36,'CO':37,'NE':38,'PA':39,'GU':40,'VI':41,'AK':42,'MD':43,'MI':44,'ND':45,'SD':46,'AZ':47,'MO':48,
'SC':49,'FM':50,'WA':51,'IN':51,'MA':52,'MT':53,'PR':54,'AR':55,'AL':56,'NJ':57,'GA':58,'MH':59,'UT':60

DEMOGRAPHIC CATEGORY VALUES:
'Female_Ages_18-24_yrs':1,'Male_Ages_75+_yrs':2,'Ages_25-39_yrs':3,'Female_Ages_2-4_yrs':4,
'Ages_<2yrs':5,'Male_Ages_65+_yrs':6,'Female_Ages_25-39_yrs':7,'Female_Ages_65-74_yrs':8,
'Ages_40-49_yrs':9,'Female_Ages_12-17_yrs':10,'Female_Ages_<2yrs':11,'Ages_5-11_yrs':12,
'Sex_Unknown':13,'Ages_65+_yrs':14,'Male_Ages_5-11_yrs':15,'Female_Ages_40-49_yrs':16,
'Ages_2-4_yrs':17,'Ages_12-17_yrs':18,'Male_Ages_25-49_yrs':19,'Sex_Female':20,
'Female_Ages_50-64_yrs':21,'Ages_<5yrs':22,'Female_Ages_5-11_yrs':23,'Ages_50-64_yrs':24,
'Ages_<5yrs':25,'Female_Ages_5-11_yrs':26,'Ages_50-64_yrs':27,'Ages_18-24_yrs':28,
'Age_Unknown':29,'Male_Ages_<5yrs':30,'Sex_Male':31,'Male_Ages_<2yrs':32,
'Female_Ages_<5yrs':33,'Male_Ages_65-74_yrs':34,'Ages_65-74_yrs':35,'Male_Ages_50-64_yrs':36,
'Ages_25-49_yrs':37,'Female_Ages_75+_yrs':38,'Male_Ages_25-39_yrs':39,'Female_Ages_25-49_yrs':40,
'Male_Ages_40-49_yrs':41,'Female_Ages_65+_yrs':42,'Ages_75+_yrs':43,'Male_Ages_12-17_yrs':44,
'Male_Ages_2-4_yrs':45,'Male_Ages_18-24_yrs':46})
>>>>>>> 12f90eff031c8d08b6e568363b6fffd70801ec86
