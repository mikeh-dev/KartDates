source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

gem "rails", "~> 7.0.6"

gem "sprockets-rails"

gem "pg"

gem "puma", "~> 5.0"

gem "jsbundling-rails"

gem "turbo-rails"

gem "stimulus-rails"

gem "jbuilder"

gem "redis", "~> 4.0"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# Use Sass to process CSS
# gem "sassc-rails"

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
gem "image_processing", "~> 1.2"

group :development, :test do
  gem "rspec-rails", "~> 5.0", ">= 5.0.2"
  gem "factory_bot_rails", "~> 6.2", ">= 6.2.0"
  gem "faker", "~> 2.18", ">= 2.18.0"
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"

  # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem "rack-mini-profiler"

  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "selenium-webdriver"
  gem "webdrivers"
  gem "capybara"
  gem "shoulda-matchers"
end
gem "devise", "~> 4.8", ">= 4.8.1"
gem "friendly_id", "~> 5.4", ">= 5.4.2"
gem "cssbundling-rails"
gem "name_of_person"
gem "sidekiq", "~> 6.5", ">= 6.5.4"
gem "stripe"
