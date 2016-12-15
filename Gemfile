source 'https://rubygems.org'

gem 'rails', '~> 4.2'
gem 'puma', require: false

gem 'turbolinks'
gem 'jquery-rails'
gem 'coffee-rails'

gem 'figaro'
gem 'tzinfo-data', platforms: [:mingw, :mswin, :jruby]
gem 'uglifier', '>= 1.3.0'
gem 'config'

gem 'maestrano-connector-rails', '2.0.0'

gem 'oauth2'
gem 'basecrm'

group :production, :uat do
  gem 'activerecord-jdbcmysql-adapter', platforms: :jruby
  gem 'mysql2', platforms: :ruby
  gem 'rails_12factor'
end

group :test, :develpment do
  gem 'activerecord-jdbcsqlite3-adapter', platforms: :jruby
  gem 'sqlite3', platforms: :ruby
end

group :test do
  gem 'simplecov'
  gem 'coveralls', require: false
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'shoulda-matchers'
  gem 'timecop'
end
