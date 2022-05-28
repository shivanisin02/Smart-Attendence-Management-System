
# Smart Attendance Management System

About The Project:

This is a GUI application which is built using Tkinter Module in Python.
It is capable to perform following task -

* It takes Attendance of the employee by face recognition method and automatically generates report of every employee.
* It automatically sends the Attendance report of employees to the manager and sends email to absentees individually.
* It can detect the live faces or fake faces so that no spoofing can be attempted and fake Attendance is not marked.
## Installation

Run the Following commands on anaconda prompt

1) Install a virtual environment by using following command:

```bash
        conda install -c anaconda virtualenv
```
 2) Change working directory to the location of this directory by using the following command: 
```bash
        cd /*location to the repository */
```  
3) Create a Virtual Environment by using the following command:
```bash
        conda create -n "your virtual environment name"
```
4) Activate the virtual environment by using following command:
```bash
        conda activate "your virtual environment name"
```  
5) Install all the Dependencies for running this application by using following command:
```bash
        pip install -r requirements.txt
```
6) Now, to finally run the application, run following command:
```bash
        python main_program.py
```

## Navigating Through The App
### Login page:
#### This is the Admin Login page for authentication. Username and password can be set using localhost/phpmyadmin.

![login page](https://github.com/shivanisin02/Employee-Attendence-Management/blob/master/screenshots/login_page.jpg?raw=true)

### Mangement page
#### This is the main page of application, here employee data can be added, updated, deleted. Employee can take their attendence using face recognition and the report will be generated automatically. It can also detect live image or fake image so that no fake attendence is marked.
![main page](https://github.com/shivanisin02/Employee-Attendence-Management/blob/master/screenshots/main_page.jpg?raw=true)

### Training page
#### For training of the data, 128 dimensional vectors will be extracted and Support vector Machine algorithm will be trained to create a face recognition model. 
![training page](https://github.com/shivanisin02/Employee-Attendence-Management/blob/master/screenshots/training_page.jpg?raw=true)

### Employee Management page
#### This page is for adding, updating, deleting employee's data.
![emp_management page](https://github.com/shivanisin02/Employee-Attendence-Management/blob/master/screenshots/emp_manage_page.jpg?raw=true)

### Attendence Report page
#### Here attendence will be marked and automatic email will be sent to absentees. We can search data by name or date and we can delete the data as well.
![Report page](https://github.com/shivanisin02/Employee-Attendence-Management/blob/master/screenshots/report_page.jpg?raw=true)