# Blogicum
This project uses basic website development technologies using the Django framework.


## Instalation

### Clone Repository
```sh
git clone https://github.com/Ak5eN/django_sprint4.git
```

### Create virtual environment
```sh
python -m venv venv
```
### Activate venv
#### Windows/Linux
```sh
venv\Scripts\activate.bat
```

#### Mac
```sh
source venv/bin/activate
```

### Install  dependencies 
```sh
pip install -r requirements.txt
```

### Go to the blogicum directory
```sh
cd blogicum
```

### Download the data from the db.json if db.sqlite3 is empty
```sh
python manage.py loaddata db.json
```

### Start the django server

#### Windows
```sh
python manage.py runserver
```
#### Mac/Linux
```sh
python3 manage.py runserver
```






