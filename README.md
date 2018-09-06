FRIENDS
=============================================

> A blog for friends to share problems

* Live at heroku : [friendzbook.herokuapp.com](https://friendzbook.herokuapp.com/)



### Used Technologies
* Python
* Django
* SQLite3
* PostgreSQL
* HTML5
* CSS3
* JavaScript
* jQuery
* Bootstrap
* Google Drive API


## Installation of the project

## Create virtual environment and goto friends directory
```bash
virtualenv friends
cd .\friends\
```
* copy the project and paste in friends directory

## Activate virtualenv and install reequirements.txt
```bash
.\Scripts\activate
python -m pip install -r .\requirements.txt
```
## goto src directory and make db ready
```bash
cd .\src\
.\manage.py migrate
```
## Run dev server
```bash
.\manage.py runserver 8888
```
* now goto http://127.0.0.1:8888/
