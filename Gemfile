source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gem 'rails',      '6.0.2.1'
gem 'bootstrap-sass', '3.4.1'
gem 'puma',       '4.3.1'
gem 'sass-rails', '6.0.0'
gem 'webpacker',  '4.2.2'
gem 'turbolinks', '5.2.1'
gem 'jbuilder',   '2.9.1'
gem 'bootsnap',   '1.4.5', require: false

group :development, :test do
  gem 'sqlite3', '1.4.2'
  gem 'byebug',  '11.0.1', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console',           '4.0.1'
  gem 'listen',                '3.1.5'
  gem 'spring',                '2.1.0'
  gem 'spring-watcher-listen', '2.0.1'
end

group :test do
  gem 'capybara',           '3.29.0'
  gem 'selenium-webdriver', '3.142.6'
  gem 'webdrivers',         '4.1.3'
  gem 'rails-controller-testing', '1.0.4'
  gem 'minitest',                 '5.13.0'
  gem 'minitest-reporters',       '1.4.2'
  gem 'guard',                    '2.16.1'
  gem 'guard-minitest',           '2.4.6'
end

group :production do
  gem 'pg', '1.1.4'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
