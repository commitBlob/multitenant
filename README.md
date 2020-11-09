# Multi tenant

## Installation

### Local Setup

1. Add Interpreter, in PyCharm bottom right, Add interpreter...

2. Select virtual environment tab and new. This will create venv folder in the current directory.

3. Activate virtual env.

    ```
    $ source venv/bin/activate
    ```

    If this works there should be (venv) prefix in the terminal

4. Install requirements.
    
    ```
    $ pip install -r requirements.txt
    ```

5. Migrations

    5.a Create migrations
    
    ```
    $ python manage.py makemigrations
   ```
   
   5.b Apply Migrations
   ```
   $ python manage.py migrate
   
6. Optional - Create superuser

    ```
    $ python manage.py createsuperuser
    ```
   
### Other commands

Run server if we want to run app on the different port add []

```
$ python manage.py runserver [localhost:8888]
```

Install dependency

```
$ pip install {dependency}
```

Add dependency to the requirements.txt
```
$ pip freeze -r requirements.txt
```