source 'https://rubygems.org'

gemspec
require 'typhoeus/adapters/faraday'

# gem 'neo4j-advanced',   '>= 1.8.1', '< 2.0', :require => false
# gem 'neo4j-enterprise', '>= 1.8.1', '< 2.0', :require => false

gem 'activesupport', '~> 4.2' if RUBY_VERSION.to_f < 2.2

group 'development' do
  gem 'listen', '< 3.1'
  gem 'guard-rspec', require: false
  if RUBY_VERSION.to_f < 2.0
    gem 'overcommit', '< 0.35.0'
  else
    gem 'overcommit'
  end
end

group 'test' do
  gem 'coveralls', require: false
  gem 'simplecov-html', require: false
  gem 'tins', '< 1.7' if RUBY_VERSION.to_f < 2.0
  gem 'rspec', '~> 3.0'
  gem 'rspec-its'
  gem 'dotenv'
end
