# About the project

**This is an attendence management system. It has two login options, one for manager who will manage the attendence of all the employees and another one is for the employees where they can see their attendance status individually.**

**The manager can add an employee, mark the attendance for a particular date, see the attendance status of each employee and can also update it.**

**The employee can only see his attendance status and can keep track of it.**


# STEPS TO RUN THE APPLICATION

# Clone the repository

    git clone https://github.com/e9kwagh/lesson028.git

# Create a virtual environment

**For Linux and macOS**

    python3.8 -m venv venv
    source venv/bin/activate

**For Windows**
```
 pip install virtualenv
```
   
    ```
     python -m venv venv
    ```
 
    ```
    virtualenv venv
    ```

    ```
    venv/Scripts/activate
    ```
  
    
    

# Go inside the project folder

    cd Everest 

# Install the necessary modules
```
pip install -r requirements.txt

```
    
**If it shows error, run**

```
 pip install django

```
   

# Run the application

    python manage.py runserver

# Open the below url on your browser

     http://127.0.0.1:8000/




# Login as Employee (This option is for different employees to log in to their profile to view their attendance status)



# You can also create a new super user with the following command and login with those credentials.

    python manage.py createsuperuser
