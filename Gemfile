source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.0.1'
gem 'sqlite3'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'carrierwave', '~> 1.0'
gem 'devise', '~> 4.2', '>= 4.2.1'
gem 'bootstrap-sass', '~> 3.3', '>= 3.3.7'
gem 'selectize-rails', '~> 0.12.4'
gem 'font-awesome-rails', '~> 4.7', '>= 4.7.0.1'
gem 'wysiwyg-rails', '~> 2.5', '>= 2.5.1'

group :development, :test do
  gem 'byebug', platform: :mri
end

group :development do
  gem 'web-console', '>= 3.3.0'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
