# flaskproject
Created the simple blog using python-flask, with curd functionality (SQLLITE).


Installing
Install and update using pip:

$ pip install -U Flask
A Simple Example
# save this as app.py
from flask import Flask

app = Flask(__name__)

@app.route("/")
def hello():
    return "Hello, World!"
$ flask run
  * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
