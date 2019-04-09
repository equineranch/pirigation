![image](https://github.com/equineranch/PIrigation/blob/master/pirigation/static/images/logo.png?raw=true)

To Install:
1. First make sure you are using pipenv.  Use "pipenv install" to insstall dependencies.
2. Some dependencies need to be installed locally outside of pipenv.  Make sure you have "RPi.GPIO installed" using "sudo apt-get install RPi.GPIO".
3. PIrigation uses SQLite.  After installing dependencies, navigate to root of flask project, then open a Python REPL. 
    Type in:  "from pirigation import db", then "db create_all()"
    This creates the database and database tables.
4. To run with flask, navigate to root of flask directory where "start.py" file is located.  Run ython3.7 start.py
