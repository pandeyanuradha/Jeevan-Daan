# Jeevan-Daan

Jeevan Daan is a secure transplant information database that contains all data on the **candidate waiting list, organ donation and matching, and transplantation**. This system will be critical in helping organ transplant institutions match waiting candidates with donated organs. It contains different interfaces for doctors, patients and an admin.

## Domain description 

1. The database stores information regarding each patient who will have a unique ID, name, phone no. , birth date, admission time, ICU, time of death, agreement for donation, their medical charts(blood pressure, heart rate, body temperature, blood group), organ donated/required.
2. The ICU table contains the location of the ICU, name, ICU type contact no, hospital registration and capacity.
3. Each doctor has a unique ID ,name ,age ,gender ,Department, post , phone no, etc.
4. The department table keeps track of the doctors registered in that department.

## Functionalities 

1. Authorised login and sign-up for donors, patients seeking organs/blood donors, doctors and admin. Signing up will automatically add them to the relevant database. 
2. ICUs/Doctors can be added to the database by admin.
3. Generate table of ICUs(can be displayed in order of location proximity), table of doctors and patients in a particular ICU.
4. Generate a table of blood banks and ICUs on the basis of different filters, like location proximity, and donor availability.
5. If the requirements match according to the above criteria, then a request can be sent from one ICU to another for emergency transportation. If the request is accepted, then that patient gets deleted from the donor table and the user who requested the donor will get a notification.
6. Users can sign up for blood donation and find the closest ICU for the same.
7. Admin can delete patients and doctoes from ICU.

## Tech - stack used in this project - 
1. NodeJS and Express for Backend
2. ReactJS for Frontend
3. Postman for testing the APIs
