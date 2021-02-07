## Getting Started
### Running the Application


First of all create virtual environment and activate it as follows:
```
$ mkdir environments
$ cd environments
$ virtualenv -p python3 instagleo
$ source intagleo/bin/activate
```

Install the requirements
```
Navigate back to the project directory and run the following command
$ pip install -r requirements.txt
```

Db Configure
```
Create mysql database with any name and configure it according to .env.dist file then
run following command in project dir.
$ python manage.py migrate
```

Start the Django app
```
$ python manage.py runserver
```
