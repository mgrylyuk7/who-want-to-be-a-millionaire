source 'https://rubygems.org'

gem 'rails', '~> 4.2.10'

gem 'devise', '~> 4.6.1'
gem 'devise-i18n'

gem 'uglifier', '>= 1.3.0'

gem 'jquery-rails'
gem 'twitter-bootstrap-rails'
gem 'font-awesome-rails'
gem 'russian'

group :development, :test do
  gem 'byebug'
  gem 'dotenv-rails'

  gem 'rspec-rails', '~> 3.4'
  gem 'factory_bot_rails'
  gem 'shoulda-matchers'

  gem 'capybara'
  gem 'launchy'
end

gem 'capybara-screenshot', :group => :test

group :production do
  gem 'pg'
  # гем, улучшающий вывод логов на Heroku
  # https://devcenter.heroku.com/articles/getting-started-with-rails4#heroku-gems
  gem 'rails_12factor'
end
