source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.0'

gem 'webpacker', '~> 5.x'

# Improve boot time
gem "bootsnap", require: false

gem 'tiny_tds'
gem 'activerecord-sqlserver-adapter', '~> 5.2.0'

gem 'acts_as_list'

# Use SCSS for stylesheets
gem "sassc-rails"

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
#gem 'turbolinks'

# Pdfs
gem "prawn"
gem "prawn_rails"

gem 'devise'

gem 'rmagick', :require => false

gem 'paperclip'

gem 'mms2r', '~> 3.9.2'
gem "mail-fetcher", git: "https://github.com/arrowhead/fetcher.git", require: "fetcher"

gem 'health_check'

gem "will_paginate", "~> 3.3"

gem 'rails_admin', '~> 2.1'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier'

# Google V8 for execjs to use
gem "therubyracer"

group :development do
  gem 'byebug'
  gem 'bullet'
  gem "rubocop"

  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.4'
end

group :development do
  gem 'capistrano', require: false
  gem 'capistrano-rails', require: false
  gem 'capistrano-bundler', require: false
  gem 'capistrano-shell', require: false
  gem 'capistrano-logtail', require: false
  gem 'capistrano-upload', require: false
  gem 'capistrano-passenger', require: false

  # ed25519 ssh key support for deploying
  gem "bcrypt_pbkdf"
  gem "ed25519"
end

group :test do
  gem 'rspec'
  gem 'rspec-rails'
  gem 'sqlite3'
end
