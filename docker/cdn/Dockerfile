FROM ubuntu:20.04
COPY ./cdn /svr/www/cdn
WORKDIR /svr/www/cdn
RUN apt-get update && apt-get install -y python3 python3-pip
RUN pip3 install matplotlib
RUN pip3 install pandas
RUN pip3 install gunicorn
RUN pip3 install dnspython
RUN pip3 install -r requirements.txt --no-cache-dir


