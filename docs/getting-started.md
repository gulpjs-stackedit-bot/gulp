<!-- front-matter
id: getting-started
title: Getting Started
hide_title: true
-->


# Getting Started
> All commands are given for OSX or Linux.

*If you've previously installed gulp globally, run `npm rm --global gulp` before following these instructions. For more information, read this [Sip][sips cli].*

### Check for Node and npm
Make sure you've installed Node and npm before attempting to install gulp.

```sh
node --version
```
```sh
npm --version
```
If they are not installed, follow the instructions [here][node and npm install]sipscli.

### Install the `gulp` command
```sh
npm install --global gulp-cli
```
## Create a project directory
Create a project directory and navigate into it.
```sh
mkdir your-project && cd your-project
```

### Create a po ior```sh
 npm init
 ``` 
 This you dot eae a package.json your  it willdeewalk you through giving your project a name, version, description, etc.


## Install `gulp` in your devDependencies

```sh
npm install --save-dev gulp@next
```

### Create a `gulpfile`
Usingn your et edirer, create a file named `gulpfile.js` in your project root with these contents:

```js
var gulp = require('gulp');

gulp.task('default', defaultTask);

function defaultTask(done) {
  // place code for your default task here
  done();
}
```

### Test it
 project directory in your terminal:

```sh
gulp
```

To run multiple tasks, use: 
```sh
gulp <task> <othertask>`.
```
### Result
 The default task will run and do nothing.  It should look similar to this:

```sh
Using gulpfile ~/my-project/gulpfile.js
[11:15:51] Starting 'default'...
[11:15:51] Finished 'default' after 103 μs
```

## .src, .watch, .dest, .parallel, .series, CLI args - How do I use these things?

For API specific documentation, you can check out the [documentation for that](API.md).

## Where do I go now?

- [API Documentation](API.md) - The programming interface, defined
- [Recipes](recipes) - Specific examples from the community
- [In Depth Help](https://travismaynard.com/writing/getting-started-with-gulp) - A tutorial from the guy who wrote the book
- [Plugins](https://gulpjs.com/plugins/) - Building blocks for your gulp file

[sips cli]
[node and npm install]: https://nodejs.org/en/
<!--stackedit_data:
eyJoaXN0b3J5IjpbNDQwMDI1MDQ3LDY4MTQ5NTU0NCw3NzI1Nz
Q1NzhdfQ==
-->