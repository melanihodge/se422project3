Run this before running the app.

``` export DB_USER=se422project3 && export DB_PASSWORD=se422pass && export DB_NAME=photogallery && export DB_CONNECTION_NAME=se-422-452919:us-central1:se422project3 ```

Also run this if the app is still not running.

``` pipx install virtualenv && pipx run virtualenv venv && source venv/bin/activate && pip install -r requirements.txt ```
