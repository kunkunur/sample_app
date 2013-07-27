source 'http://rubygems.org'

gem 'rails'

platform :jruby do
  gem "jdbc-sqlite3", "~> 3.7.2.1"
  gem 'activerecord-jdbcsqlite3-adapter'
  gem 'therubyrhino'
  gem 'jruby-openssl'
  gem 'trinidad', :require => false
end


group :development do
  gem 'rspec-rails', '2.6.1'
  gem 'annotate', '2.4.0'
end

group :test do
  gem 'rspec-rails', '2.6.1'
  gem 'webrat', '0.7.1'
  gem 'autotest', '4.4.6'
  gem 'autotest-rails-pure', '4.1.2'
  gem 'autotest-notification', '2.3.3'
  gem 'ZenTest', '4.6.2'
  
  # gem 'autotest-fsevent', '0.2.4'
  # gem 'autotest-growl', '0.2.16'
end
