# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.0.0"
gem 'activesupport'
gem 'acts-as-taggable-on', '~> 6.0'
gem 'awesome_print', require: 'ap'
gem 'aws-sdk-s3', require: false
gem 'better_errors'
gem 'binding_of_caller'
gem 'bootsnap', '>= 1.1.0', require: false
gem 'bootstrap', '4.3.1'
gem 'cancancan'
gem 'carrierwave'
gem 'coderay'
gem 'coffee-rails', '~> 4.2'
gem 'devise', '4.7.1'
gem 'devise-i18n'
gem 'devise-i18n-views'
gem 'fog-aws'
gem 'font-awesome-sass'
gem 'foreman'
gem 'google-analytics-rails'
gem 'jbuilder', '~> 2.5'
gem 'jquery-rails'
gem 'kaminari'
gem 'mini_magick'
gem 'puma', '~> 4.3'
gem 'rails', '~> 6.0.0'
gem 'rails_admin'
gem 'redcarpet', '~> 3.5.1'
gem 'rename'
gem 'sass-rails', '~> 5.0'
gem 'sprockets', '3.7.2'
gem 'turbolinks', '~> 5'
gem 'uglifier', '>= 1.3.0'
gem 'webpacker'

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'factory_bot_rails', '~> 4.11'
  gem 'pry-byebug'
  gem 'rails-erd'
  gem 'sqlite3'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'meta_request'
  gem 'rubocop'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0'
end

group :production do
  gem 'pg', '0.20.0'
  # gem 'unicorn', '5.4.1'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'chromedriver-helper'
  gem 'rspec-rails', '~> 3.7'
  gem 'selenium-webdriver'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
