A sequence diagram depicts a user creating a new note in the text field of a web page. The browser sends a POST request to the server, and the server responds with an HTTP status code 302, indicating a URL redirect to the browser. 
The browser sends GET request to the server.
An updated HTML document with a new note is sent back to the browser. The HTML document reload causes the browser to fetch three more HTTP requests: the CSS file, the JS file, and the JSON file. 
