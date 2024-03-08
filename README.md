# django_simple
 PREREQUISITES:

A) To get "python" command working on windows so you  do not have to type the whole python path :
   start -> type "Edit environmental variables..." -> select "Advanced" tab and and
   then click "environmental variables" -> In the "system variables" box "edit" the "PATH" variable -> 
   add 2 "new" PATH= C:\Users\hi\AppData\Local\Programs\Python\Python39\
   and "C:\Users\hi\AppData\Local\Programs\Python\Python39\Scripts\" -> restart.
   
   B) Install 'git' by going to https://git-scm.com/downloads. Choose between Windows/Linux/Mac OS.
   This would get "git" app and you  would be  able to run git from command line.


1) Open visual-studio-code and goto required directory and open terminal. Clone the 'django_simple' from github to your local machine:
   PS C:\Users\hi\Desktop\projects\visual_studio_projects> git clone https://www.github.com/ash322ash422/django_simple
2) At the prompt, type "cd django_simple" and then type "pip install virtualenv". 
3) At the prompt, type "virtualenv env"
4) At the prompt, type "pip install "Django==4.2.11". This would install django version 4.2.11
     You may use different version of django 
5) At the prompt, type " django-admin startproject mysite". This creates a django project called 'mysite'. 
6) At the prompt, type "cd mysite". This would take you inside 'mysite' directory.
7) At the prompt, type "python manage.py migrate". This would create some predefined admin apps that are very helpful. 
8) At the prompt, type "python manage.py runserver 127.0.0.1:8000". This would start development server on local machine port number 8000.
9) Go to web browser and type '127.0.0.1:8000'. You will see django welcome page. Congratulations!!!!!

