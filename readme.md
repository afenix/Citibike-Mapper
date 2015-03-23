
Citibike App
========

A simple sinatra app that uses citibike json data, the leaflet api, ruby and javascript to allow users to choose start and ending points from dropdown lists and then see those locations on a map.  Special thanks to Flatiron school for the tutorial and ashleygwilliams for hosting the tutorials repo.      

Installation
------------

First clone the repository.  
```
$ git clone http://github.com/afenix/citibike-mapper
```

Install all of the required gems:
```
$ gem pry
$ gem rspec
$ gem pg
$ gem sinatra
$ gem sinatra-contrib
$ bundle install
```

Install and start PostGres on system
```
$ brew install postgres
echo "export PGDATA=/usr/local/var/postgres" >> ~/.bash_profile
echo "export PGHOST=/tmp" >> ~/.bash_profile
source ~/.bash_profile

To start the Postgres server, simply run:
`code()`
postgres

````
Start the webserver:

````
$ ruby app.rb
```

In your web browser, go to http://localhost:4567

Contribute
----------
```
- Issue Tracker: github.com/afenix/citibike-mapper
/issues
- Source Code: github.com/afenix/citibike-mapper
```
Support
-------

This app is a work in progress.  By no means is it complete. However, if you are having issues, please let me know at: a.fenix@icloud.com

Author
---------
Alister A. Fenix, 2015

License
---------

Free and OS License. Code for the people by the people. 2015 Alister Fenix

---------

If you would like to create your own sinatra based, leaflet app, follow these instructions(taken directly from the initial tutorial): 

Get up and running
1. fork and then clone this repo: [https://github.com/ashleygwilliams/citibike-sinatra](https://github.com/ashleygwilliams/citibike-sinatra)
2. `bundle install`
3. `bundle exec shotgun`
4. `localhost:9393`

Once you clone the above code, follow the readme instructions.
