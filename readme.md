Install conda from:

`https://conda.io/miniconda.html`

on Windows run the .exe, on macs and linux run the bash script with:

`sh Miniconda3-latest-Linux-x86_64.sh`

or 

`sh Miniconda3-latest-MacOSX-x86_64.sh`

Follow the onscreen instructions to install conda.

Next we want to create a conda environment with:

`conda create --name opencon2018 python=3.7 matplotlib numpy jupyterlab`

Feel free to call it what you want, we've chosen opencon2018.

Now activate the environment with:

`source activate opencon2018`

and run the lab software with

`jupyter lab`


# Django Web Application 

## Create Conda Environment for Web Application

Install required python tools.
`conda create --name webapp python=3.7`
`pip install django`

Install text editor visual studio code can be found here: https://code.visualstudio.com/

Traverse working directory to a directory for the web application.
Create a new django project with the below command.
mac: `django-admin.py startproject journal-pick`
windows: `python path\to\django-admin.py startproject journalpick`

Create application called search.
`python manage.py startapp search`






