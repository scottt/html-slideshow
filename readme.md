# Use [html-slideshow](https://github.com/robflaherty/html-slideshow) on dynamically generated content
Hacks [html-slideshow](https://github.com/robflaherty/html-slideshow) for use with Javascript generated DOM content.
Originally written to integrate html-slideshow with a Javascript based wiki such as creole.js

# Usage
    <script src="resources/htmlSlides.js"></script>
    <script>
    /* ... modify DOM with Javascript ... */
    slider.init({ hideMenu: true });
    </script>
