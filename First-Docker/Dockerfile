FROM        ubuntu:latest
WORKDIR     /app
COPY        .. /app
RUN         yum install python36 gcc python3-devel -y
CMD         ["python3", "app.py"]