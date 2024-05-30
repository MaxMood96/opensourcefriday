source "https://rubygems.org"

ruby File.read(
  File.expand_path("#{File.dirname(__FILE__)}/.ruby-version")
).strip

# Include https://github.com/heartcombo/devise/pull/5327 for OmniAuth 2
gem "devise", ">= 4.9.0"
gem "devise-i18n", ">= 1.10.3"
gem "faraday-http-cache"
gem "figaro"
gem "jquery-rails", ">= 4.5.0"
gem "octicons_helper", ">= 17.1.0"
gem "octokit"
gem "omniauth-github"
gem "omniauth-rails_csrf_protection", ">= 1.0.2"
gem "pg"
gem "puma"
gem "rack-host-redirect"
gem "rails", "~> 7.0", ">= 7.0.2.4"
gem "rtl"
gem "sassc-rails"
gem "sitemap_generator"
gem "turbolinks"
gem "uglifier"

group :development, :test do
  gem "byebug"
end

group :development do
  gem "listen"
  gem "rubocop"
  gem "rubocop-performance"
  gem "rubocop-rails"
  gem "spring"
  gem "web-console", ">= 4.2.1"
end

group :production do
  gem "connection_pool"
  gem "dalli"
  gem "kgio"
  gem "memcachier"
  gem "rack-cache"
end

group :test do
  gem "simplecov", require: false
  gem "vcr", require: false
end
