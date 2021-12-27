source 'https://rubygems.org'

#gem 'rails', '7.0.0'
gem "rails", github: "rails/rails", branch: "7-0-stable"

gem 'sassc-rails'
gem 'terser'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'
gem 'rails-html-sanitizer'
gem 'sdoc', group: :doc
gem 'overcommit'

group :development do
  gem 'web-console'
end

group :development, :test do
  gem 'sqlite3'
  gem 'byebug'
  gem 'spring'
  gem 'rails-controller-testing'
  gem 'brakeman'
end

group :production do
#HID:  gem 'pg' # HID on 10/3/2020
  gem 'rails_12factor'
end
