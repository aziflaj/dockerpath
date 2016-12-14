FROM ruby:2.3.1
MAINTAINER Aldo Ziflaj <aldoziflaj95@gmail.com>

RUN mkdir /novice
WORKDIR /novice

COPY Gemfile Gemfile.lock ./
RUN bundle install

COPY . ./
EXPOSE 3000
CMD ["ruby", "app.rb"]
