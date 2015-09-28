## Website Performance Optimization portfolio project

Optimizations to index.html:

Compressed all images
Moved the javascript link to the end of the html to avoid render blocking
Inlined the css to avoid render blocking (maintained an index.dev.html for development but used the inlined index.html for production)
Used an async script to load the google font to avoid render blocking

Optimizations for pizza.html listed in the comments of main.js