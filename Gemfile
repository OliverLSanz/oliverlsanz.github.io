# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

# the github pages gem will install the right jekill version
# gem "jekyll"

gem "github-pages", "~> 214", group: :jekyll_plugins

# add plugins for sitemap, rss and seo
group :jekyll_plugins do
    gem 'jekyll-sitemap'
    gem 'jekyll-feed'
    gem 'jekyll-seo-tag'
  end