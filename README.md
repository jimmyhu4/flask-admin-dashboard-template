# flask-admin-dashboard-template

This repo uses the following flask UI template: 
https://github.com/app-generator/flask-black-dashboard

# Steps to run the app on Windows using Git Bash

1. Get the code
```
git clone https://github.com/app-generator/flask-black-dashboard.git
cd flask-black-dashboard
```

2. Virtualenv modules installation (Windows based systems)
```
virtualenv --no-site-packages env
source ./env/Scripts/activate
```

3. Install modules - SQLite Database
```
pip3 install -r requirements.txt
```

4. Run Flask app
```
# Set the FLASK_APP environment variable
export FLASK_APP=run.py
# Run app
flask run
```
You should see output like the following after launching the app
<img src="https://user-images.githubusercontent.com/13156232/81893754-44254d00-957c-11ea-8b09-6fb6aba5c89f.png">
You can access the dashboard in browser: http://127.0.0.1:5000/