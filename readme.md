# Sirgantmusic.com
A rails locomotive app showcasing Sirgant.

## Viewing Local Site
* ```bundle exec wagon serve``` to launch the front end portion of the site & access at http://0.0.0.0:3333
* ```cd sirgantapp && bundle exec rails g locomotive:install``` to install engine routes. Feel like this shouldn't have to be run every time....
* ```mongod``` to start mongo db
* ``` bundle exec unicorn_rails``` to start the backend rails app
* Site can be viewed at http://localhost:8080/

* If you don't have imagemagick, you should install it (on mac) by ```brew install imagemagick```

## Developing
* To get started, best bet is to follow this [tutorial](http://doc.locomotivecms.com/get-started/create-your-first-site)
