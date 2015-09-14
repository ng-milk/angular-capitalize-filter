# Angular capitalize filter

### [Quick Demo](http://ng-milk.github.io/angular-capitalize-filter/)
Angular filter that capitalizes each word in a string, read about it on [here](https://ngmilk.rocks/2015/04/03/angularjs-filter-that-capitalizes-each-word-in-a-string/).
CSS is fairly powerful, but it can only capitalize words that aren't uppercase. The `text-transform:capitalize` property won't change anything in a string like **CAN'T GET ME CSS**. Use this directive to achieve consistent capitalization of each word in a given string.

## Usage
1. Include `ng-capitalize.js`.
2. Add `dm.capitalize` as a dependency to your app.
3. Profit!


## Bower
Installable via `bower`:

```bash
bower install ng-capitalize
```

## Example
See [index.html](https://github.com/ng-milk/angular-capitalize-filter/blob/master/index.html) for an example.

```html
  <script>
    angular.module('app', ['dm.capitalize']);
  </script>

  <ul ng-app="app">
    <li>{{'MOUNTAIN' | capitalize}}</li> <!-- Mountain -->
    <li>{{'MOUNTAIN DOOM' | capitalize}}</li> <!-- Mountain Doom -->
  </ul>
```

## About ngmilk
<img src="http://ngmilk.rocks/content/images/2014/10/111-1.jpg" width="200px"/>

**ngmilk** is the place to go for fresh front-end articles, with a focus on AngularJS.
See more on [ngmilk.rocks](https://ngmilk.rocks)

Follow [@ngmilkrocks](http://twitter.com/ngmilkrocks) on Twitter to stay ahead of the game.

