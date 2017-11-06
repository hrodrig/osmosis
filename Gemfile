source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.4'
# Use postgresql as the database for Active Record
gem 'pg', '~> 0.18'
# Use Puma as the app server
gem 'puma', '~> 3.7'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
  # A library for generating fake data such as names, addresses, and phone numbers.
  #  https://github.com/stympy/faker
  gem 'faker'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  # Better error page for Rack apps
  # https://github.com/charliesome/better_errors
  gem 'better_errors'
  # A Javascript test runner built on top of Rails for Jasmine
  # https://github.com/modeset/teaspoon
  gem 'teaspoon-jasmine'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Flexible authentication solution for Rails with Warden.
# https://github.com/plataformatec/devise
gem 'devise'

# Translations for the devise gem
# https://github.com/tigrish/devise-i18n
gem 'devise-i18n'

# Classier solution for file uploads for Rails, Sinatra and other Ruby web frameworks
# https://github.com/carrierwaveuploader/carrierwave
gem 'carrierwave'

# jQuery File Upload integrated for Rails
# https://github.com/tors/jquery-fileupload-rails
gem 'jquery-fileupload-rails'

# Pagination library for Rails, Sinatra, Merb, DataMapper, and more
# https://github.com/mislav/will_paginate
#gem 'will_paginate'

# Integrates the Twitter Bootstrap pagination component with will_paginate
# https://github.com/bootstrap-ruby/will_paginate-bootstrap
gem 'will_paginate-bootstrap'

# Translations for the will_paginate gem
# https://github.com/tigrish/will-paginate-i18n
gem 'will-paginate-i18n'

# A gem to automate using jQuery with Rails
# https://github.com/rails/jquery-rails
gem 'jquery-rails'

# Repository for collecting Locale data for Ruby on Rails
# I18n as well as other interesting, Rails related I18n stuff
# For 5.0.x and 5.1.x
# https://github.com/svenfuchs/rails-i18n
gem 'rails-i18n', '~> 5.0.0'

# This is improved from rails-settings, added caching for all settings
# https://github.com/huacnlee/rails-settings-cached
gem 'rails-settings-cached'

# Organise ActiveRecord model into a tree structure
# https://github.com/stefankroes/ancestry
gem 'ancestry'

# FriendlyId is the “Swiss Army bulldozer” of slugging and permalink
# plugins for ActiveRecord. It allows you to create pretty URL’s and work
# with human-friendly strings as if they were numeric ids for ActiveRecord models.
# https://github.com/norman/friendly_id
gem 'friendly_id', '~> 5.1.0' # Note: You MUST use 5.0.0 or greater for Rails 4.0+

# Simple, scalable UUID generation.
# https://github.com/cassandra-rb/simple_uuid
gem 'simple_uuid'

# Cron jobs in Ruby
# https://github.com/javan/whenever
gem 'whenever', :require => false

# Ckeditor integration gem for rails
# https://github.com/galetahub/ckeditor
gem 'ckeditor'

# mini replacement for RMagick
# https://github.com/minimagick/minimagick
gem 'mini_magick'

# Helper for add social share feature in your Rails app. Twitter, Facebook, Weibo, Douban ...
# https://github.com/huacnlee/social-share-button
gem 'social-share-button'

# filesize is a small ruby class for handling filesizes with both the SI and
# binary prefixes, allowing conversion from any size to any other size.
# https://github.com/dominikh/filesize
gem 'filesize'

# Every Rails page has footnotes that gives information about your application and
# links back to your editor http://blog.plataformatec.com.br/
# https://github.com/josevalim/rails-footnotes
gem 'rails-footnotes', '~> 4.0'

# The missing Ruby method to print out time difference (duration) in year,
# month, week, day, hour, minute, and second.
# https://github.com/tmlee/time_difference
gem 'time_difference'

# Pretty print your Ruby objects with style -- in full color and with proper indentation
# https://github.com/awesome-print/awesome_print
gem 'awesome_print'

# Ruby string class extension. It add some methods to set color, background color
# and text effect on console easier using ANSI escape sequences.
# https://github.com/fazibear/colorize
gem 'colorize'

# A simple Angular.js wrapper for Rails
# https://github.com/hiravgandhi/angularjs-rails/
gem 'angularjs-rails'

# Bower for Rails
# https://github.com/rharriso/bower-rails
gem 'bower-rails'

# Process manager for applications with multiple components
# http://github.com/ddollar/foreman
gem 'foreman'

# Following best practices from http://12factor.net run a
# maintainable, clean, and scalable app on Rails
# https://github.com/heroku/rails_12factor
gem 'rails_12factor'

# Overrides Rails' built in logger to send all logs to stdout
# https://github.com/heroku/rails_stdout_logging
gem 'rails_stdout_logging'

# Sets serve_static_assets to true so Rails will sere your static assets
# https://github.com/heroku/rails_serve_static_assets
gem 'rails_serve_static_assets'

# Simple authorization solution for Rails.
# https://github.com/CanCanCommunity/cancancan
gem 'cancancan'

# twitter bootstrap rails gem that allows easy customization of bootstrap's less
# and javascript components
# https://github.com/scottvrosenthal/twitter-bootswatch-rails
gem 'twitter-bootswatch-rails'
gem 'twitter-bootswatch-rails-helpers'
gem 'twitter-bootswatch-rails-fontawesome'
gem 'therubyracer'

# Easy and customizable generation of forged data.
# http://github.com/sevenwire/forgery
gem 'forgery'

# Retrieve the binding of a method's caller. Can also retrieve bindings even further up the stack.
# http://github.com/banister/binding_of_caller
# Tip: add gem "binding_of_caller" to your Gemfile to enable the REPL and local/instance variable inspection.
gem 'binding_of_caller'

# Use your angular templates with rails' asset pipeline
# https://github.com/pitr/angular-rails-templates
gem "angular-rails-templates"

# A Ruby client library for Redis
# https://github.com/redis/redis-rb
gem 'redis'
