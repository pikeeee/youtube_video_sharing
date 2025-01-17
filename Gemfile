# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.2'

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem 'rails', '~> 7.0.8', '>= 7.0.8.4'

# Use pg as the database for Active Record
gem 'pg', '~> 1.5', '>= 1.5.6'

# The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem 'sprockets-rails'

# Use the Puma web server [https://github.com/puma/puma]
gem 'puma', '~> 5.0'

# Use JavaScript with ESM import maps [https://github.com/rails/importmap-rails]
gem 'importmap-rails'

# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem 'turbo-rails'

# Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem 'stimulus-rails'

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem 'jbuilder'

# Use Redis adapter to run Action Cable in production
gem 'redis', '~> 4.0'

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', require: false

# To load environment variables from .env into ENV in development
gem 'dotenv-rails', '~> 3.1', '>= 3.1.2'

# For internationalize locale
gem 'rails-i18n', '~> 7.0', '>= 7.0.9'

# For pagination
gem 'pagy', '~> 5.8', '>= 5.8.1'

# Use Sass to process CSS
# gem "sassc-rails"

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem 'debug', platforms: %i[mri mingw x64_mingw]

  # Generate models based on factory definitions
  gem 'factory_bot_rails', '~> 6.4', '>= 6.4.3'
  # Ensure the database is in a clean state on every test
  gem 'database_cleaner-active_record', '~> 2.1'
  # Generate fake data for use in tests.
  gem 'faker', '~> 3.3', '>= 3.3.1'
  # RSpec behavioral testing framework for Rails
  gem 'rspec-rails', '~> 6.1.2'
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem 'annotate', '~> 3.2'
  gem 'rubocop', '~> 1.64', '>= 1.64.1'
  gem 'rubocop-performance', '~> 1.21'
  gem 'rubocop-rails', '~> 2.25'
  gem 'web-console'
  # debug
  gem 'pry', '~> 0.14.2'

  # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem "rack-mini-profiler"

  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem 'capybara'
  gem 'selenium-webdriver'
end
