# Web Foundations Lab

## Student
Name: COMFORTSHALOM.N
Student Number: B34763

## Course
CSC1202 Web & Mobile Application Development

## Project Purpose
This project demonstrates the development workflow covered during the first three lessons.
The project demonstrates:
- basic project organisation
- HTML
- terminal commands
- Git version control
- GitHub
- Internet and Web concepts
- client/server communication
- DNS and HTTP concepts

## How to Run the Project
1. Download or clone the repository.
2. Open the project folder.
3. Open index.html using a modern web browser.

## What I Have Learned
During the first three lessons, I discovered how the World Wide Web utilizes the physical infrastructure of the Internet to transmit data. I learned that web browsers function as clients that make requests, while web servers process those requests and deliver resources back. Additionally, I learned how to use Git version control to create incremental, meaningful snapshots of my source code.



## Internet Investigation

### Question 1
What domain name did I test?
Answer: google.com

### Question 2
What IP address was returned?
Answer: 142.250.74.46

### Question 3
What does DNS do?
Answer: DNS (Domain Name System) acts like an internet phonebook. It translates human-readable domain names (like google.com) into machine-readable IP addresses so the browser can locate the correct hosting server.

### Question 4
What does ping help us test?
Answer: The ping command helps test network connectivity between a local computer and a remote host. It checks if the server is active and measures the round-trip time it takes for data packets to travel back and forth.

## Browser Request Trace

1. **User enters a URL**: The user inputs a web address (e.g., https://example.com) into the browser address bar.
2. **Browser acts as the client**: The web browser initiates a digital request for data resources from a hosting system.
3. **DNS lookup occurs**: The client contacts a DNS server to convert the domain name into a physical numerical IP address.
4. **Browser contacts the server**: The browser establishes a connection with the specific web server matching that IP address.
5. **HTTP/HTTPS request is sent**: A request message (like GET /) is sent requesting the webpage files securely.
6. **Server sends a response**: The web server processes the request and sends back a response containing the HTML, CSS, or media assets.
7. **Browser renders the page**: The browser parses the received files and visually builds the layout for the user.



USER
 | enters URL
 v
BROWSER / CLIENT
 | DNS lookup
 v
DNS SERVER
 | returns IP address
 v
BROWSER
 | HTTP/HTTPS request
 v
WEB SERVER
 | HTTP response
 v
BROWSER
 | renders HTML
 v
USER SEES WEB PAGE
