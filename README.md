<h1 align='center'> VerifyMe </h1>

VerifyMe is a user authentication platform designed to simplify the sign-up and login process. Our platform allows users to create an account with just their email, or they can continue with a Google or Apple account. With VerifyMe, you can rest assured that your information is secure and protected. Our advanced security features provide an extra layer of protection for your personal data. Whether you're signing up for a new account or logging into an existing one, VerifyMe makes the process easy, fast, and secure. Say goodbye to the hassle of multiple usernames and passwords and say hello to a simplified and secure authentication experience with VerifyMe.

<hr/>

<h1 align='center'> My Blog Post About VerifyMe </h1>


<p align="left">
 
<a href="https://gauravjoshi.hashnode.dev/building-a-system-for-user-registration-and-login-using-python-part-1" title="Building a System for User Registration and Login using Python (Part 1 )"><img src="https://cdn.hashnode.com/res/hashnode/image/upload/v1676974049877/b42b5a77-b31a-4caf-afb5-bae6cad2bc3a.png?w=1600&h=840&fit=crop&crop=entropy&auto=compress,format&format=webp" alt="Building a System for User Registration and Login using Python (Part 1)"  width="250px" align="left" /></a>
<a href="https://gauravjoshi.hashnode.dev/building-a-system-for-user-registration-and-login-using-python-part-1" title="Building a System for User Registration and Login using Python (Part 1)"><strong>Building a System for User Registration and Login using Python (Part 1 )</strong></a>
<div><strong>Feb 22, 2023 </strong></div>
<br/>This article is a tutorial on building a backend for user sign-up, login, and authentication using Python
</p> <br/> 

<hr/>
<h1 align='center'> Getting Started </h1>

## Prerequisites
Make sure you have the following installed on your system:

<ul>
 <li><a href="https://www.python.org/downloads/"> Python </a> </li>
 <li> virtualenv </li>
</ul>

You can install virtualenv using the following command:

```pip install virtualenv```

## Installation

1. Clone this repository:

 &nbsp;  &nbsp;  &nbsp;    ```git clone https://github.com/Gaurav-jo1/VerifyMe_Backend.git```

2. Navigate to the project directory: &nbsp; 

 &nbsp;  &nbsp;  &nbsp;    ```cd VerifyMe_Backend```

3. Create a virtual environment for your project (optional but recommended):

 &nbsp;  &nbsp;  &nbsp;    ```virtualenv venv```

4. Activate the virtual enviroment:

 &nbsp;  &nbsp;  &nbsp;   For Windows: &nbsp;  &nbsp;   ``` ./venv/Scripts/activate```

 &nbsp;  &nbsp;  &nbsp;   For Linux: &nbsp;  &nbsp; &nbsp;   &nbsp;  ```source ./venv/bin/activate```


5. Install the required packages listed in the requirements.txt file:

 &nbsp;  &nbsp;  &nbsp;  ```pip install -r requirements.txt```
 
6. Set up the app by running the following commands:

 &nbsp;  &nbsp;  &nbsp;  ```python manage.py makemigrations```
 
 &nbsp;  &nbsp;  &nbsp;  ```python manage.py migrate```
 
7. Create a superuser (optional) by running:

 &nbsp;  &nbsp;  &nbsp;  ```python manage.py createsuperuser```
 
## Running the App
To run the app, simply run the following command: &nbsp; ```python manage.py runserver```

## License
This project is licensed under the <a href="https://opensource.org/license/mit/">MIT License.</a>
