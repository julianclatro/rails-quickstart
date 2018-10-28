source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.3'

### Basic Configuration
gem 'rails', '~> 5.2.1'
gem 'pg', '>= 0.18', '< 2.0'

### App Server
gem 'puma', '~> 3.11'
gem 'bootsnap', '>= 1.1.0', require: false

### Compilers
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'haml'

### UX
gem 'turbolinks', '~> 5'
gem 'nprogress-rails'
gem 'remotipart', '~> 1.2'
# gem 'friendly_id', '~> 5.1.0'
# gem 'browser'
# gem 'toastr-rails'

### Forms
gem 'simple_form'
gem 'reform'
gem 'reform-rails'
gem 'dry-validation'

### API Essentials
# gem 'jbuilder', '~> 2.5'

### Users
gem 'devise'

### OAuth
# gem 'omniauth-google-oauth2'
# gem 'omniauth-facebook'

### Mailing
# gem 'mailgun-ruby', '~>1.0.3', require: 'mailgun'
# gem 'mail_form'

### Analytics
# gem 'analytics-ruby', '~> 2.0.0', :require => 'segment/analytics'

### Data Upload
gem 'carrierwave'

### Data Storage
# gem 'fog', '~> 1.38'
# gem 'fog-aws', '~> 3.3'

### Data Structure
gem 'filterrific'
gem 'will_paginate', '~> 3.1.0'
gem 'ransack', github: 'activerecord-hackery/ransack'

### Data History
gem 'logidze'

### ActiveStorage variant
gem 'mini_magick'

### ActionCable
# gem 'redis', '~> 4.0'

### Security
# gem 'bcrypt', '~> 3.1.7'


### Development and Testing
group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rspec-rails', '~> 3.0'
end

group :development do
  # gem 'capistrano-rails'
  # gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'pry-rails'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'chromedriver-helper'
end
