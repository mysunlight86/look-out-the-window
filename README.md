# Look-out-the-window

Laptop version of the site: "Look-out-the-window".

View website [https://mysunlight86.github.io/look-out-the-window/](https://mysunlight86.github.io/look-out-the-window/).

## Task

In this project work, I had to write CSS for a working application. At the beginning of the repository, I received many ready-made files: all HTML markup, CSS for preloader components and output errors, font files and styles for them, a file with a script with the described logic of the application. My task was to supplement the style.css file so that [a layout](https://www.figma.com/file/QHcvX1RsUI89CulRB7HLk6/%234-%D0%9F%D0%BE%D1%81%D0%BC%D0%BE%D1%82%D1%80%D0%B8-%D0%B2-%D0%BE%D0%BA%D0%BD%D0%BE?node-id=0%3A1&t=tJOMMSaw5EIu481X-1) would appear in the application interface.

## Functionality

When you open a page from a template, you will see loaded videos and even be able to search. Here is a brief description of the application's functionality:
- When the page loads, the script receives data from an external source, draws five cards with videos and a button to load additional cards. It also substitutes the address of the first of the loaded videos into the `<video>` tag inside a large block on the page.
- The script tracks clicks on cards and switches the current video depending on the selected card.
- The script also monitors the form submission. After submission, it searches the database for matches based on the entered parameters and redraws the page with the data received from the new request.
- In case of errors, a block with an error message is substituted in place of the video block. And while the search is in progress, preloaders are substituted in the blocks with videos and cards, displaying an animation of the loading process.
