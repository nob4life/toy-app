source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.0.3"

gem "sprockets-rails"
gem "importmap-rails"
gem "turbo-rails"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false
gem "stimulus-rails"
gem "puma", "~> 5.0"

gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails', '~> 5.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'
gem 'sdoc'

group :development, :test do 
  gem 'sqlite3'
  gem 'byebug'
  gem 'web-console'
  gem 'spring'
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
end

