FROM python:3
ENV PYTHONUNBUFFERED 1
RUN mkdir /espaciocivico_guia
WORKDIR /espaciocivico_guia
COPY requirements.txt /espaciocivico_guia/
RUN pip install --upgrade pip && pip install -r requirements.txt
COPY . /espaciocivico_guia/