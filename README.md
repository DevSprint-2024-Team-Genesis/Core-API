# Hi there! 👋

## How to gear up the server.

1. Install python 3.10.12(other versions(>3) should work as well. 3.10.12 is the current version at the time of developing this.) and pip on your system.
2. Clone the repository into a directory. (Or fork your own copy and clone it, if you want to contribute.)
3. 'cd' into the directory where 'manage.py' is in.
4. Create a virtual environment in this directory and activate it.
5. Install the requirements using the command: `pip install -r requirements.txt`
6. Run the server using the command: `python manage.py runserver`

## Admin access

1. Open the server in your browser, using the url in your terminal(where the server is running). Or directly go to the url
   'http://127.0.0.1:8000/'.
2. Add 'admin/' at the end of the url. Or visit 'http://127.0.0.1:8000/admin/'.

### Admin credentials

#### email: 'tef@gmail.com'

#### password: 'tef'


#### Disclaimer: Make sure to migrate the database before running the server. Use the following commands.

`python manage.py makemigrations`

`python manage.py migrate`

## API documentaion

If you're running the server locally, in localhost port 8000, go to this [api documentation](http://127.0.0.1:8000/swagger/) for a detailed documentation of the api endpoints. (Make sure the server is running, as this api documentation is not live, yet.)
