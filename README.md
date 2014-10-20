### Gruntfile.js

```js
'use strict';

module.exports = function (grunt) {

  require('load-grunt-tasks')(grunt);
  require('time-grunt')(grunt);

  grunt.initConfig({
  });

  grunt.registerTask('build', [
  ]);

  grunt.registerTask('serve', [
    'build'
  ]);

  grunt.registerTask('default', [
    'build'
  ]);

};
```


### package.json

```js
{
  "name": "project-name",
  "version": "1.0.0",
  "description": "Project Description",
  "homepage": "https://github.com/chrisiona/project-name",
  "devDependencies": {
    "grunt": "^0.4.5",
    "load-grunt-tasks": "^0.6.0",
    "time-grunt": "^1.0.0"
  }
}
```
