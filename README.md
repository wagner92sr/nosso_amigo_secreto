# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version 2.5

* System dependencies

* Configuration

* Database creation
   docker-compose run --rm website bundle exec rake db:create

* Database initialization
   docker-compose run --rm website bundle exec rake db:migrate

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions
  Execute o comando docker-compose build para que a aplicação execute o bundle install
  Execute o comando docker-compose up para iniciar a aplicação
* ...
