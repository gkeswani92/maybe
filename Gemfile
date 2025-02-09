source "https://rubygems.org"

ruby "3.3.0"

# Rails
gem "rails", github: "rails/rails", branch: "main"

# Drivers
gem "pg", "~> 1.1"
gem "redis", ">= 4.0.1"

# Deployment
gem "puma", ">= 5.0"
gem "bootsnap", require: false

# Assets
gem "importmap-rails"
gem "propshaft"
gem "tailwindcss-rails"

# Hotwire
gem "stimulus-rails"
gem "turbo-rails", github: "hotwired/turbo-rails", branch: "main"

# Other
gem "bcrypt", "~> 3.1.7"
gem "inline_svg"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ windows jruby ]

group :development, :test do
  gem "debug", platforms: %i[ mri windows ]
  gem "brakeman", require: false
  gem "rubocop-rails-omakase", require: false
  gem "dotenv"
  gem "letter_opener"
  gem "i18n-tasks"
end

group :development do
  gem "web-console"
  gem "hotwire-livereload"
  gem "ruby-lsp-rails"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
end
