# eocNewsticker: A jQuery newsticker plugin

## Requirements

jQuery 2.2.4 or higher

## Usage

1. Include the provided JS/CSS files

```html
<script src="eoc-newsticker.js"></script>
<link rel="stylesheet" href="eoc-newsticker.css">
```

2. Static or AJAX usage

Write your HTML Content (only for static use)

```html
<div id="example">The quick brown fox jumps over the lazy dog</div>
```

-OR-

```html
<div id="example"></div>
```
Leave the HTML empty and provide a source for AJAX load (see example)

3. Invoke the newsticker on your selected HTML Tag

```javascript
$(function() {
  $("#example").eocNewsticker();
});
```

4. Options

    * speed: The time it takes (in seconds) to move the text 1000px from right to left (normalized)
    * timeout: The time the slider waits after domready, before starting to run
    * divider: The signs used as a divider between the text blocks (if the text is not long enough to fill the whole width)
    * type (static or ajax): Regular usage (static) or get contents with ajax as a json file (ajax)
    * interval: AJAX update interval in seconds

## Future Development

I intend to read the news from a JSON file. Therefore the newsticker will be updated on-the-fly in a constant interval.

## Notice

Please bear in mind, that this project is in a very early stage of development, so please have mercy with me :)

## License

Released under the MIT license - https://opensource.org/licenses/MIT