source 'https://rubygems.org'

group :test do
  gem 'rake'

  puppetversion = ENV.key?('PUPPET_VERSION') ? "#{ENV['PUPPET_VERSION']}" : ['>= 3.0.0','< 4.0']
  gem 'puppet', puppetversion

  gem 'librarian-puppet'
  gem 'puppetlabs_spec_helper'
end
