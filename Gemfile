source 'https://rubygems.org'

gem 'rails', '3.2.3'
gem 'sass'
gem 'jquery-rails'
gem "swf_fu", "~> 2.0"

gem 'execjs'
gem 'therubyracer', :platforms => :ruby

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem "mysql2", "~> 0.3.11"
gem "mysql"
gem "sequel"
gem "haml-rails"

# gem 'tiny_tds'                          !!!!!!= when pushing to heroku remove this
# gem 'activerecord-sqlserver-adapter'

# Gems used only for assets and not required
# in production environments by default.
gem 'coffee-script'
gem 'liquid'

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platform => :ruby

  gem 'uglifier', '>= 1.0.3'
end

group :test, :development do
  gem "rspec-rails", "~> 2.0"
  gem "capybara"
  gem "sqlite3-ruby" 
  # "sqlite3", "~> 1.3.0", :require => "sqlite3"
end

group :production, :staging do
  # gem 'therubyracer-heroku', '0.8.1.pre3'
  gem "pg"
end


# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
group :development do
  gem 'debugger'
end

