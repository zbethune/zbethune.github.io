source "https://rubygems.org"

# When you want to use a different Jekyll version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#gem "jekyll", "~> 4.0.0"
#gem "github-pages", "~> 217", group: :jekyll_plugins

# Plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "github-pages", "~> 217"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2.9"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

gem "webrick", "~> 1.7"

gem "jekyll-sass-converter", "~> 1.5.2" 
