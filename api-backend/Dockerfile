FROM ubuntu:16.04
RUN apt-get update  
RUN apt-get install -y python-requests python-flask vim python2.7
RUN mkdir /api-backend
WORKDIR /api-backend
COPY api.py /api-backend
COPY Dockerfile /api-backend
LABEL label auddyc/tp_docker_backend:latest
CMD ["python", "api.py"]
