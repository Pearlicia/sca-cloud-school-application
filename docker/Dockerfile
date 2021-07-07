FROM python:3.8
LABEL maintainer = "Felicia Ebikon"

COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt


CMD ["python", "app.py"]