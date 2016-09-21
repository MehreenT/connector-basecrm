ruby "2.2.3", :engine => "jruby", :engine_version => "9.0.5.0"
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

gem 'maestrano-connector-rails', '~> 1.4'

gem 'oauth2'
gem 'basecrm'

group :production, :uat do
  gem 'activerecord-jdbcpostgresql-adapter', platforms: :jruby
  gem 'pg', platforms: :ruby
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
