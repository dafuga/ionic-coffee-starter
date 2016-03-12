CoffeeScript Ionic Starter
===

Starting point for developing Ionic apps with coffeescript.



Getting Started
---

Enjoy coffeescript + sass w/ live reloading.

```
npm install
gulp watch
```
In a separate window,
```
ionic serve
```

Coffeescript files in www/coffee will be compiled to JS and concated into www/js/application.js.  Sass files in www/sass will be compiled to CSS and concated into www/css/style.css.

Changes to any files in the project directory will trigger a reload in your browser, complete with your newly concated+compiled sass+coffee files!

Troubleshooting
---

If you get an error on running `gulp watch`, try `npm install -g gulp-cli`.

Credit
---

Most of the credit goes to [StephenGrider](https://github.com/StephenGrider/CoffeeScript-Ionic-Starter), I basically just updated dependencies to make it work for me, but I figured that this might help others.




