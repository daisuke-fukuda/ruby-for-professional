FROM ruby:2.5.3
RUN mkdir /ruby-book
WORKDIR /ruby-book
ADD Gemfile /ruby-book/Gemfile
ADD Gemfile.lock /ruby-book/Gemfile.lock
RUN bundle install