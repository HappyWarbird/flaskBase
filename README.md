# README

Clone Repository or download and extract it.

# Prepare Environment
If you want create a .env File in Repository root folder with:
```
SECRET_KEY=<Add a Secret Key>
SQLALCHEMY_DATABASE_URI=<Database-URL>
MAIL_SERVER=<Mailserver-URL>
MAIL_PORT=<Mailserver-Port>
MAIL_USE_TLS=<True for TLS>
MAIL_USERNAME=<Mailserver-User>
MAIL_PASSWORD=<Mailserver-Password>
ELASTICSEARCH_URL=<Elasticsearch-URL>
```
Init everything :)
```
cd flaskBase
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
flask db upgrade
flask translate update
flask translate compile
```

# Start Application
`flask run`