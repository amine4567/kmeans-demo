FROM python:3.10

# Install python requirements
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt

COPY requirements-dev.txt requirements-dev.txt
RUN pip install -r requirements-dev.txt