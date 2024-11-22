FROM ubuntu:latest

LABEL maintainer="ogunyemitaiwojohn@gmail.com"

LABEL version="1.0.0"

RUN apt-get update

RUN apt-get upgrade -y

RUN apt-get install python -y

EXPOSE 80

CMD [ "python", "index.py" ]

