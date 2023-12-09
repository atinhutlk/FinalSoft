FROM python:3.12
WORKDIR app
COPY . .
RUN pip install mysql-connector-python && pip install mysqlclient && pip install flask && pip install flask-cors && pip install geopy
EXPOSE 5001
ENV DB_HOST=192.168.0.17 DB_USERNAME=root DB_PASSWORD=123456 DB_PORT=3306
CMD ["python", "server.py"]
