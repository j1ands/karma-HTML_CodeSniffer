# karma-HTML_CodeSniffer

> Adapter for the HTML_CodeSniffer script

## Installation

The easiest way is to keep `karma-html_codesniffer` as a devDependency in your `package.json`.
```json
{
  "devDependencies": {
    "karma-html_codesniffer": "~1.0.0"
  }
}
```

You can simple do it by:
```bash
npm install karma-html_codesniffer --save-dev
```

Instructions on how to install `karma` can be found [here.](http://karma-runner.github.io/0.12/intro/installation.html)

## Configuration
Following code shows the default configuration...
```js
// karma.conf.js
module.exports = function(config) {
  config.set({
    frameworks: ['html_codesniffer'],

    files: [
      '*.js'
    ]
  });
};
```

----

For more information on Karma see the [homepage].


[homepage]: http://karma-runner.github.com