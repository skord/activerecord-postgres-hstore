source "http://rubygems.org"
# Add dependencies required to use your gem here.
gem 'rails'
gem 'rake'

platforms :jruby do
  gem 'activerecord-jdbc-adapter'
  gem 'jdbc-postgres', :require => false
end

platforms :ruby do
  gem 'pg'
end

# Add dependencies to develop your gem here.
# Include everything needed to run rake, tests, features, etc.
group :development, :test do
  gem "shoulda", ">= 0"
  gem "bundler", "~> 1.1.3"
  gem "jeweler", "~> 1.8.3"
  gem "rdoc"
  gem "rspec"
  gem "rcov"
end
