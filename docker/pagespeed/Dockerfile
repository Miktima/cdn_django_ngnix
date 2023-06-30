FROM ubuntu:20.04
COPY ./pagespeed /svr/www/pagespeed
WORKDIR /svr/www/pagespeed
RUN apt-get update && apt-get install -y python3 python3-pip
RUN pip3 install matplotlib
RUN pip3 install pandas
RUN pip3 install gunicorn
RUN pip3 install -r requirements.txt --no-cache-dir


