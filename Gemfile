source 'http://rubygems.org'

gem 'rails', '3.2.6'
gem 'sqlite3', '1.3.5'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '3.2.4'
  gem 'coffee-rails', '3.2.2'
  gem 'uglifier', '1.2.3'
end

gem 'jquery-rails', '2.0.0'

# group :production do
#   gem 'pg', '0.12.2'
# end 

group :development, :test do
  gem 'rspec-rails', '2.10.0'
  gem 'guard'
  gem 'guard-rspec'
  gem 'guard-spork'
  gem 'pry'
end

group :test do
  gem 'factory_girl_rails'
  gem 'simplecov', :require => false
  gem 'rb-fsevent'
  gem 'spork'
  gem 'capybara', '1.1.2'
  # Pretty printed test output
  gem 'turn', '0.8.2', :require => false
end