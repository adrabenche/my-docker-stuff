FROM python:slim-buster

WORKDIR /usr/src/app
COPY . .
RUN pip install --upgrade pip && pip install DateTimeRange colorama emoji openpyxl

CMD [ "python","hello-world.py" ]
