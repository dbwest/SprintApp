source 'https://rubygems.org'
ruby '1.9.3'

gem 'rails', '6.1.7.3'
gem 'actionpack', '6.1.7.3' # added b/c google_charts gem isn't being a good citizen in gemspec

gem 'pg'
gem 'foreman'
gem 'thin'

gem 'cancan'
gem 'activeadmin', :git => 'git://github.com/macfanatic/active_admin.git', branch: 'stable_batch_actions'
gem 'sass-rails', '>= 5.0.8'
gem "meta_search", ">= 1.1.3"

gem 'ckeditor_rails', '>= 4.0.1', :require => 'ckeditor-rails'
gem 'haml', '>= 5.0.0'

gem 'paper_trail', '>= 2.6.3'
gem 'stringex'
gem 'settingslogic'

group :development do
  gem 'better_errors', '>= 2.8.0'
  gem 'binding_of_caller'
  gem 'rspec-rails'
end

# Assets
gem 'carrierwave', '>= 1.3.2'
gem 'mini_magick', '>= 4.9.4'

# Validation helpers
gem 'spectator-validates_email', :require => 'validates_email'
gem 'date_validator', '>= 0.6.4'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'coffee-rails', '~> 4.2.2'
  gem 'uglifier', '>= 2.7.2'
  gem 'therubyracer'
end

gem 'jquery-rails', '>= 4.4.0'

group :test do
  # Pretty printed test output
  gem 'turn', '0.8.2', :require => false
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'shoulda-matchers'
  gem 'rake', '>= 12.3.3'
  gem 'faker'
  gem 'timecop'
end

# Charting
gem 'google_charts'
