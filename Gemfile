# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }

group :test do
  gem 'rspec'
  gem 'rubocop'
  gem 'simplecov', '~> 0.12.0', require: false
  gem 'simplecov-console', require: false
end


group :development, :test do
  gem 'rspec'
end