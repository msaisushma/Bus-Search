Requirements

    Python 2.7
    Virtualenv + Pip
    Pyramid
    SQLAlchemy
    SQlite

Steps to run the Server

git clone <repo_url>
cd <repo>
virtualenv .
source bin/activate
pip install Pyramid
pip install sqlalchemy
pip install pysqlite
python server.py
Navigate to http://localhost:8008/ or http://localhost:8008/bus/