# UNMAINTAINED















heroku-badges
==================
[![Build Status](https://travis-ci.org/welcoMattic/heroku-badges.svg?branch=master)](https://travis-ci.org/welcoMattic/heroku-badges)
[![Dependencies](https://david-dm.org/welcoMattic/heroku-badges.png)](https://david-dm.org/welcoMattic/heroku-badge)
[![Heroku](http://heroku-badges.herokuapp.com/?app=heroku-badges)](http://heroku-badges.herokuapp.com/projects.html)

##Usage

Create an `img` with src `https://heroku-badges.herokuapp.com/?app={app-name}`. E.g.,

HTML:

    <img src="https://heroku-badges.herokuapp.com/?app=heroku-badges" />

Markdown:

    [![Heroku](https://herok-badges.herokuapp.com/?app=heroku-badges)]


If the heroku app has no index.html than use the root query parameter to specify the url to check if heroku response with http status 200.

HTML:

    <img src="http://heroku-badges.herokuapp.com/?app=heroku-badges&root=products-e2e.html" />

Markdown:

    [![Heroku](http://heroku-badges.herokuapp.com/?app=heroku-badges&root=products-e2e.html)]

##Todo

+ [ ] configurable heroku check url
+ [x] add flat badges

##Copyright

The badges are made by me but feel free to use and copy it of course you have to copy it into your heroku app.

License
--------------

heroku-badges is released under the [MIT License](http://opensource.org/licenses/MIT).
