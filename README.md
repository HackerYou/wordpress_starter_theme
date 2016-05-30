# HackerYou Starter Theme

This is a simple theme to get you up and running with a new theme in WordPress. 

## Gulp

The theme includes gulp to process your styles and scripts, if you want to use gulp make sure you run `npm install` and `gulp` so that it will watch your files.

If you are on windows and your `localhost` setup does not have `localhost:8888` make sure to change the browser sync task.

```js
gulp.task('bs', function() {
    browserSync.init({
        // if running on windows, change this to http://localhost
        proxy: 'http://localhost:8888'
    });
});
```


