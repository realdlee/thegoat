source 'https://rubygems.org'

gem 'rails', '3.2.13'
gem 'pg'
gem 'jquery-rails'
gem 'simple_form'
gem 'strong_parameters'

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end

group :development, :test do
  gem 'factory_girl_rails'
  gem 'rspec-rails'
end

group :test do
  gem 'bourne', require: false
  gem 'database_cleaner'
  gem 'launchy'
  gem 'shoulda-matchers'
  gem 'simplecov', require: false
end

group :staging, :production do
  gem 'newrelic_rpm'
end
