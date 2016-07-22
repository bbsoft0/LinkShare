﻿ruby '2.3.1'
source 'https://rubygems.org'

gem 'bootstrap-sass'
gem 'jquery-rails'
gem 'pg'
gem 'rails', '4.2.0'
gem 'rails_12factor', group: :production
gem 'simple_form'
gem 'sorcery', '0.9.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'validate_url'

# This allows us to import bower packages
source 'https://rails-assets.org' do
  gem 'rails-assets-bootstrap-material-design'
end



group :development, :test do
  # better server logs!
  gem 'quiet_assets'

  gem 'dotenv-rails'

  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'


  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

  gem 'factory_girl_rails'
  gem 'faker'
  gem 'pry'
  gem 'rspec-rails', '~> 3.0' # https://github.com/rspec/rspec-rails
  gem 'rspec_api_documentation' # https://github.com/zipmark/rspec_api_documentation
  gem 'shoulda-matchers'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
end
