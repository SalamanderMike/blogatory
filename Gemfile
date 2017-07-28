source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

ruby '2.4.1'

gem 'rails', '~> 5.1.2'
gem 'sqlite3'
gem 'puma', '~> 3.9.1'
gem 'sass-rails', '~> 5.0.6'
gem 'uglifier', '>= 3.2.0'

gem 'coffee-rails', '~> 4.2.2'
gem 'turbolinks', '~> 5.0.1'
gem 'jbuilder', '~> 2.7'
# gem 'redis', '~> 3.0'
# gem 'bcrypt', '~> 3.1.7'


group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver', '~> 3.4.4'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.5.1'
  gem 'listen', '>= 3.1.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring', '~> 2.0.2'
  gem 'spring-watcher-listen', '~> 2.0.1'
end
