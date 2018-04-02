# Embiggener
A lightweight jQuery image enlarger

This is a very lightweight (and with that, basic) image viewer in javascript/jQuery.

Installation is just like any other javascript and css files, though be sure to have jQuery.

To Use:
For any image you desire to embiggen, add "enlarge" as a class in the \<img> tag (e.g. <code>\<img class="enlarge" src="sourceimg.jpg"/></code>).

If you wish to enable scrolling on the main page while an image is embiggened, simply delete <code>$('body').css('overflow', 'hidden');</code> and <code>$('body').css('overflow', 'visible');</code> from embiggener.js.
