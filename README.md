# NoShowAppointment -Investigate_a_Dataset
![MIT-Smart-Schedule](https://user-images.githubusercontent.com/44718084/197361706-bf5b03f1-f33a-46b7-b2da-d80e98b44439.png)
### Udacity-Data-Anayltic-Project-1 

This projects  consisted of a data set from https://www.kaggle.com/datasets/joniarroba/noshowappointments which consist of:
#### Content
110.527 medical appointments its 14 associated variables (characteristics). The most important one if the patient show-up or no-show to the appointment.
which where:
- PatientId
Identification of a patient
- AppointmentID
Identification of each appointment
- Gender
Male or Female . Female is the greater proportion, woman takes way more care of they health in comparison to man.
- Appointment date
The day of the actuall appointment, when they have to visit the doctor.
- DateAgreement
The day someone called or registered the appointment, this is before appointment of course.
- Age
How old is the patient.
- Neighborhood
(Where the appointment takes place.)
- Scholarship
(True of False . Observation, this is a broad topic, consider reading this article https://en.wikipedia.org/wiki/Bolsa_Fam%C3%ADlia)
SMS_received
(1 or more messages sent to the patient.)
## Our Boolean Virables Where 
- Hipertension
- Diabetes
- Alcoholism
- Handicap
- No-show and Scholarship

#### Insight 

- We Noticed that
1. Most people with Hadicaps did Show Up  for thier appointments 
2. Hypertension most mostly found in Patient Age above 60 and but less in patient aged 80
![__results___51_1](https://user-images.githubusercontent.com/44718084/197362325-c302b1da-f289-42fe-85da-12bcb635b9f8.png)
![__results___59_0](https://user-images.githubusercontent.com/44718084/197362475-ac71bb26-ab2c-4cf8-a524-3225ad219e84.png)
#### Our Limitations 
Our Invesgitation revealed that Hypertensive Patients don't always show up for hospital appointment.We also saw that patients with handicaps where not classified like other patient that is as Been either handicap or not but each patient with handicaps was classified according to the number of handicaps they have. Moreover the data provided on Patients with handicap was limited we had more patients with no handicap and less with handicaps and also dropping duplicate columns reduced the quqntity of patient data we had this result to us not been able to prove wethere or not the patient's handicap was a preventing factor for not showing up.Therefore the Insufficent of data might cause our results to not be completely error free and having more data on the patients will help us Know better if the fact that patients have a handicap is more of a preventive factor than hypertension or not.
#### Conclusion
In our dataset we discovered our Preventive Factor was Hypertension
We also also saw that some patients could have more than one handicap but this didn't account for them not showingup for and appointment we also attributed this to the fact that we had more Patients with no handicap and less patient with a handicap
And finally we saw that patients affected by Hypertension lie mostly between the Ages of 20 to about 100

- [ ] @kaggel.com :tada: https://www.kaggle.com/code/haggaiakumbom/noshowappointment-investigate-a-dataset
