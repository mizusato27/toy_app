source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.8"

gem "rails", "7.1.0"
gem "sassc-rails"
gem "sprockets-rails", "3.5.2"
gem "importmap-rails", "2.2.2"
gem "turbo-rails", "2.0.12"
gem "stimulus-rails", "1.3.4"
gem "jbuilder", "2.13.0"
gem "puma", "~> 6.0"
gem "bootsnap", "1.18.6", require: false
gem "sqlite3", "1.7.3"
gem "concurrent-ruby", "1.3.5"

group :development, :test do
  gem 'reline', '~> 0.5'
  gem "debug", "~> 1.7", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  gem "web-console", "4.2.1"
  gem "solargraph", "~> 0.53"
  gem "irb", "1.15.2"
  gem "repl_type_completor"
end

group :test do
  gem "capybara", "3.40.0"
  gem "selenium-webdriver", "4.1.0"
  gem "webdrivers", "5.3.1"
  gem "rails-controller-testing"
  gem "minitest", "5.25.5"
  gem "minitest-reporters"
  gem "guard"
  gem "guard-minitest"
end
