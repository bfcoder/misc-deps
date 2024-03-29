# clean up:
# rm -rf ~/.bundle/ ~/.gem/; rm -rf $GEM_HOME/bundler/ $GEM_HOME/cache/bundler/; rm -rf .bundle/; rm -rf vendor/cache/; rm -rf Gemfile.lock

source 'https://rubygems.org'
ruby "~>2.7"

gem 'rails', '6.1.5'
gem 'pg'
gem "composite_primary_keys", "~> 13.0" # For que worker

# memcached
gem 'dalli', git: "https://github.com/petergoldstein/dalli", ref: "ca8b286"

# PostGreSQL full text search
gem 'pg_search'

# Pdfs
gem "pdfkit", "~> 0.8.4"
gem "wkhtmltopdf-binary", "~> 0.12.6"

# Javascript
gem 'jquery-rails'
gem "jquery-ui-rails"
gem "jquery-fileupload-rails"

gem 'ejs'

gem 'active_model_serializers', '~> 0.8.0'
gem 'active_storage_base64'
gem 'image_processing', '~> 1.12'
gem 'active_storage_validations'

# UI
gem 'bootstrap-sass', '~> 3.4.1'
gem 'font-awesome-sass'
gem "handles_sortable_columns", git: "https://github.com/dgreene53/handles_sortable_columns.git", ref: "rails-5"
gem "scrollbar-rails"

# Server
#gem "thin", ">= 1.5.0"
gem 'unicorn'

# Maintenance
gem "turnout"

# Users
gem "devise", "~> 4.8.1"
gem 'cancancan'
gem "rolify", "~> 6.0.0"
gem "simple_form", "~> 5.0.2"
gem 'mailchimp-api', require: 'mailchimp'
gem 'devise_masquerade'
gem 'devise_invitable', '~> 2.0.6'
gem "devise-two-factor" # TOTP for devise
gem "rqrcode", "~> 2.1" # Generate QR codes for TOTP

#React
gem 'react-rails'

# JWT
gem "jwt"

# Payments
gem "stripe", "~> 3.12.1"
gem "stripe_event", "~> 2.1.1"

#PDFs
gem "prawn"
gem "prawn_rails"

gem "jquery-slick-rails"

gem "aws-sdk-s3", require: false

# Email
gem "sendgrid-actionmailer"

# Time
gem "chronic"

# Application Settings
gem "figaro", ">= 0.7.0"

gem "rollbar"

gem "will_paginate", '~> 3.1.7'
gem "activerecord-import", ">= 0.25.0"
gem "ancestry"
gem "friendly_id", "~> 5.0.4"
gem 'activerecord-postgresql-adapter'

# 3rd party login and integration
gem 'omniauth', '~> 1.3'
gem 'omniauth-rails_csrf_protection'
gem 'omniauth-stripe-connect', "~> 2.10"
gem 'twilio-ruby'

# Assets
gem 'sass-rails', '>= 3.2'
gem 'uglifier', '>= 2.5.3'
gem 'compass-rails'

# node runtime for execjs
gem "therubyracer"

# calendar
gem 'icalendar'

#vCard
gem 'vpim', :git => "https://github.com/dgreene53/vpim.git"

# edi
gem 'stupidedi'

gem 'health_check'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', require: false

# Job worker
gem "que", "~> 0.14.3"

# Google recaptcha to block automated bot
gem "recaptcha"

group :development, :test do
  gem 'byebug'
  gem "rspec-rails", ">= 3.0.2"
  gem "factory_bot_rails"
  gem 'pry'
  gem 'stripe-ruby-mock', '~> 2.5.3', require: 'stripe_mock'
  gem 'shoulda-matchers'
  gem "dotenv-rails"
end

group :test do
  gem "cucumber-rails", :require => false
  gem "database_cleaner", "~> 1.7"
  gem "rails-controller-testing"
  gem "email_spec", ">= 1.6.0"
  gem "launchy", ">= 2.4.2"
  gem "capybara", ">= 2.4.1"
  gem "webmock"
end

group :development do
  gem "brakeman"
  gem 'bullet'
  gem 'uniform_notifier', '>= 1.10.0'
  gem 'listen', '~> 3.1.0'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

gem 'rails_12factor', group: :staging


group :development do
  gem 'capistrano', require: false
  gem 'capistrano-rails', require: false
  gem 'capistrano-bundler', require: false
  gem 'capistrano-shell',  require: false
  gem 'capistrano-logtail',  require: false
  gem 'capistrano-upload', require: false
  gem 'capistrano-passenger', require: false
  gem 'cap-ec2', git: "https://github.com/dgreene53/cap-ec2", require: false

  # ed25519 ssh key support for deploying
  gem "bcrypt_pbkdf"
  gem "ed25519"
end

gem 'jbuilder', '~> 2.0'
gem 'tinymce-rails', '~> 5.10'
gem 'browser'
gem 'nokogiri', '~> 1.13'
gem 'rubyzip'
