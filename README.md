### Setup
`$ brew install python`
`$ python3 -m pip install virtualenv`
`$ virtualenv venv -p python3`
`$ source venv/bin/activate`
`$ pip install django`

### Running server locally
`$ cd CopWatchBE`
`$ source venv/bin/activate` so that your CLI has `(venv)` before your file location
`$ python manage.py runserver`

Visit `localhost:8000`