# Car-DealerWEB

Open your Terminal/Command Prompt on the project’s root folder.
Install the Requirements: pip install -r requirements.txt.
Create a [PostgreSQL] database named “cardealer_db”.
Configure PostgreSQL Database credentials under settings.py
Then, make database migrations: python manage.py makemigrations
python manage.py migrate
And finally, after a successful migration run the application: python manage.py runserver
At last, open up your favorite web browser
Go to URL “http://127.0.0.1/[ PORT_NUMBER ]/“
