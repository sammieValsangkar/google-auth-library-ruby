source "https://rubygems.org"
git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end
# Specify your gem's dependencies in googleauth.gemspec
gemspec
gem "signet", github: 'sammieValsangkar/signet', branch: 'ruby-2.3-compatible'

group :development do
  gem "bundler", ">= 1.9"
  gem "coveralls", "~> 0.7"
  gem "fakefs", "~> 0.6"
  gem "fakeredis", "~> 0.5"
  gem "logging", "~> 2.0"
  gem "rack-test", "~> 0.6"
  gem "rake", "~> 10.0"
  gem "redis", "~> 3.2"
  gem "rspec", "~> 3.0"
  gem "rubocop", ">= 0.41", "< 0.50"
  gem "simplecov", "~> 0.9"
  gem "sinatra"
  gem "webmock", "~> 1.21"
end

platforms :jruby do
  group :development do
  end
end
