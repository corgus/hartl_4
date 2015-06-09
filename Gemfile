source 'https://rubygems.org'

# gem 'rails',                   '4.2.0'
# gem 'bcrypt',                  '3.1.7'
# gem 'faker',                   '1.4.2'
# gem 'carrierwave',             '0.10.0'
# gem 'mini_magick',             '3.8.0'
# gem 'fog',                     '1.23.0'
# gem 'will_paginate',           '3.0.7'
# gem 'bootstrap-will_paginate', '0.0.10'
# gem 'bootstrap-sass',          '3.2.0.0'
# gem 'sass-rails',              '5.0.2'
# gem 'uglifier',                '2.5.3'
# gem 'coffee-rails',            '4.1.0'
# gem 'jquery-rails',            '4.0.3'
# gem 'turbolinks',              '2.3.0'
# gem 'jbuilder',                '2.2.3'

# gem 'sdoc',                    '0.4.0', group: :doc

# group :development, :test do
#   gem 'sqlite3',     '1.3.9'
#   gem 'byebug',      '3.4.0'
#   gem 'web-console', '2.0.0.beta3'
#   gem 'spring',      '1.1.3'
# end

# group :test do
#   gem 'minitest-reporters', '1.0.5'
#   gem 'mini_backtrace',     '0.1.3'
#   gem 'guard-minitest',     '2.3.1'
# end

# group :production do
#   gem 'pg',             '0.17.1'
#   gem 'rails_12factor', '0.0.2'
#   gem 'puma',           '2.11.1'
# end


RAILS_VERSION = '~> 4.2.0'
ruby '2.1.3'
gem 'rails', RAILS_VERSION
gem 'pg', '~> 0.18.1'
gem 'activesupport',   RAILS_VERSION, :require => 'active_support'
gem 'actionpack',      RAILS_VERSION, :require => 'action_pack'
# gem 'actionpack-action_caching'
gem 'actionmailer',    RAILS_VERSION, :require => 'action_mailer'
gem 'railties',        RAILS_VERSION, :require => 'rails'
gem 'bcrypt',                  '3.1.7'
gem "slim-rails"
gem 'will_paginate',           '3.0.7'

gem 'bootstrap-sass', '~> 3.3.4'
# gem 'bootstrap-will_paginate', '0.0.10'
# gem 'nokogiri', '~> 1.6.6.2'
# gem 'tzinfo'
# gem 'simple_form'

# javascript
gem 'jquery-rails', '4.0.3'
# gem 'turbolinks', '2.3.0'
gem 'mapbox-rails', '~> 1.6.1.1'

# sessions
# gem 'devise'
# gem 'omniauth'
gem 'omniauth-facebook'

gem 'fog', '1.23.0'
gem 'carrierwave', '0.10.0'
gem 'mini_magick', '3.8.0'

gem 'sass-rails', '4.0.3' #, '5.0.2'
gem 'uglifier', '2.5.3'
gem 'coffee-rails', '4.1.0'
gem 'font-awesome-rails'

group :doc do
  gem 'sdoc', '~> 0.4.0'
end

group :development, :test do
  gem 'sqlite3',     '1.3.9'
  gem 'pry-rails', '~> 0.3.3'
  # gem 'haml-rails', '~> 0.5.3'
  gem 'spring', '~> 1.3.3'
  gem 'factory_girl_rails'
  gem 'faker', '1.4.2'
  gem 'rspec-rails', '~> 3.2.1'
  # gem 'better_errors' #, '~> 2.1.1'
  gem 'web-console', '2.0.0.beta3'
end

group :development do
  # gem 'binding_of_caller', :platforms=>[:mri_21]
  gem 'guard-bundler', require: false
  gem 'guard-rails'
  gem 'guard-rspec'
  gem 'quiet_assets'
  # gem 'rb-fchange', :require=>false
  # gem 'rb-fsevent', :require=>false
  # gem 'rb-inotify', :require=>false
  gem 'spring-commands-rspec'
  # gem 'mail_view', '~> 2.0.4'
  gem 'xray-rails'
end

group :test do
  gem 'capybara'
  gem 'database_cleaner', '~> 1.4.1'
  gem 'launchy'
  gem 'selenium-webdriver'

  gem 'minitest-reporters', '1.0.5'
  gem 'mini_backtrace',     '0.1.3'
  gem 'guard-minitest',     '2.3.1'
end

group :production do
  gem 'puma', '~> 2.9.1'
  gem 'rails_12factor'
end

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development
