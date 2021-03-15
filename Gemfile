source 'https://rubygems.org'

gem 'sinatra', '~> 2.1.0'
gem 'nokogiri', '~> 1.11.2'

group :test do
  gem 'capybara'
  gem 'capybara-selenium'
  gem 'pry-byebug'
  gem 'puma'
  gem 'rack-test'
  gem 'rspec'
end

group :development, :test do
  gem 'proofer', github: '18F/identity-proofer-gem', ref: 'v2.8.0'
  gem 'aamva', github: '18F/identity-aamva-api-client-gem', tag: 'v4.0.0'
  # gem 'lexisnexis', github: '18F/identity-lexisnexis-api-client-gem', tag: 'v3.1.0'
  # gem 'identity-doc-auth', github: '18F/identity-doc-auth', tag: 'v0.4.1'
end
