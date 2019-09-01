FROM ruby:2.6.3
RUN bundle config --global frozen 0

RUN apt-get update && apt-get install -y nodejs mariadb-client sqlite3 ffmpeg --no-install-recommends && rm -rf /var/lib/apt/lists/*

ENV APP_PATH /usr/src/app
RUN mkdir -p $APP_PATH
WORKDIR $APP_PATH

COPY Gemfile* $APP_PATH/
RUN bundle install

COPY . $APP_PATH/

EXPOSE 3000

CMD ["bundle", "exec", "puma", "-C", "config/puma.rb"]
CMD ["bundle", "exec", "rails", "server", "-p", "3000", "-b", "0.0.0.0"]