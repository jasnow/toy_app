source "https://rubygems.org"

gem "rails", "7.0.4.2"

gem "sassc-rails"
gem "terser"
gem "jquery-rails"
gem "turbolinks"
gem "jbuilder"
gem "rails-html-sanitizer"
gem "sdoc", group: :doc
gem "overcommit"

group :development do
  gem "web-console"
end

group :development, :test do
  gem "sqlite3"
  gem "debug"
  gem "spring"
  gem "rails-controller-testing"
  gem "brakeman"
  gem "standard"
  gem "ruby_audit"
  gem "spektr"
end

group :production do
  # HID:  gem 'pg' # HID on 10/3/2020
  gem "rails_12factor"
end
