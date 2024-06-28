# Django_101

##
step 1.Setting up a virtual environment
<!-- https://docs.djangoproject.com/en/5.0/howto/windows/ -->
py -m venv project-name
 py -m venv django-101

 project-name\Scripts\activate.bat
 django-101\Scripts\activate.bat

 <!-- https://docs.djangoproject.com/en/5.0/howto/windows/#install-django -->
 py -m pip install Django
 <!-- python -m django --version -->

 python.exe -m pip install --upgrade pip

<!-- https://docs.djangoproject.com/en/5.0/howto/windows/#colored-terminal-output -->
 py -m pip install "colorama >= 0.4.6"


<!-- 
 
# My first project in Django:
# https://docs.djangoproject.com/en/5.0/intro/tutorial01/
# django-admin startproject mysite
# https://docs.python.org/3/tutorial/modules.html#tut-packages

# PS C:\.Programming\Django_101> py manage.py runserver
# C:\Python312\python.exe: can't open file 'C:\\.Programming\\Django_101\\manage.py': [Errno 2] No such file or directory
# PS C:\.Programming\Django_101> cd mysite
# PS C:\.Programming\Django_101\mysite> py manage.py runserver



# https://docs.djangoproject.com/en/5.0/intro/tutorial01/#creating-the-polls-app -->