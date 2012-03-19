# jquery shiftClick

A simple to use shift-click library for jQuery to enable shift clicking a la gmail.

## Synopsis

After having used Gmail extensively, it surprised me to find no simple library that does shift click
for me using jQuery. (I saw an unmaintained and 404-errored version from 2008, so that may have been good.)

To see an example of this in action, go to http://axiak.github.com/jquery-shiftclick/src/example.html

Usage synopsis:

```javascript

$("input[type='checkbox']").shiftClick(); // All shiftclick enabled on page

/* By default the library caches the relative ordering, which you'll have to clear with:
   $("foo").shiftClick("clearCache");
   whenever you redraw/reorder the elements on the page.
   To disable the cache completely, specify {"cache": false}.
*/
$("input[type='checkbox']").shiftClick({'cache': false});

```


## License

MIT

## Author

Mike Axiak