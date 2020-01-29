source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem "jekyll-theme-cayman"
gem "jekyll-feed", "~> 0.13.0"
gem "jekyll-seo-tag", "~> 2.1"
gem "ffi", "~> 1.9.25"

gem "jekyll-theme-minimal"
gem "minima", "~> 2.0"
gem 'github-pages', versions['github-pages'], group: :jekyll_plugins
gem "nokogiri", ">= 1.10.4"
gem "rubyzip", ">= 1.3.0"
