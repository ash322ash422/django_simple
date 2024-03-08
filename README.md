# django_simple
 PREREQUISITES:

A) To get "python" command working on windows so you  do not have to type the whole python path :
   start -> type "Edit environmental variables..." -> select "Advanced" tab and and
   then click "environmental variables" -> In the "system variables" box "edit" the "PATH" variable -> 
   add 2 "new" PATH= C:\Users\hi\AppData\Local\Programs\Python\Python39\
   and "C:\Users\hi\AppData\Local\Programs\Python\Python39\Scripts\" -> restart.
   
   B) Install 'git' by going to https://git-scm.com/downloads. Choose between Windows/Linux/Mac OS.
   This would get "git" app and you  would be  able to run git from command line.
*****************************************************************************************

You can create by cloning the 'django_simple' from github to the directory on your local machine.
1) Open visual-studio-code and goto the directory of your choice(say Desktop) and open terminal.
2)  Type following command:
  PS C:\Users\hi\Desktop> git clone https://www.github.com/ash322ash422/django_simple
3) At the prompt, type "pip install "Django==4.2.11". This would install django version 4.2.11
4) At the prompt, type "cd django_simple/mysite".
5) At the prompt, type "virtualenv env"
6) At the prompt, type "python manage.py runserver 0.0.0.0:8000". This would start development server on local machine port number 8000.
7) Go to web browser and type '127.0.0.1:8000/notes'. You will see 'notes' welcome page. Congratulations!!!!!
8) Go to web browser and type '127.0.0.1:8000/blog'.  You will see 'blog' welcome page.  Congratulations!!!!!

***************************************************************************

