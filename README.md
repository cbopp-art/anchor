anchor.js
======

This small but might really useful [jQuery](http://www.jquery.com) Plugin brings in an animation to all native section link and smoothly jumps at an element anywhere on your page.

###Demo
Check out a short example of the anchor.js:<br>
http://jsfiddle.net/psrRQ/4/

###Installation
Just include the `anchor.js` file and also make sure that jQuery is defined. Then, call DOM elements by using your preferred selector like in the example below.

```javascript
<script type="text/javascript" src="path/to/your/anchor.js"></script>
<script type="text/javascript">
$(function () {
    $('a[href*=#]').anchor({
        foo: 'bar'
    });
});
</script>
```
