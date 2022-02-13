# ホームページ
# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

# gem "rails"

gem "github-pages", group: :jekyll_plugins
sudo gem install bundler
sudo bundler install
cd docs
bundle exec jekyll serve
