source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.5.1"

gem "rails", "~> 5.2.3"
gem "sqlite3"
gem "puma", "~> 3.11"
gem "sass-rails", "~> 5.0"
gem "uglifier", ">= 1.3.0"
group :development, :test do
  gem "rubocop", "~> 0.54.0", require: false
end
gem "coffee-rails", "~> 4.2"
gem "jbuilder", "~> 2.5"
gem "bcrypt", "3.1.11"
gem "bootstrap-sass", "3.3.7"
gem "config"
gem "rails-i18n"
gem "bootsnap", ">= 1.1.0", require: false
gem "rails-controller-testing"

group :development, :test do
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem "web-console", ">= 3.3.0"
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
end

group :test do
  gem "capybara", ">= 2.15"
  gem "selenium-webdriver"
  gem "chromedriver-helper"
end
group :production do
  gem "pg",             "~> 0.18"
  gem "rails_12factor", "0.0.2"
end
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
