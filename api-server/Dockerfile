FROM python:3-alpine
LABEL hub_url="https://hub.docker.com/r/sachausan/lin2-server"
WORKDIR /app
COPY . /app
EXPOSE 5000
ENTRYPOINT ["python3","socket_server.py"]
