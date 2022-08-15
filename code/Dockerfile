FROM python:3.9

WORKDIR /usr/src/app
RUN pip install flask
COPY . .

CMD [ "python", "-u", "/usr/src/app/app.py" ]
