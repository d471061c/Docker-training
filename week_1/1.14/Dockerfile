FROM ruby:2.6.0


RUN apt-get update && apt-get install -y libv8-dev
RUN bundle config --global frozen 1

COPY . /app
WORKDIR /app

RUN bundle install

EXPOSE 3000

CMD ["rails", "s"]