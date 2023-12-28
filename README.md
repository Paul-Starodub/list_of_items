# list_of_items
Create a simple web application using the Django framework that lists any items from a database.

***
# Installing using GitHub
```
git clone https://github.com/Paul-Starodub/list_of_items
cd list_of_items
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```
---
# .env file
Open file .env.sample and change environment variables to yours. Also rename file extension to .env
***
# Run on local server
- Install PostgreSQL, create DB and User
- Connect DB
- Run:
```
python manage.py migrate
python manage.py runserver
```
***
# Run with Docker
Docker should be already installed
```
docker-compose up --build
```
***
# Create superuser

- docker exec -it airport bash 
- python manage.py createsuperuser
## Getting access
You can use following:
- superuser:
  - Email: admin@gmail.com
  - Password: vovk7777
***

# Stop server
```
docker-compose down
```
