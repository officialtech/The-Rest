# The-Rest
I'm going to create a simple API to allow admin users to view and edit the users and groups in the system.


Create the project directory
<code> mkdir tutorial </code>

<code> cd tutorial </code>

Create virtual environment
<code> python3 -m venv env </code>

Activate
<code> source env/bin/activate </code>

For Windows users
<code> env\Scripts\activate </code>

Now, Install dependencies
<code> pip3 install -r requirements.txt </code>

Set up a new project with a single application
<code> django-admin startproject tutorial . </code>

<code> cd tutorial </code>

This is new we are going to create App inside our Project
<code> django-admin startapp quickstart </code>

Now, Go Back
<code> cd .. </code>

Migrate
<code> python manage.py migrate </code>

Create Super User
<code> python manage.py createsuperuser --email admin@example.com --username admin </code>

Runserver and Start Coding ...


<i>Every Clue is inside below picture.</i>
![image](https://user-images.githubusercontent.com/46815338/112760482-c132a700-9014-11eb-99c2-283e2a48a363.png)
