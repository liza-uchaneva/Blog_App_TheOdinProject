# Blog App

A blog with articles and comments, built while working through the official [Rails Getting Started guide](https://guides.rubyonrails.org/getting_started.html) as part of [The Odin Project](https://www.theodinproject.com/).

## Features

- Create, read, update and delete articles
- Comment on articles (nested `resources :comments`)
- Validations: titles are required, and article bodies need at least 10 characters

## Tech stack

Ruby on Rails 7.1 · SQLite · Hotwire · Importmap

## Running locally

Requires Ruby 3.2.2.

```bash
bundle install
bin/rails db:setup
bin/rails server
```

Then open http://localhost:3000.
