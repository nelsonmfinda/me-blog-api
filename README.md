# Me Blog API

[![Build Status](https://travis-ci.org/nelsonmfinda/me-blog-api.svg?branch=master)](https://travis-ci.org/nelsonmfinda/me-blog-api)
[![Maintainability](https://api.codeclimate.com/v1/badges/9baf1f0c3f77a85329d9/maintainability)](https://codeclimate.com/github/nelsonmfinda/me-blog-api/maintainability)

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/nelsonmfinda/me-blog-api)

This is an blog Rest API side project using [JSON API](https://jsonapi.org/) specification.

* Ruby version

    2.5.3 (install with [rbenv](https://github.com/sstephenson/rbenv))

* System dependencies

    1. PostgreSQL
    2. Bundler (`gem install bundler`)
    3. RSpec
    4. Factory Bot

* Configuration

```sh
    gem install bundler
```
Install project dependencies
  
```sh
  bundler install
```

* Database creation

```sh
    rails db:create
```

* Database initialization

```sh
    rails db:migrate
```

* How to run the test suite

```sh
    rspec
```

Guidelines
----------

- Pull requests are welcome! If you aren't able to contribute code please open an issue on Github.
- Write specs!
- Develop features on dedicated feature branches, feel free to open a PR while it's still WIP
- Please adhere to the [Thoughtbot ruby styleguide](https://github.com/thoughtbot/guides/tree/master/style#ruby)
- All code and commit messages should be in English
- Commit messages are written in the imperative with a short, descriptive title.