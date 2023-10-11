# Predicting-Parkinsons-with-Voice-data
#== DATASET INFORMATION ==#
This is a machine learning model that I created for my first machine learning exam. This code is a comprehensive script that performs various data analysis and machine learning tasks on a dataset related to voice features, which is used to predict alzheimers disease.

The dataset is from Oxford Parkinson's Disease Detection Dataset
Data Set Characteristics: Multivariate
Number of Instances: 197
Area: Life
Attribute Characteristics: Real
Number of Attributes: 23
Date Donated: 2008-06-26
Associated Tasks: Classification
Missing Values? N/A

Data Set Information:

This dataset is composed of a range of biomedical voice measurements from 
31 people, 23 with Parkinson's disease (PD). Each column in the table is a 
particular voice measure, and each row corresponds one of 195 voice 
recording from these individuals ("name" column). The main aim of the data 
is to discriminate healthy people from those with PD, according to "status" 
column which is set to 0 for healthy and 1 for PD.

The data is in ASCII CSV format. The rows of the CSV file contain an 
instance corresponding to one voice recording. There are around six 
recordings per patient, the name of the patient is identified in the first 
column.For further information or to pass on comments, please contact Max 
Little (littlem '@' robots.ox.ac.uk).

Further details are contained in the following reference -- if you use this 
dataset, please cite:
Max A. Little, Patrick E. McSharry, Eric J. Hunter, Lorraine O. Ramig (2008), 
'Suitability of dysphonia measurements for telemonitoring of Parkinson's disease', 
IEEE Transactions on Biomedical Engineering (to appear).

-----------------------------------------------------

Attribute Information:

Matrix column entries (attributes):
name - ASCII subject name and recording number
MDVP:Fo(Hz) - Average vocal fundamental frequency
MDVP:Fhi(Hz) - Maximum vocal fundamental frequency
MDVP:Flo(Hz) - Minimum vocal fundamental frequency
MDVP:Jitter(%),MDVP:Jitter(Abs),MDVP:RAP,MDVP:PPQ,Jitter:DDP - Several 
measures of variation in fundamental frequency
MDVP:Shimmer,MDVP:Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,MDVP:APQ,Shimmer:DDA - Several measures of variation in amplitude
NHR,HNR - Two measures of ratio of noise to tonal components in the voice
status - Health status of the subject (one) - Parkinson's, (zero) - healthy
RPDE,D2 - Two nonlinear dynamical complexity measures
DFA - Signal fractal scaling exponent
spread1,spread2,PPE - Three nonlinear measures of fundamental frequency variation 

-----------------------------------------------------

Citation Request:

If you use this dataset, please cite the following paper: 
'Exploiting Nonlinear Recurrence and Fractal Scaling Properties for Voice Disorder Detection', 
Little MA, McSharry PE, Roberts SJ, Costello DAE, Moroz IM. 
BioMedical Engineering OnLine 2007, 6:23 (26 June 2007)

#== PROJECT PROMPT INFORMATION ==#
Machine learning approaches to identify Parkinson’s disease using voice signal 
features.
Parkinson’s Disease (PD) is the second most common age-related neurological disorder that leads 
to a range of motor and cognitive symptoms. A PD diagnosis is difficult since its symptoms are 
quite like those of other disorders, such as normal aging and essential tremor. When people reach 
50, visible symptoms such as difficulties walking and communicating begin to emerge. Even 
though there is no cure for PD, certain medications can relieve some of the symptoms. Patients 
can maintain their lifestyles by controlling the complications caused by the disease. At this point, 
it is essential to detect this disease and prevent it from progressing. The diagnosis of the disease 
has been the subject of much research. In this Exam, your objective is to detect PD using 
different types of Machine Learning (ML) models such as K-Nearest Neighbor (KNN), and 
Logistic Regression to differentiate between healthy and PD patients by voice signal features.
Dataset
The study included voice recordings from 31 people, including 23 people with Parkinson’s Disease 
(PD) (16 males and 7 females) and eight Healthy Controls (HC) (males = 3 and females = 5). The 
dataset contains 195 records, 24 columns, and as presented in Table 1, a series of biomedical voice 
measurements. Table 1 is divided into columns that represent each of the voice measurements and 
rows which represent vocal recordings from individuals (the “name” column). An average of six 
recordings were made for each patient; six recordings were taken from 22 patients, and seven 
recordings were taken from nine patients. The patients’ ages ranged from 46 to 85 years (mean 
65.8, standard deviation 9.8), and the time since diagnosis ranged from 0 to 28 years. Each row 
corresponds to one voice recording for 36 s. The voice was recorded in an industrial acoustic 
company sound-treated booth by a microphone placed 8cm from the mouth. In the dataset, the 
“status” column is set to 0 for HC and 1 for those with PD, to distinguish healthy individuals 
from those with PD. 
Table 1 Matrix column entries (attributes):
name - ASCII subject name and recording number
MDVP:Fo(Hz) - Average vocal fundamental frequency
MDVP:Fhi(Hz) - Maximum vocal fundamental frequency
MDVP:Flo(Hz) - Minimum vocal fundamental frequency
MDVP:Jitter(%), MDVP:Jitter(Abs), MDVP:RAP, MDVP:PPQ, Jitter:DDP - Several 
measures of variation in fundamental frequency
MDVP:Shimmer, MDVP:Shimmer(dB), Shimmer:APQ3, Shimmer:APQ5, MDVP:APQ, 
Shimmer:DDA - Several measures of variation in amplitude
NHR, HNR - Two measures of ratio of noise to tonal components in the voice
status - Health status of the subject (one) - Parkinson's, (zero) - healthy
RPDE, D2 - Two nonlinear dynamical complexity measures
DFA - Signal fractal scaling exponent
spread1, spread2, PPE - Three nonlinear measures of fundamental frequency variation
Use the Machine Learning algorithms K-Nearest Neighbor (KNN), and Logistic Regression, and 
the DB_Voice_Features.csv database to discriminate and evaluate classification performance of
healthy and PD patients by voice signal features.
