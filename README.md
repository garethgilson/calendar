# Calendar

This is a simple calendar with the full year on a single page. Designed to be printed, it will automatically adjust to any paper size or direction (though it looks best in landscape orientation).

By default, the current year is used. You can override the year by supplying a `year` parameter, e.g. `/calendar.php?year=2027`. You can override the starting month by supplying a `month` parameter, e.g. `/calendar.php?month=9`. The parameters can be combined safely, e.g. `/calendar?year=2024?month=9`.

You can also switch to a weekday-aligned rendering by setting the `layout` parameter value to `aligned-weekdays`.

Unabashedly written in PHP.
