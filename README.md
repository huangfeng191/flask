pip install virtualenv --proxy http://127.0.0.1:8011

virtualenv env

cd venv\Scripts
activate
deactivate.bat

pip install flask flask-sqlalchemy --proxy http://127.0.0.1:8011



<!-- freeze requirement -->
pip3 install gunicorn

pip3 freeze > requirements.txt
