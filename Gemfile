source 'https://rubygems.org'

gem 'rails', '~> 5.2.1'
gem 'rails-i18n'

gem 'autoprefixer-rails'
gem 'aws-sdk', '~> 2.2'
gem 'clearance'
gem 'clearance-deprecated_password_strategies'
gem 'daemons'
gem 'dalli'
gem 'delayed_job'
gem 'delayed_job_active_record'
gem 'gravtastic'
gem 'high_voltage'
gem 'honeybadger'
gem 'http_accept_language'
gem 'jquery-rails'
gem 'kaminari'
gem 'mail', '2.6.6'
gem 'newrelic_rpm'
gem 'paul_revere', '~> 3.0.0'
gem 'pg', platform: :mri
gem 'activerecord-jdbcpostgresql-adapter', platform: :jruby
gem 'rack'
gem 'rack-utf8_sanitizer'
gem 'rbtrace', '~> 0.4.8', platform: :mri
gem 'rdoc'
gem 'rest-client', require: 'rest_client'
gem 'roadie-rails', '~> 1.3.0'
gem 'sass', require: false
gem 'shoryuken', '~> 2.1.0', require: false
gem 'statsd-instrument', '~> 2.3.0'
gem 'uglifier', '>= 1.0.3'
gem 'unicorn', '~> 5.5.0.1.g6836', platform: :mri, require: false
gem 'validates_formatting_of'
gem 'elasticsearch-model', '~> 5.0.0'
gem 'elasticsearch-rails', '~> 5.0.0'
gem 'elasticsearch-dsl', '~> 0.1.2'
gem 'faraday_middleware-aws-sigv4', '~> 0.2.4'
gem 'xml-simple'
gem 'compact_index', '~> 0.11.0'
gem 'sprockets-rails'
gem 'rack-attack'
gem 'rqrcode'
gem 'rotp'

# Logging
gem 'lograge'
gem 'logstash-event'

group :development, :test do
  gem 'rubocop', require: false
  gem 'toxiproxy', '~> 1.0.0'
  gem 'pry-byebug', platform: :mri
end

group :development do
  gem 'bootsnap', require: false
  gem 'rails-erd'
  gem 'listen'
end

group :test do
  gem 'minitest', require: false
  gem 'capybara', '~> 2.18'
  gem 'factory_bot_rails'
  gem 'launchy'
  gem 'rack-test', require: 'rack/test'
  gem 'mocha', require: false
  gem 'shoulda'
end

group :development, :deploy do
  gem 'kubernetes-deploy', '>= 0.20.6', platform: :mri, require: false
end
