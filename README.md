## Website Performance Optimization portfolio project - Justin Stout

To run locally, open index.html in your browser. Navigate to the last option or open views/pizza.html to see the pizza page.

To run remotely and measure speed metrics, use a simple HTTP server to host on a port (I used 8080) and then use ngrok to set up a tunnel to an outside URL.

Optimizations to index.html:

Compressed all images

Moved the javascript link to the end of the html to avoid render blocking

Inlined the css to avoid render blocking (maintained an index.dev.html for development but used the inlined index.html for production)

Used an async script to load the google font to avoid render blocking

Optimizations for pizza.html listed in the comments of main.js