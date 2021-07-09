source 'https://rubygems.org'
ruby '1.9.3'

gem 'rails', '4.0.0'
gem 'actionpack', '3.2.13' # added b/c google_charts gem isn't being a good citizen in gemspec

gem 'pg'
gem 'foreman'
gem 'thin'

gem 'cancan'
gem 'activeadmin', :git => 'git://github.com/macfanatic/active_admin.git', branch: 'stable_batch_actions'
gem 'sass-rails', '>= 4.0.0'
gem "meta_search",    '>= 1.1.0.pre'

gem 'ckeditor_rails', '>= 4.0.1', :require => 'ckeditor-rails'
gem 'haml'

gem 'paper_trail', '>= 2.6.3'
gem 'stringex'
gem 'settingslogic'

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'rspec-rails', '>= 2.13.0', '>= 2.13.0'
end

# Assets
gem 'carrierwave'
gem 'mini_magick'

# Validation helpers
gem 'spectator-validates_email', :require => 'validates_email'
gem 'date_validator'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'coffee-rails', '~> 4.0.0'
  gem 'uglifier', '>= 1.0.3'
  gem 'therubyracer'
end

gem 'jquery-rails', '>= 2.0.1'

group :test do
  # Pretty printed test output
  gem 'turn', '0.8.2', :require => false
  gem 'rspec-rails'
  gem 'factory_girl_rails', '>= 4.2.1'
  gem 'shoulda-matchers'
  gem 'rake'
  gem 'faker'
  gem 'timecop'
end

# Charting
gem 'google_charts'
