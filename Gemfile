source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.2'

gem 'bcrypt'
gem 'rails'
gem 'puma'
gem 'sass-rails'
gem 'faker'
gem 'carrierwave'
gem 'mini_magick'
gem 'fog'

gem 'will_paginate'
gem 'bootstrap-will_paginate'
gem 'webpacker'
gem 'turbolinks'
gem 'jbuilder'
gem 'rexml'
gem 'bootsnap', require: false

group :development, :test do
  gem 'sqlite3'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console'
  gem 'listen'
  gem 'spring'
  gem 'spring-watcher-listen'
end

group :test do
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
  gem 'puma'
end
