source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.3.4'

# Core gems
gem 'bcrypt'
gem 'bootsnap', '>= 1.15.0', require: false
gem 'http'
gem 'jbuilder', '~> 2.7'
gem 'puma', '~> 5.6'
gem 'nokogiri', '>= 1.15.4'
gem 'rails', '~> 7.2'
gem 'sprockets', '< 4'
gem 'sassc-rails'
gem 'faker'

# Required gems for future Ruby versions
gem 'mutex_m'
gem 'csv'

# Development and test environment gems
group :development, :test do
  gem 'amazing_print'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'dotenv-rails'
  gem 'pry-rails'
  
  # ✅ Correct sqlite3 version
  gem 'sqlite3', '~> 1.5', '>= 1.5.2'

  gem 'table_print'
  gem 'web_git', github: 'firstdraft/web_git'
  gem 'grade_runner', github: 'firstdraft/grade_runner'
end

# Additional development gems
group :development do
  gem 'listen', '~> 3.7'
  gem 'annotate'
  gem 'better_errors', '2.6'
  gem 'binding_of_caller'
end

# Test environment gems
group :test do
  gem 'capybara'
  gem 'factory_bot_rails'
  gem 'rspec-html-matchers'
  gem 'rspec-rails'
  gem 'webmock'
end

# Production environment gems
group :production do
  gem 'pg'
end
