# todo-web-app
This is a todo web application. Its purpose is to provide a tool for listing out activities to be carried out, 
increasing productivity and managing time.

##Technologies used  
* Django framework
* HTML 5
* CSS

## App Features  
* Authentication (login and signup)
* Admin panel
* Display a list of todos
* Add a todo
* Delete a todo
* Update a todo

## Getting started  
The following guide will help you get up and running with this project on your local
environment.  

### Prerequisites  
Make sure you have these installed  
* Python
* Django
* Git

### Clone the repository
Clone the repo to your local machine using the following command.  

```git clone <repository_url>```

Replace <repository_url> with the URL of your repository.  

###  Set Up a Virtual Environment
Navigate to the project directory and create a virtual environment using the code below  

```cd projectname```
```python -m venv venv```

Activate the virtual environment  
On windows, use  
```venv\Scripts\activate```

Om macOS, use  
```source venv/bin/activate```

### Install Dependencies  
Install project dependencies using pip as shown below.  

```pip install -r requirements.txt```

###  Initialize the Database  
Apply migrations to set up the database.    

```python manage.py migrate```

### Create superuser  
Create a superuser to access the Django admin panel  

```python manage.py createsuperuser```

Follow the instructions to the end of creating a superuser account.  

### Run the development server  
Start the Django development server as shown.  

```python manage.py runserver```  

Your app will be accessible at http://localhost:8000/  
Your all setup and done, Huray !!  

./ CICD, Deployment (Coming soon)


