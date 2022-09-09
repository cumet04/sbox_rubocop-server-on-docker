FROM ruby:3.1.2

RUN mkdir /app
WORKDIR /app

COPY Gemfile Gemfile.lock .
RUN bundle install
