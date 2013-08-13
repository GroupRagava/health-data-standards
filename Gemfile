source "http://rubygems.org"

gemspec :development_group => :test

gem 'mongoid', :git => 'https://github.com/mongoid/mongoid.git'

group :development do
  gem 'rake'
  gem 'pry', '~> 0.9.10'
  gem 'pry-nav', '~> 0.2.2'

end

group :test do
  gem 'factory_girl', '~> 4.1.0'
  gem "tailor", '~> 1.1.2'
  gem "cane", '~> 2.3.0'
  gem 'simplecov', :require => false
  gem 'webmock'

  gem 'minitest'
  gem 'turn', :require => false
  gem 'awesome_print', :require => 'ap'

end
