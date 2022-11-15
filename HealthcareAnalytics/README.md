# Healthcare Analytics

A medical centre offers various services that require customers to book appointments in advance – including medical appointments, small surgery, blood test... Most customers attend their appointments on time, but nonetheless about 20% of the patient fail theirs appointments. A no-show is costly to the medical centre as it blocks diary slots for patients that otherwise may attend – and it also implies that the patient that no-shows misses out on an opportunity to look after their health. The medical centre wants to reduce the impact of no-shows by calling or texting in advance patients that are likely to no-show to remind them of the appointment or offer to reschedule.

## Dataset

The dataset is available on Kaggle and is composed of 110,527 medical appointments and 14 features.

Data Dictionary
- PatientId: patient unique ID
- AppointmentID: appointment unique ID
- Gender: Male or Female
- ScheduledDay: the day someone called or registered the appointment, this is before appointment of course
- AppointmentDay: the day of the actual appointment, when they have to visit the doctor
- Age: How old is the patient
- Neighbourhood: where the appointment takes place
- Scholarship: True of False
- Hipertension: True or False
- Diabetes: True or False
- Alcoholism: True or False
- Handcap: True or False
- SMS_received: True or False
- No-show : True or False

## Insights

- Female patients have taken more appointments then male patients

- Ratio of Nohow and Show is almost equal for age group except Age 0 and Age 1 with 80% show rate for each age group

- Each Neighbourhood have almost 80% show rate

- There are 99666 patients without Scholarship and out of them around 80% have come for the visit and out of the 21801 patients with Scholarship around 75% of them have come for the visit.

- There are around 88,726 patients without Hypertension and out of them around 78% have come for the visit and Out of the 21801 patients with Hypertension around 85% of them have come for the visit.

- There are around 102,584 patients without Diabetes and out of them around 80% have come for the visit and Out of the 7,943 patients with Diabetes around 83% of them have come for the visit.

- There are around 75,045 patients who have not received SMS and out of them around 84% have come for the visit and out of the 35,482 patients who have received SMS around 72% of them have come for the visit.

- There is no appointments on sunday and on saturday appointments are very less in comparision to other week days
