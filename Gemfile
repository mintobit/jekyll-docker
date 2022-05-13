source "https://rubygems.org"

gem "docker-template"

group :development do
  gem 'envygeeks-rubocop'
  unless ENV["CI"] == "true"
    gem "travis"
    gem "pry"
    gem "webrick"
  end
end
