# generator-simplesite

A generator for [Yeoman](http://yeoman.io).

### sw-angular

Simple setup to start playing with angular

## Deps

You will need yeoman, grunt and bower. You will also need bourbon and neat.
I prefer to install them manually, rather them from bower.
   
   To get this working, you need node.js and npm installed. 
   You need the following modules:

	  * grunt-contrib-watch
	  * grunt-contrib-compass
	  * grunt-php
	  * grunt-concurrent


These will be automatically installed  for you when you run 'yo simplesite'.
You also need sass and compass installed.

You will need to be running compass

Once you've run 'yo sw-angular', then go into the sass directory and type 'bourbon install' and 'neat install'

## Recent Changes

Project no longer uses the connect task, enabled by 'grunt-contrib-connect'.
We now use 'grunt-php' and 'grunt-concurrent', to run php as a the server,
and concurrently watch for changes.

## License

MIT license
https://github.com/sunilw/generator-simplesite/LICENSE-MIT


