# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.5'

group :test, :development do
  gem 'factory_bot_rails'
  gem 'pry-byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :test do
  gem 'ephemeral_response'
  gem 'guard-rspec', require: false
  gem 'rspec-rails', '~> 4.0.0.beta'
  gem 'rspec-retry'
  gem 'shoulda', require: false
  gem 'shoulda-callback-matchers'
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'database_cleaner' # Database Cleaner is a set of strategies for cleaning your database in Ruby.
  gem 'vcr' # Record your test suite's HTTP interactions and replay them during future test
  gem 'webmock' # Library for stubbing and setting expectations on HTTP requests in Ruby.
  gem 'rack_session_access' # In order to set a session variable in a capybara test
end

group :development do
  gem 'better_errors' # Better Errors replaces the standard Rails error page with a much better and more useful error page.
  gem 'binding_of_caller'
  gem 'bullet' # check for N+1 sql req
  gem 'gem_updater' # Update gems in your Gemfile and fetch their changelogs github.com/MaximeD/gem_updater
  gem 'letter_opener_web' # Open mail in browser
  gem 'lol_dba' # Displays a list of columns that probably should be indexed
  gem 'rails-erd' # Generate model diagrams
  gem 'railroady' # Generate model diagrams alternative
  gem 'web-console'
  gem 'listen'
  gem 'spring' # Rails application preloader
  gem 'spring-watcher-listen'
  gem 'spring-commands-rspec'
  gem 'spring-commands-cucumber'
  gem 'spring-commands-sidekiq'
  gem 'benchmark-ips' # Generate benchmark
end
gem 'rubocop' # Ruby static code analyzer
gem 'rubocop-rails_config'
gem 'rubocop-performance'
group :production do
  gem 'wkhtmltopdf-heroku', '2.12.5.0' # PDF
end

gem 'rake'
gem 'rails', '~> 6.0.2'
gem 'webpacker'
gem 'sprockets-rails'
gem 'sprockets'
gem 'puma'
gem 'bootsnap', require: false
gem 'sassc-rails'

# Turbolinks
gem 'turbolinks'

# Caching
gem 'redis'
gem 'sidekiq'
gem 'sidekiq-status'

# Blacklist, DDOS attack
gem 'rack'
gem 'rack-attack'

# Core Ruby on Rails
gem 'rest-client'
gem 'rack-cors', require: 'rack/cors'
gem 'pg'
gem 'figaro'
gem 'rack-host-redirect'

# HAML
gem 'hamlit'

# Ruby wrapper for UglifyJS JavaScript compressor
gem 'uglifier'

# CoffeeScript adapter for the Rails asset pipeline
gem 'coffee-rails'

# JQuery
gem 'jquery-rails'
gem 'jquery-ui-rails'

# Bootstrap
gem 'bootstrap', '~> 4.4.1'
gem 'bootstrap_form'
gem 'bootstrap-datepicker-rails'

# Simple forms
gem 'simple_form'

# Valid email
gem 'valid_email'

# Blog (see application.rb)
gem 'rack-reverse-proxy', require: 'rack/reverse_proxy'

# Amazon S3
gem 'aws-sdk-s3'

# Upload on Amazon S3
gem 'paperclip'
gem 'delayed_paperclip'
gem 'paperclip-compression'

# RMagick is an interface between the Ruby programming language and the ImageMagick image processing library.
gem 'rmagick'

# Use Active Storage variant
gem 'image_processing'

# Payment
gem 'stripe'
gem 'stripe_event'

# Logs : log user agent and if it’s a search engine
gem 'lograge'
gem 'browser'

# Business logic: SMS and CALLS
gem 'nexmo'

# Customer Service Platform
gem 'zendesk_api'

# Mailing
gem 'gridhook', github: 'GuillaumeWrobel/gridhook', ref: '3adac6'
gem 'griddler'
gem 'griddler-sendgrid'

# Sendinblue marketing mailing
gem 'sib-api-v3-sdk'

# SEO sitemap generator
gem 'sitemap_generator'

# Pagination
gem 'pagy'

# Password encryption
gem 'bcrypt'

# Crash reporting
gem 'bugsnag'

# Model spatial latitude longitude
gem 'geokit-rails'
gem 'geokit'

# PDF
gem 'wicked_pdf'

# E164 international phone number normalizing, splitting, formatting
gem 'phony'

# Pretty things
gem 'awesome_print', require: 'ap'
gem 'friendly_id'

# JSON, XML
gem 'json'
gem 'multi_json'
gem 'rabl-rails', github: "navidemad/rabl-rails"
gem 'oj'

# New Relic
gem 'newrelic_rpm'

# CSV
gem 'csv'

# Export as XLSX
gem 'rubyzip'
gem 'caxlsx_rails'
gem 'xlsxtream'
gem 'fast_excel'

# Read Excel files
gem 'spreadsheet'

# Internationalization
gem 'i18n-tasks'
gem 'i18n-tasks-csv'
gem 'rails-i18n'
gem 'route_translator'
gem 'http_accept_language'
gem 'country_select'

# The simplest way to group by: day, week, hour of the day
gem 'groupdate'

# JavaScript charts with one line of Ruby
gem 'chartkick'

# Number to letters
gem 'humanize'

gem 'rack-timeout'

# Working hours
gem 'working_hours'

# ActiveModel like attributes for PORO objects
gem 'virtus'

# Profiler
gem 'rack-mini-profiler'

# Picture gallery
gem 'magnific-popup-rails'

# Phone number
gem 'intl-tel-input-rails'

# Used in Streak binding
gem 'http'

# Read/write files/spreadsheets in Google Drive/Docs.
gem 'google_drive'

# Catch unsafe migrations at dev time
gem 'strong_migrations'

# Slack API wrapper for Ruby
gem 'slack-notifier'

# async rendering
gem 'render_async'

# https://blog.jasonharrelson.com/blog/2014/03/07/how-i-design-rails-applications-part-1-value-objects/
# Value Object
gem 'enumerative'

# Track changes to your models
gem 'paper_trail'

# AASM is a continuation of the acts-as-state-machine rails plugin, built for plain Ruby objects.
gem 'aasm'

# Detect gender (male female)
gem 'gender_detector'

# Markdown
gem 'redcarpet'

# DSL to check your data for inconsistencies
gem 'checker_jobs'

# Allows you to add Google sign-in to your Rails app
gem 'google_sign_in'

# A flexible authentication system utilizing Rack middleware
gem 'omniauth'

# Facebook OAuth2 Strategy for OmniAuth
gem 'omniauth-facebook'

# Heroku Platform API
gem 'platform-api'

# A library for generating fake data such as names, addresses, and phone numbers.
gem 'faker'

# Caroussel
gem 'jquery-slick-rails'

# Counter cache
gem 'counter_culture'

# Controller Action caching
gem 'actionpack-page_caching'

# Algolia search engine - Search made easy
gem 'algoliasearch-rails'
gem 'algoliasearch'

# Create and manage database triggers
gem 'hairtrigger'

# builds named scopes that take advantage of PostgreSQL's full text search.
gem 'pg_search'