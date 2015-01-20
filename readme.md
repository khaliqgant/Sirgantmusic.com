# Sirgantmusic.com
A rails locomotive app showcasing Sirgant.

## Viewing Local Site
* ```bundle exec wagon serve``` to launch the front end portion of the site & access at http://0.0.0.0:3333
* ```cd sirgantapp && bundle exec rails g locomotive:install``` to install engine routes. Feel like this shouldn't have to be run every time....
* ```mongod``` to start mongo db
* ``` bundle exec unicorn_rails``` to start the backend rails app from sirgantapp
* Site can be viewed at http://localhost:8080/
* Access admin from http://localhost:8080/locomotive


* If you don't have imagemagick, you should install it (on mac) by ```brew install imagemagick```

## Developing
* To get started, best bet is to follow this [tutorial](http://doc.locomotivecms.com/get-started/create-your-first-site)

## Deployment
* [Locomotive](http://doc.locomotivecms.com/get-started/deployment)
* This resource: http://doc.locomotivecms.com/get-started/engine-in-production
* On production, run unicorn from sirgantapp
    ```
    unicorn -c config/unicorn.rb -D
    ```
* Will want to add nginx as well (not sure which is better)
    * http://blog.mccartie.com/2014/08/28/digital-ocean.html
    * http://sirupsen.com/setting-up-unicorn-with-nginx/
