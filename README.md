# jquery.rowspanizer.js
Dynamic rowspan based on the content of the table for ADPP

### jQuery

Use the plugin as follows:

```js
$('table').rowspanizer();
```

By default, `vertical-align: top` css style will be added. You can override default by passing the `vertical_align` option:
```js
$('table').rowspanizer({vertical_align: 'middle'});
```

## Notes

* Requires jQuery 1.7+.

## License

This plugin is available under [the MIT license](http://mths.be/mit).
