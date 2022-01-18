source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.3'

# rails
gem 'rails', '~> 7.0.1'

# core
gem 'bootsnap', require: false
gem 'jbuilder'
gem 'pg'
gem 'puma', '~> 5.0'
gem 'redis', '~> 4.0'

# assets
gem 'importmap-rails'
gem 'sprockets-rails'
gem 'stimulus-rails'
gem 'turbo-rails'

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem 'debug', platforms: %i[ mri mingw x64_mingw ]
  gem 'rspec-rails'
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem 'web-console'

  # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem 'rack-mini-profiler'

  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  gem 'spring'
end

group :test do
  gem 'factory_bot_rails'
  gem 'shoulda-matchers'
end
