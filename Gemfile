source "https://rubygems.org"

ruby "2.3.1"

gem "active_model_serializers", "0.9.5"
gem "administrate", ">= 0.2.0"
gem "analytics-ruby", "~> 2.0.0", require: "segment/analytics"
gem "attr_extras"
gem "autoprefixer-rails"
gem "bourbon"
gem "coffee-rails"
gem "email_validator"
gem "faraday"
gem "font-awesome-rails"
gem "haml-rails"
gem "high_voltage"
gem "inifile"
gem "jquery-rails", "~> 4.2.0"
gem "neat"
gem "normalize-rails"
gem "octokit"
gem "omniauth-github"
gem "paranoia", "~> 2.0"
gem "pg"
gem "puma"
gem "rails", "4.2.7.1"
gem "rails-assets-classnames", source: "https://rails-assets.org"
gem "rails-assets-es5-shim", source: "https://rails-assets.org"
gem "rails-assets-lodash", source: "https://rails-assets.org"
gem "react-rails"
gem "resque", "~> 1.25.0"
gem "resque-scheduler"
gem "resque-sentry"
gem "rest-client", ">= 1.8.0"
gem "sass-rails"
gem "split", require: "split/dashboard"
gem "stripe"
gem "uglifier", ">= 2.7.2"

group :staging, :production do
  gem "rack-timeout"
  gem "rails_12factor"
  gem "sentry-raven", ">= 0.12.2"
end

group :development, :test do
  gem "bundler-audit", require: false
  gem "byebug"
  gem "dotenv-rails"
  gem "foreman"
  gem "quiet_assets"
  gem "rspec-rails", ">= 3.4"
end

group :test do
  gem "capybara", "~> 2.4.0"
  gem "capybara-webkit", "~> 1.6"
  gem "database_cleaner"
  gem "factory_girl_rails"
  gem "launchy"
  gem "shoulda-matchers"
  gem "webmock"
end
