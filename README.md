# New Project Name

This project utilizes grunt.js and Sass as a workflow solution for creating optimized websites. To get up and running, follow these instructions:

1. Download or Clone the repo `git@github.com:*user*/*project-name*.git`
2. Open up a terminal window and cd into the project directory
3. Enter the following to install: `npm install` *(If there is an error, try `sudo npm install`)*
4. Then run: `grunt watch`
5. To end the `grunt watch` process, press *CTRL-C* in the terminal window. To manually publish with grunt, in the terminal simply run: `grunt`

Now you are ready for developming and making updates. Do not edit the .css files (/css/processed/), instead update the .scss files (/css/sass/). For Javascript, edit the files in the **js/custom** directory.

This workflow will use grunt to watch the scss and js files for changes then lint/compile them. If there are errors in the code, publishing will fail. Refer to the console for the line number.


## Grunt Task Reference

* <code>grunt</code> or <code>grunt default</code> to manually publish the project
* <code>grunt watch</code> to automate optimization while building
* <code>grunt cleanup</code> to remove all processed Sass CSS files, run after adding or changing .scss files. Run occasionally and before deploying
* <code>grunt icons</code> to build SVG images with PNG fallbacks
* <code>grunt minify</code> to use Yahoo!'s [SmushIt](http://www.smushit.com/ysmush.it/) service to minify images
