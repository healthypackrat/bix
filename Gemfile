# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

ruby '2.7.1'

gem 'dry-system'
gem 'dry-auto_inject'
gem 'dry-validation', '~> 1.4'
gem 'dry-monads', '~> 1.3'

gem 'rom'
gem 'rom-sql'
gem 'pg'

gem 'dotenv'
gem 'rake'

gem "hanami-controller", "~> 1.3"
gem "hanami-router", "~> 1.3"

gem "rack-test"

gem "puma"

group :test do
  gem 'rspec'
  gem 'database_cleaner-sequel'
end
