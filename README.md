
Week - 1 Assignment:
----------------------------------------------------------------------------------------------------------------------------------------




What is the main functionality of the browser?.
---------------------------------------------------

The browser checks the cache for a DNS record to find the corresponding IP address of desired URL.
DNS(Domain Name System) is a database that maintains the name of the website (URL) and the particular IP address it links to. Every single URL on the internet has a unique IP address assigned to it. The IP address belongs to the computer which hosts the server of the website we are requesting to access
The primary purpose of DNS is human-friendly navigation. Makes life easier by not having to remember the IP of everything
If the requested URL is not in the cache, ISP’s DNS server initiates a DNS query to find the IP address of the server that hosts
The purpose of a DNS query is to search multiple DNS servers on the internet until it finds the correct IP address for the website
The browser initiates a TCP connection with the server.
Once the browser receives the correct IP address, it will build a connection with the server that matches the IP address to transfer information. Browsers use internet protocols to build such connections. There are several different internet protocols that can be used, but TCP is the most common protocol used for many types of HTTP requests.
The browser sends an HTTP request to the webserver.
broswer usually makes an API request for the same
The server handles the request and sends back a HTTP response.
The browser displays the HTML content (for HTML responses, which is the most common)
