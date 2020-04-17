FROM ubuntu:latest 

WORKDIR /app
COPY . /app

ENV API_URL http://localhost:8000
RUN apt-get update && apt-get install -y curl 

RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt install -y nodejs

RUN npm install
RUN npm run build
RUN npm install -g serve

EXPOSE 5000

CMD [ "serve", "-s", "-l", "5000", "dist" ]