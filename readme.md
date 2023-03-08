# Project 3 Bernerd's app

![](https://github.com/yutaro741/project/blob/main/photo/work1_image03%20copy.jpg)


# Criteria A: Planning

## Problem definition
Bernerd is a student studying for IB at UWC ISAK Japan. He has a lot of things to do in his life, such as Homework, CAS activity, part time job and his hobby. He is finding it is hard to manage his task for those massive amounts of tasks. So, he is willing to have an application that solves that problem. He requires the Login and Register system, which makes his girlfriend use that as well. He wants not only the parts to add tasks, but also edit the tasks to be able to cope with changing deadlines. He didn’t mention how he wants to see the tasks, but because he likes photography, he strongly wants to change the colors of the tasks, to make it easy to see.


## Proposed Solution
Proposed solution:
Design Statement
To solve my client's problem, I will create an application to manage the tasks for him. I will be using Python as the primary programming language for the application, KivyMD for the graphical user interface (GUI), and SQLAlchemy to manipulate the database in which the tasks logs will be stored. The application will consist of a login page, a registration page, main page, page to edit the task, and page to see all of the task.

System
The application to manage appliance usage will be developed on the programming editor PyCharm version 2022.3.2, run on a 2020 MacBook Pro using the OS macOS Big Sur version 13.2.1. Through PyCharm, the application will be coded using Python, KivyMD for the GUI, and SQLite to manipulate the database.

## Software Justification
Python

I will be using Python as the primary programming language for the following reasons. Firstly, Python is high-level, interpreted, simple syntax language, making it accessible to beginner programmers while still maintaining a high degree of flexibility and practicality for a variety of projects. Additionally, Python is regarded as one of the fastest growing programming languages, which means the resources online that may aid in the developement of this project will be abundant. Secondly, ranked above C, I am most familiar coding in Python, which will make the project run much faster than if I would need to learn a new programming language. Lastly, Python is an object-oriented programming language, which will be useful for this project since OOP frameworks are modular, making it easy to identify problems in the code, the code can be reusable through inheritance, and functions can be flexible and usable across multiple classes due to polymorphism.

KivyMD

I will be using KivyMD to create the graphical user interface, which is an open source library capable of creating graphical user interfaces (GUI) for applications. In this project, the GUI will act as the communication between the user, who will input commands and view information through their keyboard and computer screen, and the program, which will manipulate the database to create, add, edit and delete data. The GUI is a crucial component of this application, as it will allow the client, or anyone including those without experience in programming, to easily access the logs.

SQLite
I have chosen to use SQLite as the database management system for this project. SQLite is a lightweight, embedded relational database engine that is perfect for small to medium scale projects. It's highly efficient, fast and reliable, making it a popular choice for developers. Additionally, SQLite is open source and requires no setup or administration, making it easy to integrate with any project. With its ability to handle large amounts of data and its support for SQL, SQLite provides a powerful solution for data storage and retrieval. Furthermore, SQLite is cross-platform compatible, which means that the application can run seamlessly on different operating systems such as Windows, Linux and macOS.


## Success Criteria
1. Login and Register system (Encrypt password)
2. Adding journal (Name, category, due date, tag color)
3. Be able to Edit journal
4. Be able to change color easily
5. Be able to delete the task finished with one button
6. Be able to pick the date easely.


# Criteria B: Design
## System Diagram
![](https://github.com/yutaro741/project/blob/main/photo/Screen%20Shot%202023-03-07%20at%2016.26.18.png)
## Flow Diagrams
Login system
![](https://github.com/yutaro741/project/blob/main/photo/F343FB60-E71B-4140-94DD-82DE76A4D329.jpg)

Registerasion system
![](https://github.com/yutaro741/project/blob/main/photo/CD6F0DF9-D993-485E-BC88-E8C2FA7F2901.jpg)

Add note system
![](https://github.com/yutaro741/project/blob/main/photo/177CC81C-FD04-4678-806C-FBE31C8F4453.jpg)

Edit note system
![](https://github.com/yutaro741/project/blob/main/photo/260CF555-6A80-420A-BCBA-51ECE1080E96.jpg)

Show data table system
![](https://github.com/yutaro741/project/blob/main/photo/657BF954-12FD-4CFC-908D-CC591DB00141.jpg)

## Wire frame
![](https://github.com/yutaro741/project/blob/main/photo/83343B53-AD3A-4DAE-A3B8-C9D37D1D7FED.jpg)

## Record of Tasks
| Task No 	| task                                                                	| Planned Outcome                                                                                                                	| Time estimate 	| Target completion date 	| Criterion 	|
|---------	|---------------------------------------------------------------------	|--------------------------------------------------------------------------------------------------------------------------------	|---------------	|------------------------	|-----------	|
| 1       	| First meeting with client                                           	| Identify problem, set up future meeting(s)                                                                                     	| 20m           	| Feb20                  	| A         	|
| 2       	| Create proposed solution and success criteria                       	| Write proposed solution and success criteria.                                                                                  	| 1h            	| Feb20                  	| A         	|
| 3       	| Research rationale                                                  	| Research and create a logical rationale behind the tools used for the proposed solution                                        	| 1h            	| Feb20                  	| B         	|
| 4       	| Create login page                                                   	| Program the kivymd and python files for the GUI and functionality of the login page                                            	| 40min         	| Feb20                  	| C         	|
| 5       	| Create registration page                                            	| Program the kivymd and python files for the GUI and functionality of the registration page                                     	| 40min         	| Feb20                  	| C         	|
| 6       	| Create Main page                                                    	| Program the kivymd and python files for the GUI and functionality of the main page                                             	| 1h            	| Feb20                  	| C         	|
| 7       	| Create page to add note                                             	| Program the kivymd and python files for the GUI and functionality of the note add page                                         	| 3h            	| Feb20                  	| C         	|
| 8       	| Create page to edit note                                            	| Program the kivymd and python files for the GUI and functionality of the note edit page                                        	| 2h            	| Feb20                  	| C         	|
| 9       	| Create system to get color and complementary color                  	| Program the python file for functionality to get the color with color code and able to use complementary color for text color. 	| 2h            	| Feb20                  	| C         	|
| 10      	| Create 80 buttons for substitution of MDDataTable.                  	| Program the kivymd and python files for the GUI and functionality to see the all tasks in main page. I can't use MDDatatable.  	| 5h            	| Feb20                  	| C         	|
| 11      	| Second meeting with cliant                                          	| Let cliant see the prototype and get approval.                                                                                 	| 10m           	| Feb27                  	| A         	|
| 11      	| Be able to use MDDataTable, MDColorPicker, MDDatePicker, MDCheckbox 	| Ask to ChatGPT, and install something strange to be able to use all of the program.                                            	| 5m            	| Feb27                  	| N/A       	|
| 12      	| Delete everything                                                   	| Delete all of the data that I made in Kivymd and Python                                                                        	| 20sec         	| Feb27                  	| N/A       	|
| 13      	| Create login page                                                   	| Program the kivymd and python files for the GUI and functionality of the login page                                            	| 20m           	| Feb27                  	| C         	|
| 14      	| Create registration page                                            	| Program the kivymd and python files for the GUI and functionality of the registration page                                     	| 10m           	| Feb27                  	| C         	|
| 15      	| Create Main page                                                    	| Program the kivymd and python files for the GUI and functionality of the main page                                             	| 2h            	| Feb27                  	| C         	|
| 16      	| Create page to add note                                             	| Program the kivymd and python files for the GUI and functionality of the note add page                                         	| 1h            	| Feb27                  	| C         	|
| 17      	| Create page to edit note                                            	| Program the kivymd and python files for the GUI and functionality of the note edit page                                        	| 20m           	| Feb27                  	| C         	|
| 18      	| Create page to edit note to see all tasks with MDDataTable          	| Program the kivymd and python files for the GUI and functionality of to see all of the data using MDDataTable                  	| 1.5h          	| Mar3                   	| C         	|
| 19      	| Create MDColorPicker                                                	| Program the kivymd and python files for the GUI and functionality to select color easelly.                                     	| 1h            	| Mar3                   	| C         	|
| 20      	| Create MDdatepicker                                                 	| Program the kivymd and python files for the GUI and functionality to select date easelly.                                      	| .5h           	| Mar3                   	| C         	|
| 21      	| Create MDCheckbox                                                   	| Program the kivymd and python files for the GUI and functionality to select category easelly.                                  	| 1h            	| Mar3                   	| C         	|
| 22      	| Apply those to add page and edit page.                              	| let MDColorPicker, MDDatepicker, MDCheckbox use in edit and add page.                                                          	| .5h           	| Mar3                   	| C         	|
| 23      	| Final meeting with cliant                                           	| Let cliant see the prototype and get approval.                                                                                 	| 15m           	| Mar3                   	| A         	|
| 24      	| Write UML diagram, System diagrams, flow diagram, and other diagram 	| Draw all of the diagram and get check from my friends.                                                                         	| 5h            	| Mar3                   	| B         	|
| 25      	| Make the code clean                                                 	| Make kivy for GUI to make more clean and organised.                                                                            	| 30m           	| Mar3                   	| C         	|
| 25      	| Take a video.                                                       	| Take a demonstration video.                                                                                                    	| 15m           	| Mar3                   	| D         	|
## Test plan
| Instruction                                    | Input example/code                           | Description                                                                                            | Expected output                                                                              | Success criteria |
|------------------------------------------------|----------------------------------------------|--------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|------------------|
| Test registration system                       | username, email, password, confirm password  | Save a new user to the database                                                                        | Input is added to database "users", window is switched to main page.                         |                1 |
| Test login system                              | email, password                              | Log in with user that I made in registration system                                                    | user id is saved to class and window swiched to main page.                                   |                1 |
| Test button to go to add-note page             | Click icon button                            | Go to add-note page                                                                                    | Change the page to add-note page.                                                            |                2 |
| Test color picker                              | click and chose color                        | Pick color from MDColorpicker and save it in database.                                                 | Get color code that get from the color picker and save it into database.                     | 2,3,4            |
| Test date picker                               | Click and chose date                         | Pick date from MDDatepicker and save it in database                                                    | Get date that get from date picker(year, month, date) and save it in database.               | 2,3,4            |
| Test multiple choice                           | Click and choose category                    | Pick one of the date from checkbox.  Make sure you can't choose more than two things at the same time. | Get categoryes from check box and save it in database.                                       | 2,3              |
| Test add the note                              | task, category, description, due date, color | Add the new note to database.                                                                          | Input is added to database "note", window is switched to main page.                          |                2 |
| Test there is new note in main screen.         | ------                                       | Make sure there is something writting down in main page after adding some note                         | Main page shows the most resent task.                                                        |                2 |
| Test button to go to edit-note page            | Click one of the tasks.                      | Go to edit-note page                                                                                   | Change the page to edit-note page, and fill the all of page automatically.                   |                3 |
| Test edit the note                             | task, category, description, due date, color | Get all of the data and edit the note. Make sure data is not added, and id is not changed.             | Change the data on the database with the data given.                                         |                3 |
| Test button to logout                          | Click button                                 | Go to login pave                                                                                       | Window switched to login page.                                                               |                1 |
| Test vewing all tasks                          | Click button                                 | See all of the tasks.                                                                                  | Click the button to show the MDDataTable to get all tasks                                    |                6 |
| Test vewing tasks that is in selected category | Click checkbox                               | See task that is in particular category.                                                               | Click the checkbox to show the particular category. Make sure no more than 2 is selected.    |                6 |
| Test deleting tasks.                           | Click the checkbox and press icon.           | Delete selected tasks.                                                                                 | Get ids of selected tasks and delete data from database. Reload again to show deleted tasks. |                5 |

# Criteria C: Coding


# Criteria D: Functionality 
Video link
