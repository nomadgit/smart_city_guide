source 'https://rubygems.org'

gem 'rails', '3.2.11'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'mysql2'
gem 'forgery'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# social_stream_gems = lambda {
#   gem 'social_stream-base'
#   gem 'social_stream-documents'
#   gem 'social_stream-places'
# }

# # Developing Social Stream
# if ENV['PLACES_DEV']
#   path '../social_stream', &social_stream_gems
# else
#   git 'git://github.com/ging/social_stream.git', &social_stream_gems
# end

git 'git://github.com/ging/social_stream.git', branch: "master" do
  gem 'social_stream-base'
  gem 'social_stream-documents'
  gem 'social_stream-places'
end


# FI-WARE Authentication
gem 'omniauth-fiware'

group :development do
  gem 'rspec-rails', '2.6.1'
  gem 'forgery'
  gem 'meta_request', '~> 0.2.0'
  gem 'debugger'
end

group :test do
  gem 'rspec-rails', '2.6.1'
  gem 'webrat', '0.7.1'
end

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
