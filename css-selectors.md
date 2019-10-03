# CSS Selectors

[Source](https://www.learndatasci.com/tutorials/ultimate-guide-web-scraping-w-python-requests-and-beautifulsoup/)

With beautifulsoup4, we can use the `select_one()` function to extract data from an HTML document.

1. To get a tag, such as `<a></a>`, `<body></body>`, use the naked name for the tag. E.g. `select_one('a')` gets an anchor/link element, `select_one('body')` gets the body element

1. `.temp` gets an element with a class of `temp`, E.g. to get `<a class="temp"></a>` use `select_one('.temp')`

1. `#temp` gets an element with an id of `temp`, E.g. to get `<a id="temp"></a>` use `select_one('#temp')`

1. `.temp.example` gets an element with both classes `temp` and `example`, E.g. to get `<a class="temp example"></a>` use `select_one('.temp.example')`

1. `.temp` a gets an anchor element nested inside of a parent element with class `temp`, E.g. to get `<div class="temp"><a></a></div>` use `select_one('.temp a')`. Note the space between `.temp` and `a`.

1. `.temp` `.example` gets an element with class `example` nested inside of a parent element with class `temp`, E.g. to get `<div class="temp"><a class="example"></a></div>` use `select_one('.temp .example')`. Again, note the space between `.temp` and `.example`. The space tells the selector that the class after the space is a child of the class before the space.

1. ids, such as `<a id=one></a>`, are unique so you can usually use the id selector by itself to get the right element. No need to do nested selectors when using ids.
