source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.3', '>= 6.0.3.4'
# Use Puma as the app server
gem 'puma', '~> 4.1'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 4.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

gem 'sprockets-rails', :require => 'sprockets/railtie'
# Twitter bootstrap for front-end UI
gem 'bootstrap', '~> 5.0.0.alpha2'
# Bootstrap JavaScript depends on jQuery. If you're using Rails 5.1+, add the jquery-rails gem to your Gemfile:
gem 'jquery-rails'

# Font Awesome for icons
gem 'font-awesome-sass', '~> 5.15.1'

# To visualize the DB
gem 'hirb'

# dotenv to saet ENV variables
gem 'dotenv-rails', groups: [:development, :test]

# devise por user authentication
gem 'devise'

group :development, :test do
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3', '~> 1.4'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development, :test do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

group :production do
  # Use the PostgreSQL gem for Heroku production servers
  gem 'pg', '>= 0.18.4'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
