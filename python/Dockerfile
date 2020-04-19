FROM python:3.6
ENV PYTHONUNBUFFERED 1
COPY requirements.txt /var/www
RUN pip install -r requirements.txt
COPY ./ /var/www
WORKDIR /var/www
