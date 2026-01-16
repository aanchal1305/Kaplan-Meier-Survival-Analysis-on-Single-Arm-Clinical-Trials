# Kaplan-Meier-Survival-Analysis-on-Single-Arm-Clinical-Trials

Problem Statement:
A pharmaceutical company conducted a single arm clinical trial to assess the efficacy 
of their drug on patients diagnosed with lung cancer. While designing the trial, the 
primary endpoint of interest was 24-month event free survival rate. A patient was 
defined to have experienced an event only if the patient had a disease progression or 
death occurred. The standard of care for patients with this diagnosis was widely 
assumed to have a 24-month event free survival rate of 50%. The trial began on 01 Jan 
2020, and the study team recruited 200 patients over a period of 24 months. Further, the 
final analysis was conducted approximately 24 months after recruitment ended with a 
data cut-off date of 01 Jan 2024

Data Description:
1) event_or_withdrawal_date: Date on which the patient experienced an event or 
withdrew consent from the trial. If blank, then it can be 
assumed that patient neither withdrew consent from the 
trial nor experienced an event.
 
3) reason: Reason for trial discontinuation. If blank, then it can be 
assumed that the patient either completed all trial 
requirements or was lost to follow-up.

Exercise 1:  
The goal of this exercise is to assess if the study drug under consideration is significantly 
better than the standard of care currently available in terms of 24-month survival rate.  

Exercise 2 
The pharmaceutical company plans to conduct another single arm trial using the same 
drug for patients diagnosed with liver cancer. The standard of care in this case is widely 
accepted to have a 24-month survival rate of 40%. The study team believes that the 
study drug under consideration will have a 24-month survival rate of 60% and plans to 
recruit 200 patients in the trial within 24 months. Note that since this is a single arm 
trial, patients will only be recruited in the study drug arm. Further, they anticipate an 
annual dropout rate of 5%. Under the study team’s assumption, find the observed 
probability of success of the study drug being significantly better than the standard of 
care. You may have to conduct a simulation exercise to answer this question of interest. 
(You may use certain assumptions).

