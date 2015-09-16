source 'https://rubygems.org'

gem "bundler", "> 1"
gem "rake"

gem 'elasticsearch-api',        :path => File.expand_path("../elasticsearch-api", __FILE__),        :require => false
gem 'elasticsearch-transport',  :path => File.expand_path("../elasticsearch-transport", __FILE__),  :require => false
gem 'elasticsearch-extensions', :path => File.expand_path("../elasticsearch-extensions", __FILE__), :require => false
gem 'elasticsearch',            :path => File.expand_path("../elasticsearch", __FILE__),            :require => false

gem "pry"
gem "ansi"
gem "shoulda-context"
gem "mocha"
gem "turn"
gem "yard"
gem "ci_reporter", "~> 1.9"

if defined?(RUBY_VERSION) && RUBY_VERSION > '1.9'
  gem "simplecov"
  gem "simplecov-rcov"
  gem "cane"
end

if defined?(RUBY_VERSION) && RUBY_VERSION > '2.2'
  gem "test-unit", '~> 2'
end
