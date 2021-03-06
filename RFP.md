# ClassRemainder
---
## **About this application**
- App contains two screens to display the upcoming classes of student.
- On first screen recent upcoming class with time and room number is displayed in a rectangular box.
- User clicks on box to redirect to second screen.
- Second screen displays list of all upcoming classes with time and room number.

## **Team Members**
| S No | Members                                                            | Roles              | Contact                |
|------|--------------------------------------------------------------------|--------------------|------------------------|
| 1    | [HARSHAVARDHAN KURRA](https://github.com/harshakurra123)           | Backend Developer  | S542409@nwmissouri.edu |
| 2    | [MANOJ NUVVALA](https://github.com/manojnuvvala)                   | Frontend Developer | S541998@nwmissouri.edu |
| 3    | [SAI KIRAN REDDY ENUGALA](https://github.com/saikiranreddyenugala) | Tester             | S542041@nwmissouri.edu |
| 4    | [HEMANTH VENKATA REDDY TELLURI](https://github.com/hemanth8056)    | Team Lead          | S542393@nwmissouri.edu |


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

## Functional Requirements

### Home Screen:
1.	API to get the upcoming class with room number and time.
2.	Button to redirect to list of upcoming classes.
3.	Add class button to add new class (subject, time and date, room number).
### Classes List Screen:
1.	API to display list of all upcoming classes.
2.	Edit button for each class to edit class details.
3.	Delete button for each class to delete a class.
### Login Page:
1.	Text fields to enter username and password.
2.	Button for authenticating into the application.
3.	Forgot password link, to reset the password.
### Header:
1.	Your profile link to navigate to user details.
2.	Logout button to logout of the application.

## Bidder Qualifications
- BIDDER is thoroughly familiar with all provisions and requirements of the Documents and the conditions under which the Work is to be performed.
- BIDDER finds that the proposed Contract Documents are complete, and that they are appropriate for the full, proper, and timely performance of the proposed Application.
- BIDDER possesses and commits to the OWNER the technical knowledge, practical experience, management skills.


## Schedule Duration
1. Start Date - 18-aug-2021
2. End Date - 31-mar-2022

## Schedule
| Task | Start | End |
| :--- | :----: | ---: |
| Project Plan | 18-aug-2021 | 05-sep-2021 |
| Requirements Gathering | 06-sep-2021 | 05-oct-2021 |
| UI Designs | 06-oct-2021 | 05-nov-2021 |
| Cost & Schedule | 06-nov-2021 | 05-dec-2021 |
| Setup of Project | 12-jan-2022 | 15-feb-2022 |
| Coding | 16-feb-2022 | 28-feb-2022 |
| Testing | 01-mar-2022 | 15-mar-2022 |
| Deployment | 16-mar-2022 | 31-mar-2022 |


## GUI
  ### Screen1
  ![Screen1](images/Screen1.jpg)
  ### Screen2
  ![Screen2](images/Screen2.jpg)
  ### LOGIN SCREEN  
  ![LOGIN_PAGE](images/loginwithlogo.jpg)
  
 
## References
- [Django Documentation](https://docs.djangoproject.com/en/3.2/)
- [Python Documentation](https://docs.python.org/3/tutorial/)
