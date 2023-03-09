# Project 3 Mr.B's app

![](https://github.com/yutaro741/project/blob/main/photo/work1_image03%20copy.jpg)[^1]

[^1]:https://webcomicgamma.takeshobo.co.jp/special/abyss_artwork/ Made in abyss background art work "narakumon"

# Criteria A: Planning

## Problem definition
Mr.B is a student studying for IB at UWC ISAK Japan. He has a lot of things to do in his life, such as Homework, CAS activity, part time job and his hobby. He is finding it is hard to manage his task for those massive amounts of tasks. So, he is willing to have an application that solves that problem. He requires the Login and Register system, which makes his girlfriend use that as well. He wants not only the parts to add tasks, but also edit the tasks to be able to cope with changing deadlines. He didn’t mention how he wants to see the tasks, but because he likes photography, he strongly wants to change the colors of the tasks, to make it easy to see.


## Proposed Solution
Proposed solution:
Design Statement
To solve my client's problem, I will create an application to manage the tasks for Mr.B. I will be using Python as the primary programming language for the application, KivyMD for the graphical user interface (GUI), and SQLite to manipulate the database in which the tasks logs will be stored. The application will consist of a login page, a registration page, main page, page to edit the task, and page to see all of the task.

System
The application to manage appliance usage will be developed on the programming editor PyCharm version 2022.3.2, run on a 2020 MacBook Pro using the OS macOS Big Sur version 13.2.1. Through PyCharm, the application will be coded using Python, KivyMD for the GUI, and SQLite to manipulate the database.

## Software Justification
Python

I will be using Python as the primary programming language for the following reasons. Firstly, Python is high-level, interpreted, simple syntax language, making it accessible to beginner programmers while still maintaining a high degree of flexibility and practicality for a variety of projects. Additionally, Python is regarded as one of the fastest growing programming languages[^2], which means the resources online that may aid in the developement of this project will be abundant. Secondly, ranked above C, I am most familiar coding in Python, which will make the project run much faster than if I would need to learn a new programming language. Lastly, Python is an object-oriented programming language, which will be useful for this project since OOP frameworks are modular, making it easy to identify problems in the code, the code can be reusable through inheritance, and functions can be flexible and usable across multiple classes due to polymorphism.
[^2]:https://www.bairesdev.com/technologies/why-is-python-top-language/ Why Is Python Programming Considered the Top Language?


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

## UML Diagram
![](https://github.com/yutaro741/project/blob/main/photo/Screen%20Shot%202023-03-09%20at%201.26.56.png)

## ER diagram
![](https://github.com/yutaro741/project/blob/main/photo/9565C84E-E414-4E24-887A-E2F0D472EADF.jpg)

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
## Database configuration
This application will use two databases, users and notes. "users" are used to manage the user id, username, email and password of the user account. "notes" are used to manage the id, user_id, title, due_date, category, description and color of the tasks. I made the project3.db file for manage the data. Also, I made main.py and main.kv.
These are the steps for making the basic basic preparation for writing code in the python file.

Firstly, I will make the python file, main.py and import everything that we need.
```.py
import sqlite3
from kivymd.uix.screen import MDScreen
from kivymd.app import MDApp
import datetime
import hashlib
from kivymd.uix.pickers import MDDatePicker
from kivymd.uix.pickers import MDColorPicker
from typing import Union
from kivymd.uix.datatables import MDDataTable
```
Then, I will make class database_handler() and class SaveMyData.
```.py
def rgba_to_hex(rgba):#Change the color data type [(rational number below 1), (number //), (num //), (1)] (RGBA) to #FFFFFF(#hexadecimal).
    rgb = rgba[:3]
    return '#{:02X}{:02X}{:02X}'.format(*[int(x*255) for x in rgb])

def hex_to_rgba(hex_color, alpha=1.0):#Change the color data type #FFFFFF(#hexadecimal) to [(rational number below 1), (number //), (num //), (1)] (RGBA).
    hex_color = hex_color.lstrip('#')
    rgb = tuple(int(hex_color[i:i + 2], 16)/255 for i in (0, 2, 4))
    return rgb + (alpha,)


class SaveMyData:
    #This class is used to save data used for one single login.
    #Data will be reseted every time restarting the program.
    id = 0
    note = [0, 0, 0, 0, 0, 0, 0, 0]
    editnote = 0
    due = ">="
    order = "ASC"
    date = "2023-12-12"
    categories = "Homework"
    color = "#FFFFFF"
    allcategory="*"

class database_handler():
    def __init__(self):
        self.connection = sqlite3.connect("project3.db")
        #Becasuse we will use only one database, database is automatically setted if you start this class.
        self.cursor = self.connection.cursor()
        #Make cursor

    def run_query(self, query):
        self.cursor.execute(query)
        self.connection.commit()
        #This will run query. This is used

    def close(self):
        self.connection.close()

    def create_tables(self):#This program is used for only first time to make connection and make database.
        query = f"""CREATE TABLE if not exists users(
            id INTEGER PRIMARY KEY,
            email text NOT NULL,
            password text NOT NULL,
            username text NOT NULL
        );"""
        self.run_query(query)

    def create_note(self):#This program is used for only first time to make connection and make database.
        query = f"""CREATE TABLE if NOT exists note(
            id INTEGER PRIMARY KEY,
            user_id INTEGER not NULL,
            category TEXT not NULL,
            due_date TEXT not NULL,
            title TEXT not NULL,
            description TEXT not NULL
            color text DEFAULT '#FFFFFF'
        );"""
        self.run_query(query)

    def register(self, username, email, password):
        query = f"""INSERT INTO users(email, password, username) VALUES('{email}', '{hash(password)}', '{username}');"""
        #Add account into database 'users'
        self.run_query(query)
        self.close()

    def login(self, email, password):
        query = f"""SELECT id from users WHERE email = '{email}' and password = '{hash(password)}'"""
        if self.get_info(query) is None:#Search there is pair of email and hashed password in the users database.
            return None
        else:
            #If there is data, return the user-id.
            id = self.get_info(query)
            return list(id[0])[0]
            #The data is sended with list that contains tuple, so it is making data to one number.

    def add_note(self, user_id, category, due_date, title, description, color):
        query = f"""INSERT INTO note(user_id, category, due_date, title, description, color) VALUES ('{user_id}', '{category}', '{due_date}', '{title}', '{description}', '{color}')"""
        #This program will add the task to database note
        self.run_query(query)
        self.close()

    def edit_note(self, id, category, due_date, title, description, color):
        query = f"""UPDATE note SET category='{category}', due_date='{due_date}', title='{title}', description='{description}', color='{color}' WHERE id = '{id}'"""
        #This program will edit the note that id is given.
        self.run_query(query)
        self.close()

    def get_info(self, query):
        self.cursor.execute(query)
        return self.cursor.fetchall()
        #Return all of imformation that satisify query conditions from database.

make = database_handler()
make.create_tables()
make.create_note()
make.close()
```
I will move create_tables() and create_notes() only once, and delete that program.
Instead of that, I will add the program below to connect kivy file and python file with MDApp.
```.py
class main(MDApp):#code will run with this class.
    def built(self):
        return


test = main()
#Run main program to start showing the program.
test.run()
```
Every time we move the python file, this will let the kivy file move as well.

Finally, we will make kivy file, main.kv and make all of the screen that is needed. 
```.py
ScreenManager:
    LoginScreen:
        name: "LoginScreen"
    RegistrationScreen:
        name: "RegistrationScreen"
    MainScreen:
        name: "MainScreen"
    EditingScreen:
        name: "EditingScreen"
    NoteAddingScreen:
        name: "NoteAddingScreen"
    AllTaskScreen:
        name: "AllTaskScreen"
```
So, I finished the basic setting. we will build up the things from next.

## Login and Registeration Screen
First, I will make the GUI of login screen within kivy file.
```.py
<LoginScreen>:
    FitImage:
        source: "シンプルもやもや背景12-1.png"#background image
    MDCard:
        size_hint:.6, .8
        #Main parts will be smaller than full screen.
        pos_hint: {"center_x":.5, "center_y":.5}
        orientation: "vertical"

        MDLabel:
        #Text to show how to login.
            size_hint:1, .1
            font_style:"H2"
            text:"Login"
            halign:"center"

        MDTextField:
        #Input the data to get email
            id:email_in
            hint_text:"enter email"
            size_hint_x: .8
            pos_hint:{"center_x":.5}
            icon_left: 'email-outline'

        MDTextField:
        #Input the data to get password
            id:password_in
            hint_text:"enter password"
            password: True
            size_hint_x: .8
            pos_hint:{"center_x":.5}
            icon_left: "lock"

        MDBoxLayout:
            MDRaisedButton:
            #Start the program if you press this button.
                id: login
                text:"Login"
                md_bg_color: "#a8dadc"
                on_press:root.try_login()
                #If you press, try_login() in python file will be active.
                size_hint:.5, .1

            MDRaisedButton:#Go to register screen if you don't have account yet.
                text: "Register"
                md_bg_color: "#90ee90"
                on_press:root.parent.current = "RegistrationScreen"
                #Move the page to RegistrationScreen.
                size_hint:.5, .1
```

Next, I will write python code for login screen. I set the name of def to try_login(), so I will use that.
```.py
def hash(message):
    return hashlib.md5(message.encode("utf-8")).hexdigest()
    #This is different way to hash with class, but it is still hash.

class LoginScreen(MDScreen):
    def try_login(self):#This programs runs if you press button.
        email_entered = self.ids.email_in.text#Get the email.
        email_entered = email_entered.replace(" ", "")
        #Because space bar is automatically entered if it's change to english setting, delete all spaces.
        password_enterd = self.ids.password_in.text
        if database_handler().login(email=email_entered, password=password_enterd) is None:
            #find if there is user data in database(user)
            print(f"Incorrect email or password. Please try it again.")
        else:
            print("Login Success!!")
            SaveMyData.id = database_handler().login(email=email_entered, password=password_enterd)
            #Save the user-id to the class, becasue we will use this so many times after log in.
            self.parent.current = "MainScreen"
            #Go to main screen.
```

Login screen is done.
![](https://github.com/yutaro741/project/blob/main/photo/Screen%20Shot%202023-03-09%20at%2017.00.04.png)

However, I can't login to the app because I don't have the account.
So, I will make registratin system.
Fortunetly, program of kivy file and python file is mostly same, so it is not hard to make it.

kivy file:
```.py
<RegistrationScreen>:
    FitImage:
        source: "シンプルもやもや背景12-1.png"#background
    MDCard:
        size_hint:.6, .8
        pos_hint: {"center_x":.5, "center_y":.5}
        orientation: "vertical"

        MDLabel:
            size_hint:1, .1
            font_style:"H2"
            text:"Register"
            halign:"center"

        MDTextField:
            id:uname
            hint_text:"enter username"
            size_hint_x: .8
            pos_hint:{"center_x":.5}
            icon_left: "rename"

        MDTextField:
            id:email_in
            hint_text:"enter email"
            size_hint_x: .8
            pos_hint:{"center_x":.5}
            icon_left: 'email-outline'

        MDTextField:
            id:passwd
            hint_text:"enter password"
            password: True
            size_hint_x: .8
            pos_hint:{"center_x":.5}
            error: False
            icon_left: 'lock'

        MDTextField:
            id:password_check
            hint_text:"enter password_check"
            password: True
            size_hint_x: .8
            pos_hint:{"center_x":.5}
            error:False
            icon_left: 'lock-check'

        MDBoxLayout:
            MDRaisedButton:
                id: login
                text:"Login"
                md_bg_color: "#a8dadc"
                on_press:root.parent.current = "LoginScreen"
                size_hint:.5, .1

            MDRaisedButton:
                text: "Register"
                md_bg_color: "#90ee90"
                on_press:root.try_register()
                size_hint:.5, .1
```

python file:
```.py
class RegistrationScreen(MDScreen):
    def try_register(self):
        email = self.ids.email_in.text
        username = self.ids.uname.text
        password = self.ids.passwd.text
        #get email, username, password from application
        if password == self.ids.password_check.text:
            #Check password entered is same as second password enterd.
            query = f"""SELECT id FROM users WHERE email = '{email}'"""
            if database_handler().get_info(query) == []:
                #Check there is no same account in the users database.
                database_handler().register(username=username, email=email, password=password)
                #Add the user to database
                print("Register success!")
                self.parent.current = "MainScreen"
                #Go to mainscreen
                SaveMyData.id = database_handler().login(email=email, password=password)
                #Save userid because it will use a lot after that.
            else:
                print("This email is already used")
        else:
            print("error. Password and password check is not same")
        database_handler().close()
```
Registration screen is done.
![](https://github.com/yutaro741/project/blob/main/photo/Screen%20Shot%202023-03-09%20at%2019.27.34.png)

## Main Screen
Next, I will make the main screen, the screen that goes after you log in.
kivy file:
```.py
def nowtime():#return time now with yyyymmdd structure.
    dt = datetime.datetime.now()
    if dt.month < 10:
        month = f"0{dt.month}"
    else:
        month = dt.month
    if dt.day < 10:
        day = f"0{dt.day}"
    else:
        day = dt.day
    out = f"{dt.year}{month}{day}"
    return out

<MainScreen>:
    FitImage:
        source: "シンプルもやもや背景12-1.png"
    MDCard:
        id: main_box
        size_hint:.6, .8
        pos_hint: {"center_x":.5, "center_y":.5}
        orientation: "vertical"
        MDLabel:
            text:"Welcome to Task application!"
            font_style:"H2"
        MDBoxLayout:
            orientation:"vertical"
            MDLabel:
                id: ResentTask
                text: ""
                font_style: "H2"
            MDLabel:
                id: DueTask
                text: ""
        MDBoxLayout:
            orientation: "horizontal"
            MDIconButton:
                id:Add_note
                icon: "pencil-plus"
                on_press: root.parent.current = "NoteAddingScreen"
            MDIconButton:
                id:Logout
                icon: "logout"
                on_press: root.parent.current = "LoginScreen"
            MDIconButton:
                id:All_task
                icon: "reorder-horizontal"
                on_press: root.parent.current = "AllTaskScreen"
```


python file:
```.py
class MainScreen(MDScreen):
    def on_pre_enter(self, *args):
        query = f"""SELECT title, due_date from note WHERE due_date >= {nowtime()} and user_id = {SaveMyData.id}"""
        db = database_handler()
        db.cursor.execute(query)
        data = db.cursor.fetchone()
        # Find the "one" task that due date is not passed yet and most resent due date.
        if data is None:
            s = ["---", "---"]
        else:
            s = list(data)
            #Let it list because I hate turple.
        db.close()
        self.ids.ResentTask.text = f"The most resent task is '{s[0]}'"
        self.ids.DueTask.text = f"Deadline:{datetostr(s[1])}"
        #Change the text in kivy to see the task easelly.
```

Main screen is done.
![](https://github.com/yutaro741/project/blob/main/photo/Screen%20Shot%202023-03-09%20at%2019.29.07.png)

## Add and Edit page.
I made the main page, but because there is no task in the database, we have nothing to show.
So, I will gonna make the page to add the task to the database.

I use MDColorpicker and MDDatepicer to pick the date and color. Because of this, my 10 hours are getting to nothing. Also, I was getting able to use checkbox as well. Those 3 are where there is originality in my project.
kivy file:
```.py
<NoteAddingScreen>:
    FitImage:
        source: "シンプルもやもや背景12-1.png"
    MDCard:
        size_hint:.6, .8
        pos_hint: {"center_x":.5, "center_y":.5}
        orientation: "vertical"
        MDBoxLayout:
            test:""
            font_style:"H2"
        MDBoxLayout:
            orientation: "vertical"
            spacing: dp(20)
            MDLabel:
                size_hint:1, .1
                font_style:"H2"
                text:"Add note"
                halign:"center"
            MDTextField:
                id: title
                hint_text:"enter title here"
            MDTextField:
                id: description
                hint_text:"enter description here"

        MDBoxLayout:
            orientation:"vertical"
            spacing: dp(20)
            MDLabel:
                text: 'Categories:'
            MDBoxLayout:
            #This is the checkboks that can choose categories.
            #group:'options' will let the checkbox not to choose more than two things.
            #active:True/false will make the initial setting to be pressed/not.
                MDCheckbox:
                    id: Homework
                    group: 'options'
                    size_hint_y: None
                    active: True
                    on_active: root.on_checkbox_active("Homework")
                MDLabel:
                    size_hint_y: None
                    text:"Homework"
                    size_hint_x: 1.8
                MDCheckbox:
                    id: CAS
                    group: 'options'
                    size_hint_y: None
                    active: False
                    on_active: root.on_checkbox_active("CAS")
                MDLabel:
                    size_hint_y: None
                    text:"CAS"
                MDCheckbox:
                    id: Photo
                    group: 'options'
                    size_hint_y: None
                    active: False
                    on_active: root.on_checkbox_active("Photo")
                MDLabel:
                    size_hint_y: None
                    text:"Photo"
                MDCheckbox:
                    id: Work
                    group: 'options'
                    size_hint_y: None
                    active: False
                    on_active: root.on_checkbox_active("Work")
                MDLabel:
                    size_hint_y: None
                    text:"Work"
                MDCheckbox:
                    id: Others
                    group: 'options'
                    size_hint_y: None
                    active: False
                    on_active: root.on_checkbox_active("Others")
                MDLabel:
                    size_hint_y: None
                    text:"Other"
                    size_hint_x: 1.2
        MDBoxLayout:
            MDRoundFlatButton:
                id: date
                text: "Open date picker"
                pos_hint: {'center_x': .5, 'center_y': .5}
                on_release: root.show_date_picker()
                md_bg_color:"orange"
            MDRoundFlatButton:
                id: toolbar
                text: "Customize color"
                pos_hint: {"center_x": .5, "center_y": .5}
                on_release: root.open_color_picker()
                md_bg_color: "FF0000"
                text_color: "black"


        MDBoxLayout:

            MDIconButton:
                id:Add_note
                icon: "pencil-plus"
                on_press: root.addNote()
            MDIconButton:
                id: BackMain
                icon: "home"
                on_press: root.parent.current = "MainScreen"
```

python file:
```.py
def strtodate(s:str):#Change the date data type yyyy-mm-dd (string type) to yyyymmdd (integer type)
    s = str(s).replace("-", "")
    return s

def datetostr(s):#Change the date data type yyyymmdd (int type) to yyyy-mm-dd (str type)
    s = str(s)
    return f"{s[:4]}-{s[4:6]}-{s[6:]}"
    
class NoteAddingScreen(MDScreen):
    def on_pre_enter(self):
        self.ids.title.text = ""
        self.ids.description.text = ""
        #Set all of the data empty.

    def on_checkbox_active(self, s):
        SaveMyData.categories = s
        #Run if the category is picked, and save it to the SaveMyData class.

    def addNote(self):#run if addnote button is pressed.
        title = self.ids.title.text
        category = SaveMyData.categories
        description = self.ids.description.text
        due_date = strtodate(SaveMyData.date)#Change the text type of the date to string to integer. That will make database easyer to find which date is faster.
        color = SaveMyData.color
        id = SaveMyData.id
        #Get title, category, description, due_date. color, id from kivy and saved data.
        if title != "" and description != "":#Check if there is no empty space
            database_handler().add_note(title=title, category=category, description=description, due_date=due_date, user_id=id, color=color)
            print("Adding note success!")
            #add the note with using the data we got.
            self.parent.current = "MainScreen"
            #Change the screen to mainscreen.
        else:
            print("Some parts is empty")

    def show_date_picker(self):
        date_dialog = MDDatePicker()
        date_dialog.bind(on_save=self.on_save, on_cancel=self.on_cancel)
        date_dialog.open()
        #Open date picker. Original date setting is date of now.

    def on_save(self, instance, value, date_range):
        SaveMyData.date = value
        return
        #Run if the date is picked. Save it into Savemydata class.

    def on_cancel(self, instance, value):
        return

    def open_color_picker(self):
        color_picker = MDColorPicker(size_hint=(0.45, 0.85))
        color_picker.open()
        color_picker.bind(
            on_select_color=self.on_select_color,
            on_release=self.get_selected_color,
        )
        #open color picker, with original color blue.
        #This program runs the very first time you open this page.

    def update_color(self, color: list) -> None:
        self.ids.toolbar.text_color = color
        SaveMyData.color = rgba_to_hex(color)
        #Runs if color is picked
        #save color, and change the cokor in the button.
        #make sure that data saved is im hex every time.

    def get_selected_color(self,instance_color_picker:MDColorPicker,type_color:str,selected_color: Union):
        self.update_color(selected_color[:-1] + [1])
        #If color is selected, run the program to update color.

    def on_select_color(self, instance_gradient_tab, color: list) -> None:
        '''Called when a gradient image is clicked.'''
```

Note adding page is done
![](https://github.com/yutaro741/project/blob/main/photo/Screen%20Shot%202023-03-09%20at%2019.29.26.png)

Date picker is working like this.
![](https://github.com/yutaro741/project/blob/main/photo/Screen%20Shot%202023-03-09%20at%2019.29.40.png)

color picker is working like this.
![](https://github.com/yutaro741/project/blob/main/photo/Screen%20Shot%202023-03-09%20at%2019.29.48.png)

After you write the code for adding the tasks, you will gonna need a page to edit note.
The code and GUI is mostly same with note adding page, so it is easy to make.


kivy file:
```.py
<EditingScreen>:
    FitImage:
        source: "シンプルもやもや背景12-1.png"
    MDCard:
        size_hint:.6, .8
        pos_hint: {"center_x":.5, "center_y":.5}
        orientation: "vertical"
        MDLabel:
            size_hint:1, .1
            font_style:"H2"
            text:"Edit"
            halign:"center"
        MDBoxLayout:
            orientation: "vertical"
            MDTextField:
                id: title
                hint_text:"enter title here"
            MDTextField:
                id: description
                hint_text:"enter description here"

        MDBoxLayout:
            orientation:"vertical"
            MDLabel:
                text: 'Categories:'
                pos_hint: {"center_x":.5, "center_y":.5}
            MDBoxLayout:
                MDCheckbox:
                    id: Homework
                    group: 'options'
                    size_hint_y: None
                    active: False
                    on_active: root.on_checkbox_active("Homework")
                MDLabel:
                    size_hint_y: None
                    text:"Homework"
                    size_hint_x: 1.8

                MDCheckbox:
                    id: CAS
                    group: 'options'
                    size_hint_y: None
                    active: False
                    on_active: root.on_checkbox_active("CAS")
                MDLabel:
                    size_hint_y: None
                    text:"CAS"
                MDCheckbox:
                    id: Photo
                    group: 'options'
                    size_hint_y: None
                    active: False
                    on_active: root.on_checkbox_active("Photo")
                MDLabel:
                    size_hint_y: None
                    text:"Photo"
                MDCheckbox:
                    id: Work
                    group: 'options'
                    size_hint_y: None
                    active: False
                    on_active: root.on_checkbox_active("Work")
                MDLabel:
                    size_hint_y: None
                    text:"Work"
                MDCheckbox:
                    id: Others
                    group: 'options'
                    size_hint_y: None
                    active: False
                    on_active: root.on_checkbox_active("Others")
                MDLabel:
                    size_hint_y: None
                    text:"Others"


        MDBoxLayout:
            MDRoundFlatButton:
                id: date
                text: "Open date picker"
                pos_hint: {'center_x': .5, 'center_y': .5}
                on_release: root.show_date_picker()
                md_bg_color:"orange"
            MDRoundFlatButton:
                id: toolbar
                text: "Customize color"
                pos_hint: {"center_x": .5, "center_y": .5}
                on_release: root.open_color_picker()
                md_bg_color: "white"
                text_color:"black"


        MDBoxLayout:
            MDRaisedButton:
                id: Edit_note
                text: "Edit note"
                on_press: root.edit_note()
            MDIconButton:
                id: BackMain
                icon: "home"
                on_press: root.parent.current = "MainScreen"
```

python file:
```.py
class EditingScreen(MDScreen):
    def on_pre_enter(self):#Runs if the page is opened.
        query = f"""SELECT * from note WHERE id = {SaveMyData.editnote}"""
        #note-ID is saved, so use that to find the data of notes.
        db = database_handler()
        notes = db.get_info(query)
        notes = list(notes[0])#I hate tuple.
        self.ids.title.text = notes[4]
        #Change the text to be automatically filled.
        self.ids[notes[2]].active = True
        #Let category automatically filled as well.
        self.ids.description.text = notes[5]
        #change the text to be automatically filled.

    def edit_note(self):#Run if edit_note button is pressed.
        id = SaveMyData.editnote
        category= SaveMyData.categories
        due_date= strtodate(SaveMyData.date)
        title=self.ids.title.text
        description=self.ids.description.text
        color=SaveMyData.color
        #Get id, category, due-date, title, description and color from kivy and Saved data.
        db = database_handler()
        db.edit_note(id, category, due_date, title, description, color)
        #Run edit_note program
        db.close()
        self.parent.current = "MainScreen"
        #Change the screen to Mainscreen

    def on_checkbox_active(self, s):
        SaveMyData.categories = s
        #If the checkbox pressed, save it to SaveMyData,

    def show_date_picker(self):
        query = f"""SELECT due_date from note WHERE id = {SaveMyData.editnote}"""
        db = database_handler()
        notes = db.get_info(query)
        notes = list(notes[0])[0]
        #Get the date that is originally picked.
        db.close()
        date_dialog = MDDatePicker(year=int(notes[:4]), month=int(notes[4:6]), day=int(notes[6:]))
        #Show the date picker and chose the original setting data.
        date_dialog.bind(on_save=self.on_save, on_cancel=self.on_cancel)
        date_dialog.open()
        #Open the date picker.

    def on_save(self, instance, value, date_range):
        SaveMyData.date = value
        return #Run program if date is picked, and save it to Savemydata class.

    def on_cancel(self, instance, value):
        return

    def open_color_picker(self):
        query = f"""SELECT color from note WHERE id = {SaveMyData.editnote}"""
        db = database_handler()
        notes = db.get_info(query)
        notes = list(notes[0])[0]
        db.close()
        #Get the color that is originally chosed.
        color_picker = MDColorPicker(size_hint=(0.45, 0.85), default_color=hex_to_rgba(notes))
        #Open the color picker and choose the original color.
        color_picker.open()
        color_picker.bind(
            on_select_color=self.on_select_color,
            on_release=self.get_selected_color,
        )
        #Run select_color and release program when color is selected.

    def update_color(self, color: list) -> None:
        self.ids.toolbar.text_color = rgba_to_hex(color)
        SaveMyData.color = rgba_to_hex(color)
        #Run if color is pressed, and save color data to Savemydata class with hex type

    def get_selected_color(self,instance_color_picker: MDColorPicker,type_color: str,selected_color: Union):
        self.update_color(selected_color[:-1] + [1])
        #Change the color to the color that is pressed.

    def on_select_color(self, instance_gradient_tab, color: list) -> None:
        '''Called when a gradient image is clicked.'''
```

Editing screen is done:
![](https://github.com/yutaro741/project/blob/main/photo/Screen%20Shot%202023-03-09%20at%2019.31.34.png)
You can know the note is allready filled.


## All Task Screen
I made the screen to add the note, but there is no button of icon to go to that page.
So, I will make the screen to show all of the tasks that I added, and let it move to the editing screen the task is clicked.
Also, I will let able to show particular category.
kivy file:
```.py
<AllTaskScreen>:
    FitImage:
        source: "シンプルもやもや背景12-1.png"
    MDBoxLayout:
        size_hint:.6, .8
        pos_hint: {"center_x":.5, "center_y":.5}
        orientation: "horizontal"
        md_bg_color: "#ffffff"
        MDIconButton:
            id:Save
            icon: "delete"
            on_press: root.save()
        MDIconButton:
            id:Add_note
            icon: "pencil-plus"
            on_press: root.parent.current = "NoteAddingScreen"
        MDIconButton:
            id: BackMain
            text: ""
            icon: "home"
            on_press: root.parent.current = "MainScreen"

    MDBoxLayout:
        size_hint:.6, .6
        pos_hint: {"center_x":.5, "center_y":.5}
        MDCheckbox:
            id: Everything
            group: 'options'
            size_hint_y: None
            active: False
            on_active: root.on_checkbox_active("*")
        MDLabel:
            size_hint_y: None
            size_hint_x: .4
            text:"All"
            font_size:dp(13)
        MDCheckbox:
            id: Homework
            group: 'options'
            size_hint_y: None
            active: False
            on_active: root.on_checkbox_active("Homework")
        MDLabel:
            size_hint_y: None
            size_hint_x: 1.55
            text:"Homework"
            font_size:dp(13)
        MDCheckbox:
            id: CAS
            group: 'options'
            size_hint_y: None
            active: False
            on_active: root.on_checkbox_active("CAS")
        MDLabel:
            size_hint_y: None
            text:"CAS"
            font_size:dp(13)
            size_hint_x: .6
        MDCheckbox:
            id: Photo
            group: 'options'
            size_hint_y: None
            active: False
            on_active: root.on_checkbox_active("Photo")
        MDLabel:
            size_hint_y: None
            text:"Photo"
            font_size:dp(13)
            size_hint_x: .85
        MDCheckbox:
            id: Work
            group: 'options'
            size_hint_y: None
            active: False
            on_active: root.on_checkbox_active("Work")
        MDLabel:
            size_hint_y: None
            text:"Work"
            font_size:dp(13)
            size_hint_x: .8
        MDCheckbox:
            id: Others
            group: 'options'
            size_hint_y: None
            active: False
            on_active: root.on_checkbox_active("Others")
        MDLabel:
            size_hint_y: None
            text:"Others"
            font_size:dp(15)
            size_hint_x: 1.2
```

python file:
```.py
class EditingScreen(MDScreen):
    def on_pre_enter(self):#Runs if the page is opened.
        query = f"""SELECT * from note WHERE id = {SaveMyData.editnote}"""
        #note-ID is saved, so use that to find the data of notes.
        db = database_handler()
        notes = db.get_info(query)
        notes = list(notes[0])#I hate tuple.
        self.ids.title.text = notes[4]
        #Change the text to be automatically filled.
        self.ids[notes[2]].active = True
        #Let category automatically filled as well.
        self.ids.description.text = notes[5]
        #change the text to be automatically filled.

    def edit_note(self):#Run if edit_note button is pressed.
        id = SaveMyData.editnote
        category= SaveMyData.categories
        due_date= strtodate(SaveMyData.date)
        title=self.ids.title.text
        description=self.ids.description.text
        color=SaveMyData.color
        #Get id, category, due-date, title, description and color from kivy and Saved data.
        db = database_handler()
        db.edit_note(id, category, due_date, title, description, color)
        #Run edit_note program
        db.close()
        self.parent.current = "MainScreen"
        #Change the screen to Mainscreen

    def on_checkbox_active(self, s):
        SaveMyData.categories = s
        #If the checkbox pressed, save it to SaveMyData,

    def show_date_picker(self):
        query = f"""SELECT due_date from note WHERE id = {SaveMyData.editnote}"""
        db = database_handler()
        notes = db.get_info(query)
        notes = list(notes[0])[0]
        #Get the date that is originally picked.
        db.close()
        date_dialog = MDDatePicker(year=int(notes[:4]), month=int(notes[4:6]), day=int(notes[6:]))
        #Show the date picker and chose the original setting data.
        date_dialog.bind(on_save=self.on_save, on_cancel=self.on_cancel)
        date_dialog.open()
        #Open the date picker.

    def on_save(self, instance, value, date_range):
        SaveMyData.date = value
        return #Run program if date is picked, and save it to Savemydata class.

    def on_cancel(self, instance, value):
        return

    def open_color_picker(self):
        query = f"""SELECT color from note WHERE id = {SaveMyData.editnote}"""
        db = database_handler()
        notes = db.get_info(query)
        notes = list(notes[0])[0]
        db.close()
        #Get the color that is originally chosed.
        color_picker = MDColorPicker(size_hint=(0.45, 0.85), default_color=hex_to_rgba(notes))
        #Open the color picker and choose the original color.
        color_picker.open()
        color_picker.bind(
            on_select_color=self.on_select_color,
            on_release=self.get_selected_color,
        )
        #Run select_color and release program when color is selected.

    def update_color(self, color: list) -> None:
        self.ids.toolbar.text_color = rgba_to_hex(color)
        SaveMyData.color = rgba_to_hex(color)
        #Run if color is pressed, and save color data to Savemydata class with hex type

    def get_selected_color(self,instance_color_picker: MDColorPicker,type_color: str,selected_color: Union):
        self.update_color(selected_color[:-1] + [1])
        #Change the color to the color that is pressed.

    def on_select_color(self, instance_gradient_tab, color: list) -> None:
        '''Called when a gradient image is clicked.'''
```
All task screen is done:
![](https://github.com/yutaro741/project/blob/main/photo/Screen%20Shot%202023-03-09%20at%2019.29.14.png)

If you add tasks, it will be like this:
![](https://github.com/yutaro741/project/blob/main/photo/Screen%20Shot%202023-03-09%20at%2019.30.11.png)

Check box is working as well:
![](https://github.com/yutaro741/project/blob/main/photo/Screen%20Shot%202023-03-09%20at%2019.30.23.png)


This is the end of the code explain.


# Criteria D: Functionality 
This is the video!!!!!!!!!!!!
https://youtu.be/z1Vku4CRHws
