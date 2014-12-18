angular-touch
=============
base on <a href="https://github.com/angular/bower-angular-touch">bower-angular-touch</a>

and add ng-taphold directive

Add a `<script>` to your `index.html`:

```html                                                                                                                                                                   
<script src="/node_modules/angular-touch/angular-touch.js"></script>                                                                                                      
```

Then add `ngTouch` as a dependency for your app:

```javascript                                                                                                                                                             
angular.module('myApp', ['ngTouch']);
```
