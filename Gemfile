source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.2'

gem 'rails', '~> 6.1.4', '>= 6.1.4.1'
gem 'sqlite3', '~> 1.4'
gem 'puma', '~> 5.0'
gem 'sass-rails', '>= 6'
gem 'webpacker', '~> 5.0'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.7'
gem 'bootsnap', '>= 1.4.4', require: false

gem 'figaro'
gem 'simple_form'
gem 'devise'
gem 'haml'
gem "haml-rails", "~> 2.0"
#gem 'image_processing'

gem 'kaminari'
gem 'bootstrap4-kaminari-views'
gem 'ransack'
#gem 'select2-rails'
gem 'rubyzip'

gem 'redis'
gem 'sidekiq'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'dotenv-rails'
  gem 'pry'
  gem 'pry-rails'
  gem 'awesome_print'
  gem 'rspec-rails'
  gem 'solargraph'
  gem 'factory_bot_rails'
  gem 'faker'
end

group :development do
  gem 'web-console', '>= 4.1.0'
  gem 'rack-mini-profiler', '~> 2.0'
end

group :test do
  gem 'capybara', '>= 3.26'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
