source "https://rubygems.org"

source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.3.0"

gem "bootsnap", require: false

gem "jbuilder"

gem "importmap-rails"

gem "propshaft"

gem "pg", "~> 1.1"

gem "puma", ">= 5.0"

gem "rails", "~> 8.0.2"

gem "stimulus-rails"

gem "turbo-rails"

gem "tzinfo-data", platforms: %i[ windows jruby ]

gem "solid_cache"
gem "solid_queue"
gem "solid_cable"


gem "kamal", require: false


gem "thruster", require: false

group :development, :test do
  
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"

  
  gem "brakeman", require: false

  
  gem "rubocop-rails-omakase", require: false
end

group :development do
 
  gem "web-console"
end
