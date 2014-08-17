source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.4'
# Use mysql as the database for Active Record
gem 'mysql2'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.3'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.

gem "grape"
gem "grape-swagger"

gem "figaro", github: 'laserlemon/figaro'

gem 'unicorn'

gem 'rvm-capistrano'

gem 'sdoc', '~> 0.4.0',          group: :doc

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
gem 'spring',        group: :development

group :development do
  gem 'annotate'
  gem 'better_errors', '~> 0.9.0'
  gem 'binding_of_caller'
  gem 'cape'
  gem 'capistrano'
  gem 'capistrano-ext'
  gem 'capistrano-unicorn', :require=>false
  gem 'meta_request'
  gem 'powder'
end

group :development, :test do
  gem "pry-nav"
  gem 'pry-rails'
  gem "pry-remote"

  gem 'rspec-rails'
  gem "database_cleaner"
  gem "shoulda-matchers"
  gem "factory_girl_rails"
  gem "faker"  

  gem 'timecop'
end

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

