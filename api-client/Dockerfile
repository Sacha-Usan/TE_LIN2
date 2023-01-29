FROM python:3-alpine
LABEL hub_url="https://hub.docker.com/r/sachausan/lin2-client"
WORKDIR /app
COPY . /app
EXPOSE 5000
ENTRYPOINT ["python3","socket_client.py"]
