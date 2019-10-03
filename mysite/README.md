 ## Django Polls Application
 This application is used to create the poll and ask the people which one does they like?

 created by Apipark Withedvorrakit 6110546429
 ## Requirements

 The application requires
 * Python 3.6 r newer
 * Django 2.1.2 or newer
 * Python add-on modules as in [requirements.txt](requirements.txt)

 ## How to Run

 1. clone this reposity
    
    ```
    git clone https://github.com/Parkkung/django-polls.git
    cd django-polls
    cd mysite
    ```

 2. install requirements

    ```    
    pip3 install -r requirements.txt
    ```

 3. Create .env file

    ```
    create a file name .env
    ```

 4. Add data to .env file

    ```
    SECRET_KEY = 

    DEBUG = True

    DB_NAME = db.sqlite3

    TIME_ZONE = Asia/Bangkok
    ```

 5. migrate

    ```
    py manage.py runserver
    ```

 6. run the server

    ```
    py manage.py runserver
    ```

 7. Open the site
    
    ```
    http://127.0.0.1:8000/

    you will see that there doesn't have anything so,
        if you want to change the polls you have to go to http://127.0.0.1:8000/admin/
        or  if you wnat to vote the polls you have to go to http://127.0.0.1:8000/polls/
    ```
