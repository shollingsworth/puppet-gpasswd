source 'https://rubygems.org'

group :development, :test do
  gem 'puppetlabs_spec_helper', :require => false
  gem 'rspec-system-puppet', '~>2.0'
  gem 'puppet-lint'
  gem 'puppet-blacksmith',  '> 3.0'
  gem 'metadata-json-lint'
end

if puppetversion = ENV['PUPPET_GEM_VERSION']
  gem 'puppet', puppetversion, :require => false
else
  gem 'puppet', :require => false
end
