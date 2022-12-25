# FastAPI-Books

An example of simple FastAPI app with Uvicorn (GET and POST data), SQLAlchemy to CRUD operations and Alembic to manage migrations. Deployed in Docker/Docker-Compose.

To start:

    python -m venv venv
    venv\Scripts\activate
    pip install -r requirements.txt

Then run containers:

    docker-compose build
    docker-compose up
    
Check for "Hello World!":

    http://127.0.0.1:8000/

Check docs and endpoints:

    http://127.0.0.1:8000/docs

Check database with pgAdmin:

    http://127.0.0.1:5050
