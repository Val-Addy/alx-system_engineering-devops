This about What happens when you type google
This question might seem straightforward in our daily lives. A layperson might simply say that if you’re connected to the internet and type “www.google.com" in your browser and press enter, the system connects you to the main Google server, and the Google homepage with its search bar appears on your screen.

However, behind the scenes, several steps are involved to make this happen:

DNS Lookup: The browser first converts the domain name “google.com” into an IP address using the Domain Name System (DNS).

TCP Connection: Once the IP address is obtained, the browser establishes a TCP (Transmission Control Protocol) connection with the server at that IP address, typically using port 80 for HTTP or port 443 for HTTPS.

HTTP Request: The browser sends an HTTP GET request to the server for the Google homepage.

Server Processing: The server processes the request and prepares the content of the Google homepage.

HTTP Response: The server sends back an HTTP response containing the HTML code of the homepage.

Rendering: The browser receives the HTML, parses it, and then fetches additional resources like CSS, JavaScript, and images to fully render the page.

This series of steps results in the display of the Google homepage on your screen, ready for you to use the search bar.
