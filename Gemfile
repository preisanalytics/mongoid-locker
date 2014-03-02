source 'http://rubygems.org'

gem 'mongoid', '>= 2.4', '< 5'


# groups need to be copied to gemfiles/*.gemfile

group :development do
  gem 'rspec'
  gem 'bundler'
  gem 'jeweler'

  gem 'guard-rspec'
  gem 'rb-fsevent'
end

group :development, :test do
  gem 'bson_ext', :platforms => :ruby

  gem 'rake'
  gem 'appraisal', '~> 1.0.0.beta1'
end
