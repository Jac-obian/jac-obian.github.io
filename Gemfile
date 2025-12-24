# # frozen_string_literal: true

# source "https://rubygems.org"

# gemspec

# gem "html-proofer", "~> 5.0", group: :test

# platforms :mingw, :x64_mingw, :mswin, :jruby do
#   gem "tzinfo", ">= 1", "< 3"
#   gem "tzinfo-data"
# end

# gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]

source "https://rubygems.org"

gem "jekyll", "~> 4.3"

group :jekyll_plugins do
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-gist"
  gem "jekyll-feed"
  gem "jekyll-include-cache"
  gem "jekyll-archives"
  gem "jekyll-seo-tag"
end

group :test do
  gem "html-proofer", "~> 5.0"
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]