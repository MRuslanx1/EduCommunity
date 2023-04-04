# EduCommunity- College-ERP system 
A college management system built using Django framework. It is designed for interactions between students and teachers. Features include attendance, marks and time table.

## Installation

Python and Django need to be installed

```bash
pip install django
```

## Usage
Firstly we need to meet all the requirements and in order to download all the requirements in our created environment :

```bash
virtualenv myenv
```
```bash
myenv/bin/activate
```

Then:

```bash
pip install -r requirements.txt
```

For running our project in localhost:

Go to the College-ERP folder and run

```bash
python manage.py runserver
```

Then go to the browser and enter the url **http://127.0.0.1:8000/**


## Login

The login page is common for students and teachers.  
The username is their name and password for everyone is 'project123'.  

Example usernames:  
student- 'aykhan'  
teacher- 'khayyammasiyev'  


You can access the django admin page at **http://127.0.0.1:8000/admin** and login with username 'admin' and the above password.
After getting access to admin page it is avaialble to change , edit , put passwords users including teachers and students.

Also a new admin user can be created using

```bash
python manage.py createsuperuser
```
For accesing the deployed website corresponding url is http://178.128.206.74/
## Users

New students and teachers can be added through the admin page. A new user needs to be created for each. 

The admin page is used to modify all tables such as Students, Teachers, Departments, Courses, Classes etc.




## Screenshots

### Teacher Page

![image](https://user-images.githubusercontent.com/109919551/229638979-988d10c1-e769-4de8-8c06-0e2424d607d0.png)

![image](https://user-images.githubusercontent.com/109919551/229638882-8b53b73d-83a8-417a-ba65-16f41e105ac8.png)

![image](https://user-images.githubusercontent.com/109919551/229638904-5aeae374-5451-4754-9d54-0f567375a03f.png)

![image](https://user-images.githubusercontent.com/109919551/229638919-266aaf34-aa94-4041-b20d-d1adde51664d.png)

![image](https://user-images.githubusercontent.com/109919551/229638945-02dae303-1839-45dc-8317-2688f91f7f2a.png)



### Student Page

![image](https://user-images.githubusercontent.com/109919551/229639029-a907d907-01d0-492a-98f2-6539a1424dfb.png)

![image](https://user-images.githubusercontent.com/109919551/229639040-55baeb43-2c94-4190-aaf1-eb2338c363eb.png)

![image](https://user-images.githubusercontent.com/109919551/229639162-64fc8c08-69c4-49cc-ac04-c4da92bf313d.png)

![image](https://user-images.githubusercontent.com/109919551/229639179-10d8ad12-3684-4209-8a6d-e5e0b10ccac8.png)

![image](https://user-images.githubusercontent.com/109919551/229639192-2a8e6e48-b7f6-409e-8a95-2eab620eecce.png)


### Admin Page

![image](https://user-images.githubusercontent.com/109919551/229639234-beb9bcb8-8c3f-4c84-8d45-f243949cca00.png)

![image](https://user-images.githubusercontent.com/109919551/229639269-813ca7f0-0086-4a5b-af94-e97d165e2ac3.png)
