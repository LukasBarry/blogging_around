# BLOGGING AROUND

[![Code Climate](https://codeclimate.com/github/LukasBarry/blogging_around/badges/gpa.svg)](https://codeclimate.com/github/LukasBarry/blogging_around) [![Test Coverage](https://codeclimate.com/github/LukasBarry/blogging_around/badges/coverage.svg)](https://codeclimate.com/github/LukasBarry/blogging_around/coverage) [![Issue Count](https://codeclimate.com/github/LukasBarry/blogging_around/badges/issue_count.svg)](https://codeclimate.com/github/LukasBarry/blogging_around/issues) [![Build Status](https://travis-ci.org/LukasBarry/blogging_around.svg?branch=master)](https://travis-ci.org/LukasBarry/blogging_around)

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

This is a simple blog app I am using to test several gems along with other techniques to advance my Rails education.

  * Ruby version - 2.3.0

  * Rails version - 5.0.0

  * System dependencies - None

  * Configuration

  * Database creation - PostgreSQL Database


#### USAGE

  * fork repository

  * clone to desktop

  * run commands:

```
bundle install
rake db:create db:migrate db:seed
```

[Entity Relationship Diagram](https://github.com/LukasBarry/blogging_around/blob/master/erd.pdf)

#### COMPONENTS

  * Uses Pundit for authorization and scope

  * Uses Simple Form and Cocoon for nested forms to add tags to the posts

  * Sets the views in slim rather than erb

  * State Machine is set up through AASM

  * Annotate used for models

  * Caching is done with Redis

  * Post Markdown is done through Sidekiq and Redcarpet
  
