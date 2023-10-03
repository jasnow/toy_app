source "https://rubygems.org"

gem "rails", "7.1.0.rc2"

gem "bigdecimal"
gem "mutex_m"

gem "sassc-rails"
gem "terser"
gem "jquery-rails"
gem "turbolinks"
gem "jbuilder"
gem 'mini_racer', platform: :ruby
gem "rails-html-sanitizer"
gem "sdoc", group: :doc
gem "overcommit"
gem "webrick"

group :development do
  gem "web-console"
  gem "ruby_audit"
  gem "spektr"
end

group :development, :test do
  gem "sqlite3"
  gem "spring"
  gem "rails-controller-testing"
  gem "brakeman"
  gem "standard"
end

group :production do
  # HID:  gem 'pg' # HID on 10/3/2020
  gem "rails_12factor"
end

gem 'simplecov', require: false, group: :test
