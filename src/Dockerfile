FROM python:3.12-bullseye
RUN pip install Flask-login
RUN pip install Flask-SQLAlchemy
COPY . /opt/app
WORKDIR /opt/app
CMD ["python", "./app.py"]