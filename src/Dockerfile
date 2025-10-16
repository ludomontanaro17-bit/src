FROM python:latest

COPY . /app/

WORKDIR /app

RUN pip3 install -r requirements.txt 

EXPOSE 55555

CMD ["python", "main.py"]