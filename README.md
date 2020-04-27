# flask-opencv-app
OpenCV flask app, upload your photo and find your face in that >> live Website
## How to run
### windows
- Download the repo install 
- run command "pip install -r requirements.txt"
- run app.py
### Linux
- Clone the Repo using "git clone https://github.com/dev-Roshan-lab/flask-opencv-app.git"
- run command "pip install -r requirements.txt"
- run app.py
## module used 

>- Flask
>- OpenCV-python
>- Numpy
>- run command 'pip install -r requirements.txt' to install all the required modules

### About Flask 
Flask is a micro web framework written in Python. It is classified as a microframework because it does not require particular
tools or libraries. It has no database abstraction layer, form validation, or any other components where pre-existing third-party
libraries provide common functions
### Why this ??
This is a basic app which detects your face can be used to create any Computer vision projects 
from edge detection to cancer detction with KNN in OpenCV

### Wanna Host on your website ??
- #### Prerequsite
    - Heroku Account
    - git installed on your machine

> #### Steps
 Create a Virtual Env
- run command "_pip install virtualenv_" to install Virtual env because we dont want to waste Our Data On installing the requirements on server
- run command "_python venv env_" to create virtual environment named "env"

>- run commads to activate it :
>  - 1."_cd env_"
>- 2."_cd Scripts_"
>- 3."_.\activate_"

>- run commands to install the necessary packages :
>- "_pip install numpy_"
>- "_pip install opencv-python_"
>- "_pip install flask_"
>- "_pip install gunicorn_"

>- Creating a Procfile
>- Procfile should not contain any extension and it should be named as "_Procfile_"
>- Open the Procfile and write "_web: gunicorn app:app --preload_"

>- Next to create a .gitignore file
>- save a file named "_.gitignore_" and write "_env_"

>- Time has come to Deploy
>- open Shell 
>- Type "pip freeze > requirements.txt"
>- Type "_git init_"
>- Type "_git add ._"
>- Type "_git commit -m "commit"_"
>- Type "_heroku create_" (creates a app with default random names) or Type "heroku create _'app name'_ " for custom app name
>- Type "_git push heroku master_"

### Done !!!


#### Made with Python 3.8.1




 
                             

