PREREQUISITES:
A) To get "python" command working on windows so you  do not have to type the whole python path :
   start -> type "Edit environmental variables..." -> select "Advanced" tab and and
   then click "environmental variables" -> In the "system variables" box "edit" the "PATH" variable -> 
   add 2 "new" PATH= C:\Users\hi\AppData\Local\Programs\Python\Python39\
   and "C:\Users\hi\AppData\Local\Programs\Python\Python39\Scripts\" -> restart.
B) Install 'git' by going to https://git-scm.com/downloads. Choose between Windows/Linux/Mac OS.
   This would get "git" app and you  would be  able to run git from command line.


1) Clone the 'django_simple' from github to your local machine:
   PS C:\Users\hi\Desktop\projects> git clone https://www.github.com/ash322ash422/django_simple
2) In visual Code, open the terminal in the above folder and at the prompt, type "pip install virtualenv" 
If you are installing virtualenv for the first time, then you would see following output:
**************************************************************************************************
PS C:\Users\hi\Desktop\projects\visual_studio_projects\\django_simple> pip install virtualenv
Collecting virtualenv
  Downloading virtualenv-20.25.1-py3-none-any.whl.metadata (4.4 kB)
Collecting distlib<1,>=0.3.7 (from virtualenv)
  Downloading distlib-0.3.8-py2.py3-none-any.whl.metadata (5.1 kB)
Collecting filelock<4,>=3.12.2 (from virtualenv)
  Downloading filelock-3.13.1-py3-none-any.whl.metadata (2.8 kB)
Collecting platformdirs<5,>=3.9.1 (from virtualenv)
  Downloading platformdirs-4.2.0-py3-none-any.whl.metadata (11 kB)
Downloading virtualenv-20.25.1-py3-none-any.whl (3.8 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 3.8/3.8 MB 1.4 MB/s eta 0:00:00
Downloading distlib-0.3.8-py2.py3-none-any.whl (468 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 468.9/468.9 kB 1.4 MB/s eta 0:00:00
Downloading filelock-3.13.1-py3-none-any.whl (11 kB)
Downloading platformdirs-4.2.0-py3-none-any.whl (17 kB)
Installing collected packages: distlib, platformdirs, filelock, virtualenv
Successfully installed distlib-0.3.8 filelock-3.13.1 platformdirs-4.2.0 virtualenv-20.25.1
**************************************************************************************************
3) At the prompt, type "virtualenv env"
output:
***************************************
PS C:\Users\hi\Desktop\projects\visual_studio_projects\django_simple> virtualenv env
created virtual environment CPython3.9.9.final.0-64 in 9702ms
  creator CPython3Windows(dest=C:\Users\hi\Desktop\projects\visual_studio_projects\django_simple\env, clear=False, no_vcs_ignore=False, global=False)       
  seeder FromAppData(download=False, pip=bundle, setuptools=bundle, wheel=bundle, via=copy, app_data_dir=C:\Users\hi\AppData\Local\pypa\virtualenv)
    added seed packages: pip==24.0, setuptools==69.1.0, wheel==0.42.0
  activators BashActivator,BatchActivator,FishActivator,NushellActivator,PowerShellActivator,PythonActivator
***************************************

4) At the prompt, type "pip install "Django==4.2.11". This would install django version 4.2.11
     You may use different version of django 
5) At the prompt, type " django-admin startproject mysite". This creates a django project called 'mysite'. 
6) At the prompt, type "cd mysite". This would take you inside 'mysite' directory.
7) At the prompt, "python manage.py migrate". This would create some predefined admin apps that are very helpful. 
8) At the prompt, type "python manage.py runserver". This would start development server.

