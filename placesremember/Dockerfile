FROM python:3.8
ENV PYTHONUNBUFFERED 1
RUN mkdir /placesremember
WORKDIR /placesremember
COPY requirements.txt /placesremember/
RUN pip install -r requirements.txt
COPY . /placesremember/