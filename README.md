# ANLY-530-Group-Project-Heart
Heart Failure Prediction



Heart Failure Prediction
Team 1
Michelle Irina, Made Enoh, Chhatbar, Dixit, Douadi, Rabah, Mondal, Argha, Prabhu, Saurabh Shirish

Context
Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide. Four out of 5CVD deaths are due to heart attacks and strokes, and one-third of these deaths occur prematurely in people under 70 years of age. Heart failure is a common event caused by CVDs and this dataset contains 11 features that can be used to predict a possible heart disease.

People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management wherein a machine learning model can be of great help.

The dataset can be found here: https://www.kaggle.com/fedesoriano/heart-failure-prediction.

Attribute Information
Variable	Details	Unit
Age	age of the patient	[years]
Sex	sex of the patient	[M: Male, F: Female]
ChestPainType	chest pain type	[TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
RestingBP	resting blood pressure	[mm Hg]
Cholesterol	serum cholesterol	[mm/dl]
FastingBS	fasting blood sugar	[1: if FastingBS > 120 mg/dl, 0: otherwise]
RestingECG	resting electrocardiogram results	[Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
MaxHR	maximum heart rate achieved	[Numeric value between 60 and 202]
ExerciseAngina	exercise-induced angina	[Y: Yes, N: No]
Oldpeak	oldpeak = ST	[Numeric value measured in depression]
ST_Slope	the slope of the peak exercise ST segment	[Up: upsloping, Flat: flat, Down: downsloping]
HeartDisease	output class	[1: heart disease, 0: Normal]
Source
This dataset was created by combining different datasets already available independently but not combined before. In this dataset, 5 heart datasets are combined over 11 common features which makes it the largest heart disease dataset available so far for research purposes. The five datasets used for its curation are:

Cleveland: 303 observations
Hungarian: 294 observations
Switzerland: 123 observations
Long Beach VA: 200 observations
Stalog (Heart) Data Set: 270 observations

The original datasets can be found here: https://archive.ics.uci.edu/dataset/45/heart+disease




References:
[1] fedesoriano. (September 2021). Heart Failure Prediction Dataset. Retrieved [Date Retrieved] from https://www.kaggle.com/fedesoriano/heart-failure-prediction.
[2] Janosi,Andras, Steinbrunn,William, Pfisterer,Matthias, and Detrano,Robert. (1988). Heart Disease. UCI Machine Learning Repository. https://doi.org/10.24432/C52P4X. https://archive.ics.uci.edu/dataset/45/heart+disease
[3] Detrano, R.C., Jánosi, A., Steinbrunn, W., Pfisterer, M.E., Schmid, J., Sandhu, S., Guppy, K., Lee, S., & Froelicher, V.F. (1989). International application of a new probability algorithm for the diagnosis of coronary artery disease. The American journal of cardiology, 64 5, 304-10 . https://www.semanticscholar.org/paper/International-application-of-a-new-probability-for-Detrano-J%C3%A1nosi/a7d714f8f87bfc41351eb5ae1e5472f0ebbe0574
