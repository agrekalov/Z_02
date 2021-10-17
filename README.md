# Install to Base

This article about my experience as and SRE and DevOps. Let's install Python for start application "flask-sqlite3-todo-crud". For more information I added diagrams file. This fail has name is

## Installation
Use settings.json in .vscode directory and change python path on your PC
```
"python.pythonPath": "C:\\Users\\username\\AppData\\Local\\Programs\\Python\\Python310\\python.exe"
``` 
 
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install flask and sqlalchemy.

```bash
py -m pip install flask 
py -m pip install sqlalchemy
py -m pip install flask-sqlalchemy
```

## Usage

```python
$ py app.py

# returns message on console 
Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)    

# Open web browser 
http://127.0.0.1:5000/

# returns web page
Voulya, You can use mini web-server and database!
```

## License
[MIT](https://choosealicense.com/licenses/mit/)
