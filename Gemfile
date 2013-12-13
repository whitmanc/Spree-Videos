source 'http://rubygems.org'
gemspec

gem 'nokogiri', '~> 1.6.0'

group :test do
  if RUBY_PLATFORM.downcase.include? "darwin"
    gem 'guard-rspec'
    gem 'rb-fsevent'
    gem 'growl'
  end
  gem 'coffee-rails'
end

gem 'spree', '~> 1.3'