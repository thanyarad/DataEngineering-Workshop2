 FROM python:3.10.2-alpine3.15
 # Create directories  
 RUN mkdir -p /root/workspace/src
 COPY ./  /root/workspace/site
 # Switch to project directory
 WORKDIR /root/workspace/site
 # Install required packages
 RUN pip install --upgrade pip
 RUN pip install Django
