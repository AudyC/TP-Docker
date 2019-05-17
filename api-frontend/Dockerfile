FROM ubuntu:16.04
RUN apt-get update  
RUN apt-get install -y python-requests python-flask vim python2.7
RUN mkdir /api-frontend
WORKDIR /api-frontend
COPY api.py /api-frontend
COPY Dockerfile /api-frontend
LABEL label auddyc/tp_docker_frontend:latest
CMD ["python", "api.py"]
