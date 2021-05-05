FROM python:3.9

RUN pip install djangorestframework psycopg2 django-cors-headers coverage
 
WORKDIR /api 

COPY . .
 
EXPOSE 8000  

CMD python3 manage.py migrate && python3 manage.py runserver 0.0.0.0:8000  