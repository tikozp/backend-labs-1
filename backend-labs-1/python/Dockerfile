FROM python:3.8

WORKDIR /usr/src/app

COPY app/ .

RUN pip install django

EXPOSE 8001

CMD ["python", "manage.py", "runserver", "0.0.0.0:8001"]
