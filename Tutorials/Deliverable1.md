## Deliverable 1: Pitch

Course: SEG4105

Student Name: Michias Shiferaw

Student Number: 300188168


## Overview
 
Hotel-Palace is a comprehensive hotel-management program designed to facilitate and manage the operation of a chain of hotel branches. The program serves multiple purposes, both for hotel personnel and visitors, to enhance the overall experience of booking rooms at a variety of hotels across North America. The purpose of the application is to stand as a tool that benefits both corporations and guests by serving as a central hub for ultimate and efficient service.
 
 
## Problem & Appetite
 
Currently, the staff/employee component of the program is fairly limited. The daily responsibility of supervising hotel obligations is time-consuming, so we are actively considering hiring more people. __The problem is that we are manually onboarding employees using PostgreSQL__. As a result, workflow is difficult to maintain as we have to close the application to add employees leading to the application being turned off as well as losing potential guests because of this.
 
The goal is to make employee onboarding more efficient. Allowing an existing employee to go through a form sheet that will ask for the new employee's details, results in the new employee being added to the database.
 
Given the circumstances, we are constrained by the time limits of the course, thus we would need to develop the idea by the end of a 6-week period. Ideally, with little interruption, it would take us no more than 6 weeks to implement our idea.
 
 
## Time budget
 
6 weeks
 
## Solution
 
A linear path sequence from the dashboard to add new employees is only accessible to existing employees. The form will be connected to an existing backend-triggered schema that will check for validation and ultimately prepare a query into the employee table.
The new employee form will include requests of name (first and surname), date of birth, personal email address, and living address.

The new process is described in the sketch below.


### Breadboard

 ![Breadboard](https://github.com/MichiasShiferaw/seg4105_playground/blob/main/Labs/lab03/Breadboard.jpg)


### Fat Marker
 ![Fat-Marker](https://github.com/MichiasShiferaw/seg4105_playground/blob/main/Labs/lab04/Fat-Marker.jpg)

 
 
## No-goes (nice-to-haves)
* Email confirmation is to be sent employee's personal email
* Automation input filling from document
    * From resumes or forms filled out from job-searching sites (i.e. workday, or indeed)
* Categorizes employees based on department
* Accepting  information that isn't related to employment onboarding
* Loading screen after submission
 
 
 
## Rabbit Holes
* __Removal of employees__: The deletion operation will be exempted from this pitch as we want to maintain consistency in our appetite and focus on adding employees.
* __Specialized employees to only be allowed to hire (HR department)__: Specialized employees are not our priority in this pitch as it is seen as a time-consuming path that will require adjustments in our database schemas.
* __Group employment (chained lists of new employee forms)__: Not perceivable within our appetite, can be reconsidered in future pitches.
* __Update employees' information after onboarding__: Update operation will be exempted from this pitch as we want to maintain consistency in our appetite and focus on the onboarding process.
* __Draft employment forms__: not conceivable in the provided time.


