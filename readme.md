Grunt init template generator.

Boilerplate to generate grunt init plugins that will generate grunt projects.

This work is based in [Backbone Boilerplate framework tool](https://github.com/backbone-boilerplate/grunt-bbb) from [Tim Branyen](https://github.com/tbranyen)

## Getting Started ##

#### Install this [Grunt](https://github.com/cowboy/grunt) plugin with: ####
``` bash
$ npm install -g grunt-init-plugin
```


#### Create a new grunt init template ####

###### In an empty dir /my_grunt_init_plugin run ######
``` bash
$ grunt-init-plugin init
```
###### Answer some questions #######


#### To run in development environment ####

###### Add files to template root folder ######
``` bash
$ /tasks/init/[plugin-name]/root
```

###### In your plugin folder /my_grunt_init_plugin run ######
``` bash
$ npm install -g
```

###### In an empty dir /test_my_grunt_init_plugin run ######
``` bash
$ [plugin-name] init
```

#### Need Help? ####

Open an issue or contact me


## Release History ##

2012/09/13 - v0.1.1 - Added globalstrict: true int grunt.js template file. Getting Started updated

2012/09/13 - v0.1.0 - Initial release


## License
Copyright (c) 2012 Rodrigo Valerio [@rsvalerio](http://twitter.com/rsvalerio)
Licensed under the MIT license.