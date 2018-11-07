# My Own SASS Boilerplate

A tool that helps to build UI projects using SASS preprocessor.

#### Features
-  SASS: The CSS preprocessor. [SASS Lang](https://sass-lang.com/) 
-  Bourbon.js: Bourbon is a framework library of pure Sass mixins and functions that are designed to make you a more efficient style sheet author. [Bourbon.io](https://www.bourbon.io/) 
-  Susy: Responsive layout toolkit for Sass. [Susy for SASS](http://oddbird.net/susy/) 
-  Normalize CSS: Normalize.css makes browsers render all elements more consistently and in line with modern standards. [Normalize CSS](https://necolas.github.io/normalize.css/) 
-  Grunt.js: A Javascript tasks runner. [Grunt.js](https://gruntjs.com/) 
-  Bower.js: A package manager for the web. [Bower.io](http://oddbird.net/susy/) 

#### Developer dependencies in package.json

  - "grunt": "^1.0.3"
  - "grunt-contrib-watch": "^1.1.0"
  - "grunt-sass": "^3.0.2"
  - "load-grunt-tasks": "^4.0.0"
  - "node-sass": "^4.10.0"
  - "jquery": "^3.3.1"
  - "grunt-contrib-uglify": "^4.0.0"
 
#### Developer dependencies in bower.json

  - "bourbon": "^5.1.0"
  - "susy": "^3.0.5"
  - "normalize-css": "^8.0.1"

#### How to install

It requires [Node.js](https://nodejs.org/) v8.10+ and [Node Package Manager - NPM ](https://www.npmjs.com/) v3.5+ to run.

Download this repository and install the dependencies and devDependencies:

```sh
$ cd sass-boilerplate
$ sudo npm install 
```

Install CLI for SASS:

```sh
npm install -g sass
```

Install CLI for Bower:

```sh
sudo npm install -g bower
```

Install Bower dependencies:

```sh
$ cd sass-boilerplate
$ bower install 
```
Install CLI for GRUNT:

```sh
sudo npm install -g grunt-cli
```

#### GRUNT tasks in gruntfile.js

- Grunt Sass: Compile Sass to CSS using node-sass
- Grunt Contrib Uglify: Minify JavaScript files
- Grunt Contrib Watch: Monitor files and execute tasks

#### Running GRUNT

```sh
$ cd sass-boilerplate
$ grunt 
```
Running a specific task:

```sh
$ cd sass-boilerplate
$ grunt sass
```

Monitor files and execute task:

```sh
$ cd sass-boilerplate
$ grunt watch
```

License
----

MIT

**Free Software, Hell Yeah!**

