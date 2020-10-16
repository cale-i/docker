FROM python:3
ENV PYTHONUNBUFFERD 1
RUN mkdir /code
WORKDIR /code
ADD . /code/
RUN pip install -r django_project/requirements.txt
