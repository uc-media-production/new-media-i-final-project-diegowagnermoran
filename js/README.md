# JavaScript Directory
This directory contains all of the JavaScript files for your website. You can add as many files as you want, but 
make sure to link them to your HTML files. This is _not_ a required directory and you can delete it if you don't 
want/need to use JavaScript.

Below are some code hints that you can use to get started with JavaScript. You can use jQuery or vanilla JavaScript. 
It's up to you.

## Execute Code on Page Load
Below are some examples of how to execute code when the page loads. Either of these examples will work.
```js
window.onload = function() {
  // Do someting when the page loads
}
```

```js
document.addEventListener('DOMContentLoaded', function() {
  // Do someting when the page loads
})
```

If you prefer to use jQuery, you can use the following:

```js
$(document).ready(function() {
  // Do someting when the page loads
})
```

## Selectors
Below are a few ways you can target HTML elements using JavaScript.
  
```js
// Select an element by ID
document.getElementById('some-id')

// Select an element by class
document.getElementsByClassName('some-class')

// Select an element by HTML tag name
document.getElementsByTagName('span')

// Select an element by CSS selector
document.querySelector('span.some-class')
```

If you prefer to use jQuery, you can use the `$` function to select elements.
```js
$('#some-id')
````

## Event Listeners
Event listeners are a great way to execute code when a user interacts with your website. You can attach a "listener" 
to an HTML element that will execute code during a certain event like `click`, `scroll`, `mouseover`, etc.

Below is an example of adding an event listener to an element with the id of `#my-button`.
```js
document.getElementById('my-button').addEventListener('click', function() {
  // Do something when the button is clicked
})
```