source 'https://rubygems.org'

gem 'rails', '3.2.13'
gem 'pg'
gem 'jquery-rails'
gem 'twitter-bootstrap-rails' #run 'rails generate bootstrap:install static' after 'bundle install'
gem 'highlight', :require => 'simplabs/highlight' #run 'rails generate highlight_styles' after 'bundle install', then copy generated css to assets
gem "social-buttons", git: "git://github.com/kristianmandrup/social-buttons.git"

#This section would be needed for Heroku or bundle install won't pass
group :production do
    gem 'uglifier'
    gem 'therubyracer'
end