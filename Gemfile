source 'https://rubygems.org'

gem 'rails', '3.2.12'
gem 'bcrypt-ruby', '3.0.1'
# gem 'bootstrap-sass', '2.1'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'


gem 'json'

group :production do
  gem 'pg', '0.12.2'
end

group :development, :test do
  gem 'rspec-rails', '2.11.0'
  gem 'sqlite3', '1.3.5'
  #gem 'thin'
  gem 'rails-dev-boost', :git => 'git://github.com/thedarkone/rails-dev-boost.git'
  gem 'rb-fsevent', '~> 0.9.1'
  gem 'annotate', '2.5.0'
end

group :test do
  gem 'capybara', '1.1.2'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '3.2.5'
  gem 'coffee-rails', '3.2.2'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '1.2.3'
  gem "therubyracer"
  gem "less-rails" #Sprockets (what Rails 3.1 uses for its asset pipeline) supports LESS
  gem "twitter-bootstrap-rails", '2.1.0'
end

gem 'jquery-rails', '2.0.2'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug'
