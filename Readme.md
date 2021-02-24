# Deploy flask to heroku
[Deploying a Flask Application to Heroku](https://stackabuse.com/deploying-a-flask-application-to-heroku/)
## creating a virtualenv
```
python -m venv venv/
source venv/bin/activate
```
## Install flask
```
pip install flask
pip install gunicorn
```
## create app.py
```
pip freeze > requirements.txt
```