C195 Software II - Advanced Java Concepts - WGU Schedule Application

<img src="https://imgur.com/a/M2f7cqd" alt="Many-to-Many">

The purpose of this application is to schedule appointments easier than before. My application I built was made to easily
add, modify, or delete an appointment or customer. Your log in screen will be the first to pop up on the application, then you
will be directed to the appointments screen and that will give you full customization to add, modify, delete, and update. You will have a 
customers screen you can add, modify, delete, and update. There is a reports screen where you can generate a report by month/type,
by user, and for a customer's schedule that will open on a new screen.


Author: Zackery Reynolds
Contact Info: zreyno7@wgu.edu
App Version: 1.0
Date: 7/13/2021

IDE: Apache Netbeans IDE 12.3
JDK: Version 11.0.11 Windows 64-bit
JavaFX: Version 11.0.2 Windows 64-bit


Upon creating the application, I tried to make it as easy as possible to make the scheduling application user-friendly. Once
you run the program, you will see whether you're system is set to English or French, you will notice that it is able to track what 
country you are in and will ask you to provide your credentials, which in this case is:

username: test password: test

and once you have successfully logged in, there will be a pop-up that notifies you of your appointments that are coming up, if
you don't have one coming up then it will let you know that you do not have an appointment that is scheduled. Now that you are
directed to the appointments screen, you will see a few button options presented, such as:


Appointments:

All/Week/Month: There are three radio buttons representing view by all, month, or week. You will notice that when you click the
month and week, it will show you reports for anything equal to today or after's dates.

Reports Screen: This will take you to the reports screen.

Customers Screen: This will take you to the customers screen.

Add Appointment: You will be able to enter all of the customer's information for the appointment by filling out the text fields,
select the pre-loaded data in the drop down lists, and pick a date and time. After you will out the information then you can
click the add appointment button to save the information for the new appointment but you will be notified for any error that 
may occur, if no error then your appointment will be scheduled.

Update Appointment: This is where you can modify the customer's information for an existing appointment for the database. You will
have the option to update the title, description, location, contact, type, start time/date, end time/date, and customer. You will be
able to save the information by click the update modifications button.

Delete Appointment: If you made a mistake or want to cancel an appointment, there is an option to delete an appointment with
an alert notification letting you know the appointment has been successfully deleted.

Exit: There is an exit button to exit to whole program, which is shown on the appointments screen since this is the main screen.


Customers:

Add Customer: This is where you will enter a new customer's information and click the add customer button to enter it into the
database.

Update Modifications: This is what you will click once you're finished modifying the customer to save the updates in the database.

Delete Customer: You will be able to select a user you would like to delete, there will be a pop-up notification letting you know
the customer has been deleted.


Reports:

Reports By Month/Type: There will be a drop down list that will list all 12 months. You will be able to check if there are any reports
to generate by selecting a month and clicking the Go button. There will be a pop-up that lets you know how many appointments for each
month.

Reports By Contact: You will have a drop down list and you can select the contacts from the database, once you select the contact you want
you can click the Go button and it will direct you to a new screen. The new Reports Schedule screen will show all reports for the contact
you selected. You are able to click the back button and be directed back to the Reports screen.

Reports By User: You can enter a user id in the text field and a pop-up will show letting you know how many appointments each user has by
the user id.

Overall, you are able to sort each appointment by ID, title, description, location, contact, type, start date, end date, or
customer. I decided to go with a user-friendly application that will be easy to navigate around to find the information you
need at the time. No experience needed and anyone can learn fast. Everything you need is right in front of you. The database
populates the fields on the application and will populate once a new appointment or customer is entered into the table.


MySQL Connector: mysql-connector-java-8.0.23

Javadoc Path: C:\Users\wrey1\OneDrive\Documents\NetBeansProjects\JavaApplication14\javadoc\index.html

README Path: C:\Users\wrey1\OneDrive\Documents\NetBeansProjects\JavaApplication14

Login Activity Path: C:\Users\wrey1\OneDrive\Documents\NetBeansProjects\JavaApplication14

Lambda Comments:
- ApptsMainController.java line 272.
- UpdatingCustsController.java line 146.



















