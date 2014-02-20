*This repository is a mirror of the [component](http://component.io) module [component/once](http://github.com/component/once). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-once`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# once

  Make a function or method callable only once. Useful for initialization methods
  that may be lazily invoked from several locations, but must only be called once,
  otherwise the method is a noop.

## Installation

    $ component install component/once

## API

```js
var once = require('once');

Foo.prototype.setup = once(function(){
  // expensive stuff here
});
```

## License

  MIT
