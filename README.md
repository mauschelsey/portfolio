# Data Analyst

**Technical Skills: Python, SQL, Tableau, Scikit-learn, Excel**

## Education
M.S., Data Science -- University of North Dakota _(May 2026)_

B.A., Theatre Arts -- Pepperdine University _(April 2016)_

## Projects
**Employee Attrition in Healthcare | Machine Learning | May 2026**
- High employee turnover rates can be costly for hospitals and impact patient care. To assist hospitals in addressing this relevant business problem the question "Which factors have the greatest impact on employee attrition rates in healthcare?" was investigated.
- A synthetic dataset designed for healthcare settings based on the IBM Watson dataset for attrition was utilized for this project.
- Random Forest and Neural Network models were chosen for analysis of the dataset using the model inspection technique Permutation Feature Importance to determine the top 5 features which impact employee attrition rates in healthcare. 
- Correlated features were removed from the dataset to prevent redundant information from eroding model quality along with features which provided little predictive value.
- Data was cleaned and prepped for model training and the following pipelines were built using Scikit-learn.
  
![Random Forest Pipeline](/assets/img/RF_Pipeline.jpg)
_Random Forest Pipeline_

- A Random Forest & Neural Network model were selected as Random Forest is one of the most effective models when researching employee attrition rates and deep learning models such as Neural Network are the next phase in research.
  
![Neural Network Pipeline](/assets/img/NN_Pipeline.jpg)
_Neural Network Pipeline_

- ADASYN was used to address the large class imbalance in the dataset for the target value of attrition.
- The metrics accuracy and recall were used for evaluation favoring recall due to the class imbalance and a preference for false positives compared to false negatives since missed predictions could lead to understaffing which would greatly impact patient care. 
-	Permutation Feature Importance Technique was applied to the Neural Network model which had a higher recall score to identify the five most influential factors impacting model performance.

![Box Plot of Permutation Feature Importance Technique Results](/assets/img/Permutation_Recall.png)

- The five features which consistently had an affect on the models predicting employee attrition rates include: Overtime, Age, Monthly Income, Years at Company, & Number of Companies. 

[Full Report](/assets/docs/Final-MausC.pdf)

**Patient Satisfaction Interactive Dashboard | Data Visualization |	May 2026**
- Data from the HCAHPS survey was analyzed to answer the question "Which hospitals have the highest levels of patient satisfaction?"
- The Hospital Consumer Assessment of Healthcare Providers and Systems Survey (HCAHPS) provides data on patient experience after a recent hospital stay in hospitals across the United States which accept payments from Medicare & Medicaid.
- Data was sourced from the archives for Centers for Medicare & Medicaid Services for the years 2020-2025. 
-	Using Python & Pandas data was cleaned and prepared for use in Tableau with a total of 7,505,535 records and 23 features. 
- The Patient Survey Star Rating was used in the dashboard to represent the patient's experience as an overall rating of patient satisfaction for hopsitals with at least 100 completed surveys over a four-quarter period. 
- An interactive dashboard in Tableau was prepared for hospitals across the United States to analyze their patient satisfaction from the years 2020-2025 and can serve as an assessment tool for hospital administrators. 

![Patient Satisfaction Dashboard](/assets/img/Patient_Satisfaction_Dashboard.jpg)

[Interactive Dashboard on Tableau](https://public.tableau.com/app/profile/chelsey.maus/viz/PatientSatisfactioninHospitalsAcrossAmerica/UpdatedDashboard)

[Full Report](/assets/docs/Final-MausC.pdf)

## Work Experience
**Environmental Educator @ Finn Partners _(January 2023 - Present)_**
- Deliver interactive environmental education assemblies to 200-500 K-5 students, adapting presentation strategies based on audience engagement and educator feedback to improve learning outcomes and program effectiveness.
- Track attendance, engagement patterns, and qualitative feedback across school presentations to identify trends and refine delivery.
- Generate reports summarizing engagement outcomes and recommendations for enhancing programing effectiveness.
- Coordinate audio-visual logistics, scheduling, and troubleshooting across multiple school locations ensuring reliable program execution while identifying process improvements that increase operational efficiency.

**Certificated Substitute Teacher @ LAUSD _(January 2017 - Present)_**
- Maintain accurate student and classroom records while ensuring compliance with district reporting requirements.
- Analyze student performance data and adapt instructional approaches based on observed trends and outcomes.
- Communicate information effectively to diverse audiences including students, teachers, and administrators.
- Manage competing priorities in fast-paced environments while maintaining accuracy, organization, and attention to detail.
- Apply data-informed decision making to support classroom performance and operational continuity.
  
## [Tableau](https://public.tableau.com/app/profile/chelsey.maus/vizzes)

## [LinkedIn](https://www.linkedin.com/in/chelsey-maus-134665b2/)
