To run:

Install Flask

```pip install flask```


Mac:

```
export FLASK_APP=api.py
export FLASK_DEBUG=1
flask run
```

PC

```
set FLASK_APP=api.py
set FLASK_DEBUG=1
flask run
```

App running at 127.0.0.1:5000

Example call

http://127.0.0.1:5000/v1.2/estimates/price?start_longitude=-91.4&start_latitude=45.6&end_longitude=-91.7&end_latitude=45.63

e.g. with curl

http://127.0.0.1:5000/v1.2/estimates/price?start_longitude=-91.4&start_latitude=45.6&end_longitude=-91.7&end_latitude=45.63


Can be deployed to e.g. Heroku or PythonAnywhere. 