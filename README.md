ruby-getting-started

This application is a barebones Rails app that supports Ruby on Heroku.


Running Locally

Make sure you have Ruby installed.  Also, install the Heroku Toolbelt.

$ git clone git@github.com:heroku/ruby-getting-started.git
$ cd ruby-getting-started
$ bundle install
$ bundle exec rake db:create db:migrate
$ heroku local
Your app should now be running on localhost:5000.


Deploying to Heroku

$ heroku create
$ git push heroku master
$ heroku run rake db:migrate
$ heroku open
