source "https://rubygems.org"
git_source(:github){|repo| "https://github.com/#{repo}.git"}

ruby "2.5.1"
gem "bootsnap", ">= 1.1.0", require: false
gem "coffee-rails", "~> 4.2"
gem "config"
gem "jbuilder", "~> 2.5"
gem "kaminari", "~> 1.1.1"
gem "pg", ">= 0.18", "< 2.0"
gem "puma", "~> 3.11"
gem "rails", "~> 5.2.4", ">= 5.2.4.2"
gem "sass-rails", "~> 5.0"
gem "strip_attributes", "~> 1.9.0"
gem "uglifier", ">= 1.3.0"
gem "dotenv-rails", "~> 2.7.5"
gem "activerecord-import", "1.0.4"
gem "carrierwave"
gem "validates_lengths_from_database", "0.8.0"
gem "capistrano"
gem "capistrano-rails"
gem "capistrano-rvm"
gem "capistrano3-puma"
gem "listen", ">= 3.0.5", "< 3.2"
gem "spring"
gem "spring-watcher-listen", "~> 2.0.0"
gem "web-console", ">= 3.3.0"

group :development, :test, :staging, :sun_staging do
  gem "letter_opener_web", "~> 1.0"
end

group :development, :test do
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
end

group :development, :test do
  gem "factory_bot_rails", "~> 5.0.2"
  gem "pry-rails", "~> 0.3.6"
  gem "rspec-rails", "~> 3.8.0"
  gem "rubocop", "~> 0.62.0", require: false
  gem "shoulda-matchers", "~> 4.0.0.rc1"
  gem "shoulda-callback-matchers"
end


group :test do
  gem "capybara", ">= 2.15"
  gem "chromedriver-helper"
  gem "selenium-webdriver"
end
