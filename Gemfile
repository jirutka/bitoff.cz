source "https://rubygems.org"

require "json"
require "open-uri"
versions = JSON.parse(open("https://pages.github.com/versions.json").read)

gem "github-pages", versions["github-pages"]

group :development do
  gem "forematter", git: "https://github.com/jnv/forematter", require: false
end

group :jekyll_plugins do
    gem "jekyll-livereload"
end
