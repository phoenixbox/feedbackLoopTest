source "https://rubygems.org"

ruby '2.1.5'
gem "rails", "4.1.1"
gem "pg", "0.17.1"
gem "uglifier", ">= 1.3.0"
gem "jquery-rails", "3.1.0"
gem "sass-rails", "4.0.3"
gem "bootstrap-sass", "~> 3.1.1"
gem "puma"
gem "turbolinks"

group :development, :test do
  gem "dotenv-rails", "0.11.1"
  gem "rspec-rails", "3.0.1"
  gem "capybara", "2.3.0"
  gem "selenium-webdriver", "2.42.0"
  gem "pry"
  gem "database_cleaner", "1.3.0"
  gem "jasmine", "2.0.2"
# Guard Live Reload
  gem "guard", ">= 2.2.2",       :require => false
  gem "guard-livereload",        :require => false
  gem "rack-livereload"
  gem "rb-fsevent",              :require => false
end

group :production, :staging do
  gem "rails_12factor"
end