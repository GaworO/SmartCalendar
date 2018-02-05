# SmartCalendar

This aplication is build with Python ,JavaScript , jQuery , Bootstrap , Bottle and SQLAlchemy.

What can be found in the app ?

1) Main Page 

This page is available at index.html. There is possibility to rejester and login on the main page. The graphics have been made with bootstrap. 


2) User interface 

When user logs in or register it is possible to see an interactive calendar made with java script , when you click a day it will redirect you to the formular that takes the choosen date from the calendar and also loads data about all possible objects into formular. There is possibility to choose sport or obeject where the user wants to play. When you fill the formular and sign in it will redirect you to the page with calendar and show all the events that you are sign in. There is a possibility to delete the chosen event. 



3) Admin interface 

When admin logs in he can see all users , all events that user has sign in , and all possible sport objects. There is also possiblity for admin to edit and delete all users , events and sport objects. 


All possible routes : 

Main Page 

1 localhost:8080

User Interface

1 User Registration /registerUser 
2 User Log In /login 
3 User Authentication /loginS 
4 Calendar JS /sala 
5 Calendar form /sala 
6 Event Delete /delete/user/<id> 
7 User Log out /logout 
  
Admin Interface

1 Admin Log In /adminSi 
2 Admin Authentication /adminSi 
3 Add New Gym /adminSi 
4 Update Gym /<id>/updaterecord
5 Delete Gym /deleterecord/<id> 
6 Update User /<id>/updateuser 
7 Delete User /deleteuser/<id>
8 Update Event /<id>/updateevent 
9 Delete Event /deleteevent/<id>
10 Admin Log out /logout 
  
To run the aplication you need to have installed on your computer SQLAlchemy and bottle. It is possible just to download them and add to the project. 

To run the aplication just simply type python app.py into console in the file where you hold your project. 
  
  



