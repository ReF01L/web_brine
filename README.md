# Brine Tool
WEB version for the BrineTool [Rhonda Software]

## For start:
python -m venv venv
### Windows
venv/Scripts/activate
### Linux
source venv/bin/activate

python -m pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
\Create admin user\
python manage.py runserver
