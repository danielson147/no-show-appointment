# no-show-appointment
This dataset has information for 110,527 medical appointments in Brazil. It has 14 columns which are as follows:

PatientId: This is a unique identification number given to each patient.
AppointmentID: This is also a unique identification number for every scheduled appointment.
Gender: This column specifies the gender of the patient.
ScheduledDay: This is the date on which the appointment was scheduled by the hospital.
AppointmentDay: This is the date a patient is expected to visit the hospital.
Age: This column indicates the age of the patient.
Neighbourhood: This indicates the location of the hospital.
Scholarship: This column indicates whether a patient is enrolled in Brasilian welfare program (Bolsa Familia) or not.
Hipertension: This indicates whether the patient is hypertensive or not. This has '0' and '1' status. Where '0' is for patients that are not hypertensive and '1' is for patients that are hypertensive.
Diabetes: This indicates whether the patient is diabetics or not. This has '0' and '1' status. Where '0' is for patients that are not diabetics and '1' is for patients that are diabetics.
Alcoholism: This indicates whether the patient is an alcoholic or not. This has '0' and '1' status. Where '0' is for patients that are not alcoholic and '1' is for patients that are alcoholic.
Handcap: This indicates whether the patient is physically challenge or not. it has numbers from '1' to '4'. '1' indicates that a patient has 1 physical challenge while '2', '3' and '4' indicates that the patient has 2, 3, 4 physically challenges respectively.
SMS_received: This indicates whether an SMS message was sent out to the patient or not. it has '0' and '1' values, where '0' is for patients that didi not receive SMS message and '1' is for those that received SMS messages.
No-show: This column indicates whether a patient actually visited the hospital on the day of appointment or not. It has 'Yes' and 'No' values, where 'Yes' is for patients that did not show up for their appointments and 'No' is for patients that showed up for their appointments.
The purpose of this investigation is to analyse the dataset and come up with factors that could be responsible for patients not showing up for their appointments. This will help the hospitals to manage their staff in case patients did not show up as predicted. The dependent variable in the dataset is the No-show column because it depends on other variables, while the independent variables are Age, Scholarship, Hypertension, Diabetes, Handicap, Alcoholism and SMS_received. These independent variables could be responsible for the outcome of the dependent variable. Therefore, a patient showing up or not could depend on their age, gender, enrollment in Brasilian Welfare Program (Bolsa Familia), their health status (hypertensive, diabetics or handicap), their level of alcohol intake and wether he or she received SMS message, as a reminder, or not.

In this investigation, the following variables will be analysed to determine the factors we need to consider in order to know if a patient will show up for his or her appointment or not:

Dependent variable: No-show
Independent variables: Age, Scholarship and SMS_received.
