ruby '2.5.0'
source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.0.7'
gem 'pg'
gem 'puma', '~> 3.0'
gem 'devise'
gem 'factory_bot_rails'
gem 'faker', :git => 'https://github.com/stympy/faker.git', :branch => 'master'
gem 'scout_apm'
gem 'simple_token_authentication', '~> 1.0'
gem 'active_model_serializers'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'rails_admin', '~> 1.3'

group :development, :test do
  gem 'byebug', platform: :mri
  gem 'rspec-rails', '~> 3.7'
  gem 'database_cleaner'
end

group :development do
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end
