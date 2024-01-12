# frozen_string_literal: true

source 'https://rubygems.org'

ruby '3.2.2'

gem 'rails', '~> 7.1.2'

gem 'pg', '~> 1.1'

gem 'puma', '>= 5.0'
gem 'rack-cors'

gem 'rswag-api'
gem 'rswag-ui'

gem 'tzinfo-data', platforms: %i[windows jruby]

gem 'devise', '~> 4.9', '>= 4.9.3'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', require: false

group :development, :test do
  gem 'debug', platforms: %i[mri windows]
  gem 'ffaker', '~> 2.2'
  gem 'pry-rails', '~> 0.3.3'
  gem 'rspec-rails', '~> 6.1'

  gem 'rswag-specs', '~> 2.13'
  gem 'rubocop', '~> 1.59', require: false

  gem 'factory_bot_rails', '~> 6.4', '>= 6.4.3'

  group :test do
  gem 'simplecov', '~> 0.22.0', require: false
  gem 'shoulda-matchers', '~> 6.0'
  end
 end

  group :development do
    # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
    # gem "spring"
  end

