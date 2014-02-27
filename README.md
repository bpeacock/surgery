New Library
===========

Usage
-----

Installation: `npm install`

```javascript
function myFunction() {
    surgery({
        'routeRegex [RegEx], callback [function]': function() {

        },
        'routeName [string], callback=noop [function]': function() {

        },
        'callback [function]': function() {
            
        },
        'config [object]': function() {

        }
    })(arguments);
}
```

Development
-----------

To Build: `grunt build`

To Develop: `grunt watch`

To Test: `npm test`
