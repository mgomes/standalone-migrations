source 'https://rubygems.org'

gem 'rake', '>= 10.0'
gem 'activerecord', ENV['AR'] ? ENV['AR'].split(",") : [">= 5.1.0", "< 5.3.0"]
gem 'railties', ENV['AR'] ? ENV['AR'].split(",") : [">= 5.1.0", "< 5.3.0"]

group :dev do
  gem 'sqlite3'
  gem 'rspec', '>= 2.99.0'
  gem 'jeweler'
end
