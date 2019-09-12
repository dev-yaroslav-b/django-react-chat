FROM python:3
ENV PYTHONUNBUFFERED 1
RUN mkdir /chat
WORKDIR /chat
COPY requirements.txt /chat/
RUN pip install -r requirements.txt
COPY . /chat/