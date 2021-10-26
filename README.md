# Install envorment for developers


This project about my experience as SRE and DevOps. Let's install IaC for our project. For more information I added diagrams file. This file has name is web_service.png. File diagram_app.py has code for generate web_service.png. 

## Installation

Installing Vagrant is extremely easy. Head over to the [Vagrant downloads page](https://releases.hashicorp.com/vagrant/2.2.18/vagrant_2.2.18_x86_64.msi) and get the appropriate installer or package for your platform. Install the package using standard procedures for your operating system.

The installer will automatically add vagrant to your system path so that it is available in terminals. If it is not found, please try logging out and logging back in to your system (this is particularly necessary sometimes for Windows).



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
Clone git repo 


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
