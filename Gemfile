###############################################################################
# The gem versions in this configuration are able to run all CouchDB tests using
# Ruby 1.8.7 p330. (Latest 1.8.7 Ruby version as of testing).
#
# Couch Potato 0.3.1 to 0.4.1 (latest as of testing) breaks the Couch DB unit tests.
# Ruby 1.9.2 p136 (latest as of testing) also breaks the Couch DB unit tests.  I did not try earlier versions.
#
# I don't use SimpleDB, so I cannot comment on whether this configuration is able to run the SimpleDB tests.
###############################################################################

source 'http://rubygems.org'

gem 'rails', '3.0.4'
# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'couch_potato', '0.3.0'
gem 'right_aws', '2.0.0'
gem 'json', '1.5.1'
gem 'uuidtools', '2.1.2'
gem 'mattmatt-validatable'

# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
group :development, :test do
  gem 'jeweler', '1.5.2'
  gem 'shoulda', '2.11.3'
  gem 'mocha', '0.9.12'
  gem 'test-unit', '2.2.0'

  # To use debugger (ruby-debug for Ruby 1.8.7+, ruby-debug19 for Ruby 1.9.2+)
  # gem 'ruby-debug'
  # gem 'ruby-debug19'
end
