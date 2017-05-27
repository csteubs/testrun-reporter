# README

Simple API-only application generated with Rails 5

Tutorial found at https://scotch.io/tutorials/build-a-restful-json-api-with-rails-5-part-one

To run application:
- clone
- bundle install
- '$rails s'

Test API manually:
- brew install httpie
- '$ http :3000/todos/ title=Mozart created_by=1'


To run rspec tests:
- cd into the spec/ folder
- '$ bundle exec rspec'