
source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.3.5'
gem 'rails', '~> 7.1.0'
gem 'sqlite3', '~> 1.6'
gem 'puma', '~> 6.0'
gem 'jbuilder', '~> 2.11'
gem 'bootsnap', '>= 1.17.0', require: false
gem 'webrick', '~> 1.8'
gem 'ostruct', '~> 0.5'
gem 'warnings'

# Asset pipeline (Sprockets) is optional in Rails 7+, so not included by default
# gem 'sprockets-rails', '~> 3.4'

group :development, :test do
  gem 'byebug', platforms: [:mri, :windows]
  gem 'rspec-rails', '~> 6.1'
  gem 'pry'
  gem 'rubocop', require: false
end

group :development do
  gem 'web-console', '>= 4.2.0'
  gem 'listen', '~> 3.7'
end

group :test do
  gem 'capybara', '>= 3.35'
  gem 'selenium-webdriver', '>= 4.0'
  gem 'webdrivers', '~> 5.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:windows, :jruby]
