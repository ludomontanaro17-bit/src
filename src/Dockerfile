FROM python:latest

COPY . /app/

WORKDIR /app

RUN pip install -r requirements.txt 

EXPOSE 55555

CMD ["python", "main.py"]