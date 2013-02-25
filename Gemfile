source 'https://rubygems.org'
# source 'http://ruby.taobao.org'

gem 'rails', '~> 3.2.8'

# Site map generator
# gem 'sitemap_generator'

# User
gem 'devise'
gem 'devise-async'
gem 'devise-encryptable'
gem 'omniauth'
gem 'omniauth-weibo-oauth2'
gem 'omniauth-xiaonei'
# gem 'omniauth-douban-oauth2'
# gem 'omniauth-tqq-oauth2'
gem 'weibo_2', :git => 'https://github.com/jonnyzheng/weibo_2.git' # weibo api
gem 'renren', :git => 'https://github.com/jasl/renren.git' # renren api
gem 'cancan' # access control

# Acts as something
gem 'acts-as-messageable'
gem 'acts-as-taggable-on'
gem 'acts_as_commentable'

# Attachments
gem 'carrierwave'
# gem 'mini_magick' # when using upyun, this is no need
gem 'carrierwave-upyun'
gem 'rest-client' # for up yun

# UI
gem 'jquery-rails'
# gem 'cells'

# Pagination
gem 'kaminari'

# Base administrator's panel
gem 'rails_admin'
gem 'rails_admin_tag_list'

# Task queue
gem 'delayed_job'
gem 'delayed_job_active_record'
gem 'dj_mailer' # send mail using classic api
gem 'daemon-spawn'

# WYSIWYG editor
# gem 'rails_kindeditor' # attachments part not suit for real world

# Misc
gem 'settingslogic'
gem 'sanitize' # HTML sanitize
gem 'rails-i18n'
gem 'quiet_assets' # disabled assets log
gem 'whenever', :require => false # a pure ruby impl of crontab w/t friendly dsl
gem 'backup' # application data backup

# Server monitoring service. see http://www.newrelic.com about sign up and configuration
# gem 'newrelic_rpm'
# Exception reporting service, see more on http://www.airbrake.io
# gem 'airbrake'
# Google analytics
# gem 'garelic'

group :production do
  gem 'mysql2'

  # Memcached
  gem 'dalli'

  # Application server
  gem 'unicorn'
end

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  gem 'execjs'
  gem 'therubyracer'
  gem 'uglifier', '>= 1.0.3'

  # UI
  gem 'bootstrap-sass'
  gem 'compass-rails'
  gem 'jquery-ui-rails'

  gem 'turbo-sprockets-rails3'
end

group :development do
  # Generate table definations
  gem 'annotate'

  # Log analyzer
  gem 'request-log-analyzer'

  # Debugger
  gem 'pry'
  gem 'pry-rails'

  # Deploy
  gem 'capistrano'
  gem 'rvm-capistrano'
  gem 'capistrano-unicorn'
  gem 'sushi'
  gem 'capistrano_colors'
  gem 'foreman' # very cool... but... configuration is too simple to use on production
end

group :development, :test do
  gem 'letter_opener' # send mail to broswer, not really send
  gem 'rspec-rails'
  gem 'awesome_print'

  gem 'sqlite3'
  gem 'thin'
end

group :test do
  gem 'capybara'
  gem 'database_cleaner'
  gem 'launchy'
  gem 'factory_girl'
  gem 'shoulda-matchers'
  gem 'email_spec'
end
