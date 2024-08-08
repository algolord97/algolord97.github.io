# frozen_string_literal: true

source "https://rubygems.org"

gem 'github-pages', group: :jekyll_plugins

group :jekyll_plugins do
  gem 'jekyll-theme-chirpy'
  gem 'jekyll-include-cache'
  gem 'jekyll-sass-converter'
  gem 'jekyll-assets'
end

group :test do
  gem "html-proofer", "~> 3.19.0"
  gem 'tzinfo'
  gem 'tzinfo-data'
end

# Windows platform용 젬
gem 'wdm', '>= 0.1.0' if Gem.win_platform?
