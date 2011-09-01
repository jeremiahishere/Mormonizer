source 'http://rubygems.org'

gem 'rails', '3.1.0.rc8'
gem 'mysql2'

gem 'haml-rails'
gem 'therubyracer'
gem 'hpricot'
gem 'ruby_parser'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', "  ~> 3.1.0.rc"
  gem 'coffee-rails', "~> 3.1.0.rc"
  gem 'uglifier'
  gem 'compass', :git => 'git://github.com/chriseppstein/compass.git', :branch => 'rails31'
end

group :development, :test do
  gem 'web-app-theme', :git => 'git://github.com/jweslley/web-app-theme.git'
  gem 'rspec-rails'
  gem 'ruby-debug19', :require => 'ruby-debug'

  gem "capybara", "~>1.0.0"
  gem "database_cleaner", "~>0.6.7"
  gem "cucumber-rails"
  gem "pickle", "~>0.4.7"
  gem "cucumber"
  gem 'machinist'
end

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'
