# Capstone-Project
Early identification of Prediabetic   using machine learning
Domain Background

India has 61.3 million diabetes patients. The numbers are estimated to rise to 101.2 million by 2030.  

Out of all the cases of diabetes, 95% cases are of Type 2 diabetes mellitus.  The type 2 diabetes can go unnoticed for a long time, till it manifests in the form of metabolic syndromes like Retinopathy, Neuropathy, Nephropathy and Cardio vascular diseases. The prediabetic stages also carry high risk for cardiovascular diseases (CVDs).

There have been many studies that shows this large-scale epidemic is faced not only in India, but across the world at large. 

The type 2 Diabetes is a curable lifestyle disease. Due to ignorance, socio economic reasons and unhealthy food habits it has become such a big problem. If it can be diagnosed at a prediabetes level, many young and old folks alike can get the treatment in time and will be benefited from it.  

Reference articles:
1.	http://www.apiindia.org/medicine_update_2013/chap40.pdf 
2.	https://globalizationandhealth.biomedcentral.com/articles/10.1186/s12992-014-0080-x
3.	https://apps.who.int/iris/bitstream/handle/10665/204871/9789241565257_eng.pdf;jsessionid=770028777591CC613FC338061D0255F1?sequence=1
4.	https://www.who.int/diabetes/country-profiles/ind_en.pdf
5.	https://www.researchgate.net/publication/51607936_The_Indian_Council_of_Medical_Research-India_Diabetes_ICMR-INDIAB_study_methodological_details
6.	https://www.thelancet.com/journals/langlo/article/PIIS2214-109X(18)30387-5/fulltext
7.	https://www.sciencedirect.com/science/article/pii/S2214999616000035 
8.	https://www.who.int/en/news-room/fact-sheets/detail/diabetes
 

 
Problem Statement

Due to the asymptomatic nature of disease and the low disease awareness among the population, diagnosis of this disease is delayed by several years. As a result, many subjects already have vascular complications at the time of diagnosis of diabetes.  

The current challenges 
1.	High prevalence of prediabetes and very high conversion rate from prediabetes to diabetes (to the tune of 18% per year), is a great challenge.  India has nearly 3.0% of adults with prediabetes that constitutes impaired fasting glucose (IFG) and impaired glucose tolerance (IGT).  
2.	Many studies show that Indians have more body fat for any given body mass index (BMI) compared with other countries in Europe, America and Africa.  Indians also have higher levels of central obesity (measured as waist circumference [WC], WHR, visceral fat, and posterior subcutaneous abdominal fat). The prevalence of overweight in adults in India increased from 9·0% in 1990 to 20·4% in 2016; this prevalence increased in every state of the country. For every 100 overweight adults aged 20 years or older in India, there were 38 adults with diabetes, compared with the global average of 19 adults in 2016.  
3.	The food habits, along with the climate in India differs significantly from region to region. This could be also a reason why the diabetes in some of the states is more prevalent than the others.  

 
 
 
Datasets and Inputs

The dataset that will be used is available from the “data.gov.in” on the Annual health survey 2014:  Clinical, Anthropometric & Bio-chemical (CAB) Survey.

https://data.gov.in/resources/clinical-anthropometric-bio-chemical-cab-2014-survey-data-district-sitamarhi-bihar

The survey was carried out in the following nine states in India: 
RAJASTHAN
UTTAR PRADESH
ODISHA
ASSAM
MADHYA PRADESH
CHHATTISGARH
UTTARAKHAND
BIHAR
JHARKHAND

The survey was carried out in 288 districts in these states. Out of the indices captured in this survey the following indices will be analyzed for prediction of prediabetes. 

Age
BP_Diastolic
BP_Diastolic_2reading
BP_systolic
BP_systolic_2_reading
Haemoglobin_level
Length_height_cm
Marital_status
Pulse_rate
Pulse_rate_2_reading
Sex
Weight_in_kg
date_survey
district_code
fasting_blood_glucose_mg_dl
state_code
year_of_birth
BMI


 
Solution Statement

The objective of this project is to come up with a simple and noninvasive diabetes risk score that can predict the risk percentage specific to a region and sex. It can help early identification of the prediabetic stage and also help in management of related abnormalities such as dyslipidemia and hypertension and to preserve the beta cell function.  

Along with the high blood glucose level, in diabetes there is also prevalence of hypertension. The BMI also a factor that influences the occurrence of diabetes. These parameters can be easily be accessed. If there is a correlation identified between these abnormalities among a populace, it can be a good identifier for possible diabetes cases. 

We will develop a deep neural network model that can predict the risk of prediabetes based on   the available parameters like BMI index, Age, Sex, BP, hemoglobin level, Geo Social factors. 

This diabetes risk score will help significantly in alarming the high-risk individual to take appropriate action much before the diabetes surfaces. This will help in reducing the unprecedented health care challenges in India that has arose due to diabetes.


