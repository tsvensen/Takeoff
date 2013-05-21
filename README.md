# Takeoff

Automated optimized project development workflow. A tool, introduction and configuration for [Grunt](http://gruntjs.com).

* * *
**GET YOUR PROJECT QUICKLY OFF THE GROUND**
* * *

## Quick Launch

To get up and running, follow these instructions:

1. Download or Clone the repo `git@github.com:tsvensen/Takeoff.git`
2. Open up a terminal window and cd into the project directory
  * Make sure the Grunt command line tools are installed globally, if not run `npm install grunt-cli -g`
3. Enter the following to install: `npm install` *(If there is an error, try `sudo npm install`)*
4. Then run: `grunt watch`
5. To end the `grunt watch` process, press *CTRL-C* in the terminal window. To manually publish with grunt, in the terminal simply run: `grunt`
6. Update the file paths of the last two lines in the `<head>` for icons.fallback.css and lte-ie7.js

Now you are ready for developming and making updates. Do not edit the .css files (/css/processed/), instead update the .scss files (/css/sass/). For Javascript, edit the files in the **js/custom** directory.

This workflow will use grunt to watch the scss and js files for changes then lint/compile them. If there are errors in the code, publishing will fail. Refer to the console for the line number.

### [See the project page for more information and documentation](https://github.io/tsvensen/Takeoff#Takeoff)


## Takeoff Task Reference

* <code>grunt</code> or <code>grunt default</code> to run the default Takeoff task
* <code>grunt watch</code> to automate optimization while building
* <code>grunt cleanup</code> to remove all processed Sass CSS files, run after adding or changing .scss files. Run occasionally and before deploying
* <code>grunt icons</code> to build SVG images with PNG fallbacks
* <code>grunt minify</code> to use Yahoo!'s [SmushIt](http://www.smushit.com/ysmush.it/) service to minify images

* * *
#### Created by [Tim Svensen](http://timsvensen.com) (follow [@tsvensen](https://twitter.com/tsvensen))
* * *

Remember, this is a start. From here you can mold and shape it to fit your approach.


## Legal
Author & copyright (c) 2012: [Tim Svensen](http://timsvensen.com), Dual MIT & GPL license

### Grunt Legal
Copyright (c) 2012 "Cowboy" Ben Alman, contributors Licensed under the MIT license.

[https://github.io/gruntjs/grunt/blob/master/LICENSE-MIT](https://github.io/gruntjs/grunt/blob/master/LICENSE-MIT)
