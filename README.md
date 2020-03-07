sudo apt install python3-venv python3-pip

**Create an environment**

Create a project folder and a venv folder within:

mkdir myproject

cd myproject

python3 -m venv venv

**Activate the environment**

Before you work on your project, activate the corresponding environment:

. venv/bin/activate

**Install Flask**

Within the activated environment, use the following command to install Flask:

pip install Flask

export FLASK_APP=file.py/flaskr

Debug Mode
export FLASK_ENV=development

flask run
Running on http://127.0.0.1:5000/
