# frozen_string_literal: true

source "https://rubygems.org"
gemspec


gem "jekyll", "~> 4.2"

group :jekyll_plugins do
	gem "jekyll-feed", "~> 0.12"
	gem "jekyll-paginate"
end


install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
	gem "tzinfo", "~> 1.2"
	gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?