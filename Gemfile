source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'jekyll'
gem 'jekyll-coffeescript'
gem 'jekyll-watch'
gem 'jekyll-paginate'
gem 'rake'

group :jekyll_plugins do
    gem 'jekyll-livereload'
end