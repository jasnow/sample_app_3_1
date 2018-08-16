source 'https://rubygems.org'

gem 'rails', '3.1.12'

gem 'rack'
gem 'gravatar_image_tag'
gem 'will_paginate', '3.1.0' # LOCKED DOWN
gem 'sass-rails'
gem 'coffee-script'
gem 'uglifier'
gem 'jquery-rails'
gem 'nokogiri'
gem 'overcommit'

group :development do
  gem 'annotate'
  gem 'faker'

  gem 'dawnscanner', require: false
end

group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails', '2.99.0'
  gem 'rubocop-rspec'
  gem 'test-unit'
end

group :test do
  gem 'database_cleaner'
  gem 'webrat'
  gem 'spork'
  gem 'factory_bot_rails'

  # Pretty printed test output
  gem 'turn', require: false
end

group :production do
  gem 'pg'
end
