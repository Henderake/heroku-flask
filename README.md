# heroku-flask
A minimal example for deploying Flask application on Heroku

## Steps

### Step 1

```cmd
git clone https://github.com/Henderake/heroku-flask.git
```

### Step 2

```cmd
heroku create [app-name]
```

### Step 3
Commit and push to heroku. To enable flask debug mode, add debug=True when calling app.run() in app_run.py

```cmd
git commit
git push heroku master
```


## References
1. https://stackoverflow.com/questions/17260338/deploying-flask-with-heroku
2. https://devcenter.heroku.com/articles/getting-started-with-python
