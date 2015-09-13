source 'http://rubygems.org'

ruby '2.0.0'
# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'
gem 'rails', '~> 4'
gem 'pg'
# store sessions in db rather than in cookies
gem 'activerecord-session_store'
# deprecated, to remove, user.UserObserver is the only place we use this
gem 'rails-observers'
gem "haml-rails", "~> 0.9"

# web server
gem 'unicorn'

# pagination & tagging
gem "kaminari", "~> 0.15.1"
gem 'will_paginate', "~> 3.0.pre2"
gem 'acts-as-taggable-on'

# Emails
gem 'actionmailer-with-request', '~> 0.3'
gem 'exception_notification' , '~> 4'

# Security
gem 'authlogic'
gem 'rubycas-client', "~> 2.3.9", :require => ['casclient', 'casclient/frameworks/rails/filter']
gem 'ucb_ldap', "2.0.0.pre5"
gem 'omniauth'
gem 'omniauth-cas'
gem 'bcrypt'

# Misc
gem 'pothoven-attachment_fu'
gem 'nokogiri'

# Deploy with Capistrano
gem 'capistrano'

# Production-specific
group :production do
  gem 'rails_12factor'
end

# Development
group :development do
  gem 'yard'
  gem 'better_errors', "1.1.0"
  gem 'binding_of_caller'
  gem 'bullet'
  gem 'annotate'
end

# Testing
group :test do
  gem 'autotest-rails'
  gem 'rspec-rails'
  gem 'cucumber-rails', "~> 1.4.2"
  gem 'capybara'
  gem 'database_cleaner'
  gem 'simplecov'
end

# UI
gem 'therubyracer'
gem 'uglifier'
gem 'sass-rails', '>= 3.2'
gem 'jquery-rails'
gem 'jquery-ui-rails'
gem 'bootstrap-sass', '~> 3.3.3'
gem 'bootstrap_form'
gem 'bootstrap-material-design'

gem 'jquery-datatables-rails', '~> 3.3.0'
gem 'will_paginate-bootstrap'
gem 'bootstrap-datepicker-rails'