source 'http://rubygems.org'

#gem 'rails', '3.1.0'
gem 'rails', '4.0.4'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

# for Heroku deployment - as described in Ap. A of ELLS book
group :development, :test do
  gem 'sqlite3'
  gem 'database_cleaner'
  gem 'capybara'
  gem 'launchy'
  gem 'rspec-rails'
  gem 'turbolinks'
  #gem 'haml'
  gem 'haml-rails'
  #gem 'haml-contrib'
  gem 'RedCloth'
  gem 'sprockets', '2.11.0'
  gem "omniauth-google-oauth2", "~> 0.2.1"
  gem 'bootstrap-sass', '2.3.2.0'
  gem 'webrat' 
  gem 'factory_girl_rails' 
end
group :test do
  gem 'cucumber-rails', :require => false
  gem 'cucumber-rails-training-wheels'
  gem 'shoulda-matchers'
  gem 'shoulda'
end
group :production do
  gem 'pg'
  gem 'rails_12factor'
  gem 'bootstrap-sass', '2.3.2.0'
  gem "omniauth-google-oauth2", "~> 0.2.1"
  gem 'sprockets', '2.11.0'
  gem 'turbolinks'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'therubyracer'              
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'uglifier'
end

gem 'jquery-rails'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
gem 'haml'
