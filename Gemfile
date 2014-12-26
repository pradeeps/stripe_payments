source 'https://rubygems.org'

ruby '2.1.5'

gem 'rails', '4.1.8'
gem 'sass-rails', '~> 4.0.3'
gem 'bootstrap-sass'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'stripe', :git => 'https://github.com/stripe/stripe-ruby'
gem "figaro"
gem 'activeadmin', github: 'gregbell/active_admin'
gem 'devise'

group :development do
	gem "letter_opener"
end

group :development, :test do 
	gem 'sqlite3'
	gem 'spring'
end

group :production do 
	gem 'rails_12factor'
	gem 'pg'
end

group :sdoc do 
	gem 'sdoc', '~> 0.4.0'
end

