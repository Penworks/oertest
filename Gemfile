# frozen_string_literal: true

source "https://rubygems.org"
gemspec

gem "jekyll", ENV["JEKYLL_VERSION"] if ENV["JEKYLL_VERSION"]
gem "kramdown-parser-gfm" if ENV["JEKYLL_VERSION"] == "~> 3.9"
# added below from cmd line help info when getting depracation warnings about scss @import
gem 'wdm', '>= 0.1.0'
# added to update the Minima Sass that was throwing a ton of depracated error warnings
gem 'jekyll-sass-converter', '~> 2.0'
# add the paginator v2
#gem 'jekyll-paginate-v2', '~>2.0.0'
gem 'jekyll-paginate-v2'