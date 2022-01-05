source 'https://rubygems.org/'

gemspec

gem 'rake'

group :development do
  platforms :mri do
    gem 'yard'
    gem 'redcarpet'
  end
end

group :http_client_example do
  gem 'http_parser.rb', '< 0.7'
end

group :test do
  gem 'rspec'
  gem 'rspec-collection_matchers'
  gem 'simplecov'
  gem 'coveralls'
end