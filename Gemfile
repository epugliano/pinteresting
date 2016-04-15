ruby '2.2.4'
source 'https://rubygems.org'

gem 'rails', '4.2.5'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'jbuilder', '~> 2.0'
gem 'bootstrap-sass', '~> 3.3.6'
gem 'devise'
gem 'aws-sdk', '< 2.0'
gem 'paperclip', :git=> 'https://github.com/thoughtbot/paperclip', :ref => '523bd46c768226893f23889079a7aa9c73b57d68'
gem 'masonry-rails', '~> 0.2.0'
gem 'will_paginate', '~> 3.0.5'
gem 'will_paginate-bootstrap'

group :development, :test do
	gem 'sqlite3'
end

group :production do
	gem 'pg'
	gem 'rails_12factor'
end

group :doc do

	gem 'sdoc', require: false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
