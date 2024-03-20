**0.4: New Note Diagram**
A sequence diagram that depicts a user creating a new note in the text field of a web page. The browser sends a POST request to the server, and the server responds with an HTTP status code 302, indicating a URL redirect to the browser. 
Then, the browser sends a GET request to the server.
An updated HTML document with a new note is sent back to the browser. The HTML document reload causes the browser to fetch three more HTTP requests: the CSS file, the JS file, and the JSON file. 

<a href="https://www.mermaidchart.com/app/projects/d1e1c663-04e7-4f52-9d11-a6058caba3b0/diagrams/ab514df6-6aac-4f4a-8087-471a4697154a/version/v0.1/edit" target="_blank"> New Note Diagram Link </a>


**0.5: Single Page App Diagram**
A sequence diagram that depicts a user navigating to a single-page app. The browser sends a GET request to the server, and the server responds by sending an HTML document with script tags. The browser executes the javascript and fetches the notes.
The server reverts to the browser with a JSON file. The browser renders notes with DOM-API.

<a href="https://www.mermaidchart.com/app/projects/d1e1c663-04e7-4f52-9d11-a6058caba3b0/diagrams/465dddbe-cdfc-4f6f-9a61-0d97f82ad239/version/v0.1/edit">Single Page App Link</a>
