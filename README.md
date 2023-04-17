README.md file in the markdown language 

# Development Team Project: Coding Output
----
<br/>

# Project description 
This document backs and clarifies the integration of the required computer software components, bringing the conceptualized secure software design submitted at the end of Unit 3 of the Secure Software Development Module for the University of Essex Online into the production environment developed for the Dutch Police Internet Forensics Department. Cyber forensics departments perform computer-related evidence collection, analysis, preservation, and presentation to investigate network vulnerabilities and criminal, fraud, counterintelligence, or law enforcement activities (NICSS, n.d). As per these requirements, the illustrated solution can add/remove users and, depending on the user group they belong to, upload/download files to be used accordingly by the respective legislative authority.

<br/>

# Requirements 

## Install the following
* Python v3.10.6 (https://www.python.org/downloads/)
* PyCharm IDE (https://www.jetbrains.com/pycharm/)) 
* Django web framework with Tailwind for css (https://www.djangoproject.com/download/)
* Node.js (https://nodejs.org/en)
<br/>

# How to implement the project

* Download zip file and extract files
* Open Pycharm, click projects, new project
* Open location folder, choose project folder, ok
* Create from existing source, open terminal, select + next to local to open a local 2
----
> **`IMPORTANT`, Please read!** This program is run locally and requires 3 different commands to be run in the terminal within the Pycharm IDE 
----

## The 3 commands are:

* venv\Scripts\activate  
* python manage.py tailwind start 
* python manage.py runserver.

Watch the video below for a demonstration, then Copy and paste commands from above.

Video - How to use the 3 commands: https://github.com/Jhines2022/SSD-Coding-Output/blob/4187884251dcf642bf74d13cc5e792110cbd5d3d/Video%20-%20Step%201%20-%20How%20to%20open%20web%20app%20in%20local%20host.mp4 

<br/>

# Troubleshooting

### Ensure all *import* sections in the following .py code files match the examples below. PDF documents can be found in the github repository

* settings.py 

![](https://github.com/Jhines2022/SSD-Coding-Output/blob/3f8955dd6bbfc83614b560a0e9b442783e35ea6a/Troubleshooting%20-%20settings.py.PNG)

* manage.py 

![](https://github.com/Jhines2022/SSD-Coding-Output/blob/3f8955dd6bbfc83614b560a0e9b442783e35ea6a/Troubleshooting%20-%20manage.py.PNG)

* urls.py 

![](https://github.com/Jhines2022/SSD-Coding-Output/blob/3f8955dd6bbfc83614b560a0e9b442783e35ea6a/Troubleshooting%20-%20urls.py.PNG)

### Ensure the *Add Configuration* is set

* Open window, + python
* Give name, choose script folder
* Apply, ok.
* Add configuration is applied

<br/>

# Logins and Passwords 
You can use these credentials to login to the application once the program launches in the development server at http://127.0.0.1:8000/ 

![](https://github.com/Jhines2022/SSD-Coding-Output/blob/76cfd601833a92233a99f0a707756e020cdacbd2/Logins%20and%20Passwords.PNG)

<br/>

# Evidence of execution and output

## Videos of execution

How to open web app in local host: https://github.com/Jhines2022/SSD-Coding-Output/blob/4187884251dcf642bf74d13cc5e792110cbd5d3d/Video%20-%20Step%201%20-%20How%20to%20open%20web%20app%20in%20local%20host.mp4

Admin removing user permissions: https://github.com/Jhines2022/SSD-Coding-Output/blob/4187884251dcf642bf74d13cc5e792110cbd5d3d/Video%20-%20Admin%20removing%20user%20permissions.mp4

DB SQLite3 showing data and logs: https://github.com/Jhines2022/SSD-Coding-Output/blob/4187884251dcf642bf74d13cc5e792110cbd5d3d/Video%20-%20DB%20SQLite3%20showing%20logs%20and%20data.mp4 

User uploading and deleting files: https://github.com/Jhines2022/SSD-Coding-Output/blob/4187884251dcf642bf74d13cc5e792110cbd5d3d/Video%20-%20User%20uploading%20and%20deleting%20files.mp4 

User with CRUD permissions removed: https://github.com/Jhines2022/SSD-Coding-Output/blob/4187884251dcf642bf74d13cc5e792110cbd5d3d/Video%20-%20User%20with%20permissions%20removed.mp4 

Terminal view during user activity: https://github.com/Jhines2022/SSD-Coding-Output/blob/4187884251dcf642bf74d13cc5e792110cbd5d3d/Video%20-%20Terminal%20view%20during%20user%20activity.mp4

----
## Screenshots of .py files/libraries/functions/modules code

### Auth.py

![](https://github.com/Jhines2022/SSD-Coding-Output/blob/3f8955dd6bbfc83614b560a0e9b442783e35ea6a/Auth.py.PNG)

### Decorators.py
Decorators.py provides Django’s authentication consisting of authentication and authorization

![](https://github.com/Jhines2022/SSD-Coding-Output/blob/3f8955dd6bbfc83614b560a0e9b442783e35ea6a/Decorators.py.PNG)

### forms.py

![](https://github.com/Jhines2022/SSD-Coding-Output/blob/3f8955dd6bbfc83614b560a0e9b442783e35ea6a/forms.py.PNG)

### migrations.py

![](https://github.com/Jhines2022/SSD-Coding-Output/blob/3f8955dd6bbfc83614b560a0e9b442783e35ea6a/migrations.py.PNG)

### Settings.py

![](https://github.com/Jhines2022/SSD-Coding-Output/blob/3f8955dd6bbfc83614b560a0e9b442783e35ea6a/settings.py%20for%20auth_password_validation.PNG)


### d.b.SQLite3.py 

![](https://github.com/Jhines2022/SSD-Coding-Output/blob/3f8955dd6bbfc83614b560a0e9b442783e35ea6a/SQLite3%20database%20(couldn't%20encode).PNG)

* Red = Users
* Yellow = Timestamps
* Blue = Passlib pbkdf2_sha256 password hash
* White = Permissions


### Django DB FileSystemStorage

![](https://github.com/Jhines2022/SSD-Coding-Output/blob/3f8955dd6bbfc83614b560a0e9b442783e35ea6a/authenicated%20users%20to%20upload%20file.PNG)



### Auth levels of priority (Part 1 of 2)

![](https://github.com/Jhines2022/SSD-Coding-Output/blob/3f8955dd6bbfc83614b560a0e9b442783e35ea6a/auth%20levels%20of%20priority%20Part%201%20.PNG)

(Part 2 of 2)

![](https://github.com/Jhines2022/SSD-Coding-Output/blob/3f8955dd6bbfc83614b560a0e9b442783e35ea6a/auth%20levels%20of%20priority%20Part%202%20.PNG)

----
# Discussion of the differences between the design and the final code produced
Struggled with db:sqlite3. It logs the data of users, time/date, pbkdf2_sha256 hash but throws an error while loading to UTF-8 which I am struggling to modify. 

----

# Team members

* James Hines
* Marios Maragkos



----

<br/>






