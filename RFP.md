# ClassRemainder
---
## **About this application**
- App contains two screens to display the upcoming classes of student.
- On first screen recent upcoming class with time and room number is displayed in a rectangular box.
- User clicks on box to redirect to second screen.
- Second screen displays list of all upcoming classes with time and room number.

## **Team Members**
1. HARSHAVARDHAN KURRA - Backend Developer
2. MANOJ NUVVALA - Frontend Developer
3. SAI KIRAN REDDY ENUGALA - Tester
4. HEMANTH VENKATA REDDY TELLURI - Team Lead

## Requirements
- Python
- Django
- Postgresql
- React js

## Client
Name: Dr. Dennis Case <br>
Email: dcase@nwmissouri.edu <br>
Phone: 660.562.1136 <br>

## Database Tables
- User
  - id
  - name
  - role
  - is_delete
- Class Details
  - id
  - user_id
  - classroom_id
  - start_time
  - end_time
  - is_delete
- Classroom Details
  - id
  - room_number
  - subject
  - is_delete

## Entity Relationship Diagram
![erdiagram](images/erdiagram.png)

## API's required
- User - POST, GET, PUT, DELETE
  - POST - API for adding user to the system.
  - GET - API for getting list of Users.
  - PUT - API for updating data of user.
  - DELETE - API for deleting users.

- ClassroomSchedule - POST, GET, UPDATE, DELETE
  - POST - API to schedule a class to the user.
  - GET - API to get the class assosiated to the user.
  - PUT - API to change the class assosiated to the user.
  - DELETE - API to delete class schedule of user.



