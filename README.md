# ALPHA BLOG
AlphaBlog is an app where users can add, remove, edit and view blogs. You need to be authenticated to perform most of these actions.

This project was created using Ruby on Rails with Bootstrap for frontnend styling and SQlite as backend.

## Features
* Registration of an account
* Create, edit, update and delete blogs
* Add categories for the blogs
* For admin delete account and edit or delete categories

## Tests
* It also contains unit tests and integration tests

## Run it locally
You need to have Ruby 2.7.8 and Rails 6.1.7.3

```
git clone https://github.com/AayushKrShukla/rails-crud.git
cd rails-crud
bundle install
rails db:create
rails db:migrate
```

To run tests run

```
rails test
```

In your browser go to localhost:3000/

