source 'https://rubygems.org'
ruby File.read('.ruby-version').chomp.split('-')[1] { |f| "ruby '#{f}'"}

gem 'sass-rails', '>= 6.0.0'
gem 'rails', '5.2.4.3'
gem 'unicorn'

gem 'jquery-rails', '>= 4.4.0'
gem 'nokogiri', '>= 1.10.4'

gem 'rest-client', '~> 2.0.2'
gem 'rgeo'
gem 'georuby'
# DSL grammar parsing and interpreting (used for CQL)
gem 'parslet'
gem 'rails-controller-testing', '>= 1.0.4'

gem 'responders', '~> 2.4', '>= 2.4.1'
gem 'loofah', '>= 2.3.1'
gem 'rack', '~> 2.2', '>= 2.2.3'
gem 'rake', '12.3.3'
gem 'sprockets', '3.7.2'

group :assets do
  gem 'coffee-rails', '>= 5.0.0'
  gem 'execjs'
  gem 'therubyracer'
  gem 'uglifier'
end

group :development do
  gem 'pry-rails'
end

# memory profiling
group :profile do
  gem 'ruby-prof'
end

group :test, :development do
  gem 'rspec-rails', '>= 4.0.1'
  gem 'rspec_junit_formatter'
end

group :test do
  gem 'vcr'
  gem 'webmock'
  gem 'capybara', '>= 3.32.2'
  gem 'rack-test', '>= 1.1.0'
end

group :production, :sit, :uat do
  gem 'rails_12factor'
end

gem 'bundler-audit'
