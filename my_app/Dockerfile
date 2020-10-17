FROM python:3.7-alpine
COPY test/ /my_app/test/
COPY requirements.txt /my_app/
RUN pip install -r /my_app/requirements.txt
COPY src/ /my_app/src/
CMD python /my_app/src/app.py --env dev 0.0.0.0 8080
