# studdybuddy

# Installation
# Create a Folder where you want to save the project

Create a Virtual Environment and Activate

# Install Virtual Environment First
$ pip install virtualenv Create Virtual Environment

# For Windows
$ python -m venv venv

For Mac
$ python3 -m venv venv Activate Virtual Environment

# For Windows
$ source venv/scripts/activate

# For Mac
$ source venv/bin/activate 3. Clone this project

$ git clone https://github.com/mehedihasan555552/studdybuddy.git

# Then, Enter the project
$ cd Django-Practical-Test

# Install Requirements from 'requirements.txt'
$ pip install -r requirements.txt 5. Add the hosts

Got to settings.py file Then, On allowed hosts, Add [‘’]. ALLOWED_HOSTS = [''] No need to change on Mac.

# Now Run Server
Command for PC:

# $ python manage.py runserver Command for Mac:

$ python3 manage.py runserver 7. Login Credentials

# Create Super User (HOD)
$ python manage.py createsuperuser Then Add Email, Username and Password
