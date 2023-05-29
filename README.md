# SE331
cd capston-project
# If virtualenv not install in your device
python -m pip install virtualenv

# Now Setup virtualenv
virtualenv venv
# Active virtualenv
venv\Scripts\activate

pip install -r requirements.txt

python manage.py runserver
