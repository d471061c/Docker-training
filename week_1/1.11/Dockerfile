FROM ubuntu:latest 

WORKDIR /app
COPY . /app

ENV FRONT_URL http://localhost:5000
RUN apt-get update && apt-get install -y curl 

RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt install -y nodejs

RUN npm install
RUN ls /app
EXPOSE 8000

CMD [ "npm", "start" ]