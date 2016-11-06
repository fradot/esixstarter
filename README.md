[![Build Status](https://travis-ci.org/fradot/esixstarter.svg?branch=master)](https://travis-ci.org/fradot/esixstarter)   [![devDependencies Status](https://david-dm.org/fradot/esixstarter/dev-status.svg)](https://david-dm.org/fradot/esixstarter?type=dev)

# Javascript ES6 ready frontend starter template

esixstarter is a simple front-end starter template for building javascript applications using ECMAScript6 features.

## Features:

- TDD-ready environment.
- ECMAScript6 support.
- CSS & Javascript source map.
- Livereload! Browser automatically refresh on changes.
- LESS support.   
- Javascript & CSS minification.
- Javascript linting.
- CSS Autoprefixer.
- <a href="https://github.com/fradot/esixstarter/blob/master/LICENSE.txt">MIT License</a>

## Quick Start
1. Download the zip project <a href="https://github.com/fradot/esixstarter/archive/master.zip">here</a>

2. Or clone this git repo: <pre><code>git clone https://github.com/fradot/esixstarter.git</code></pre>

##### Configure your project
Configure your project using the esixstarter-config.json file:

<pre><code>
{
  "name": "-your project name-",
  "description": "-your project description goes here-",
  "dirs": {
      "test": "test",
      "dist": "dist",
      "src": "src"
    },
  "version": "1.0.0",
  "author" : "-author fullname-"
}
</code></pre>

##### Install dependencies & Start developing

Install project dependencies from command line:
<pre><code>npm install</code></pre>

Run gulp command and start developing:
<pre><code>gulp</code></pre>

By default gulp will start a new web server at http://localhost:8080 and karma for test execution.

Javascript code will be transpiled to EcmaScript5. All js files will be minified and included in dist/js/main.js.

Enable javascript **source maps** in your browser to easily debug your application.

##### Build project
Build your project using the build command:
<pre><code>gulp build</code></pre>

The above command will produce a 'dist' folder.
