## TCP/IP model
The TCP/IP (Transmission Control Protocol/ Internet Protocol) is a framework used for network communication and ensures successful data transmission of data. It consists of four layers.

## TCP/IP Protocol Suite Analysis: Loading a Web Page

-Using the TCP/IP as a communication protocol, when you load a web page like https://www.linkedin.com, multiple layers of TCP/IP models come together to ensure that data is transmitted successfilly. Below is an analysis of how the four layers work together;

##1.Network Access Layer
This handles the physical transmission of data over cables and ensures data are sent through the Wi-Fi router or Ethernet cables.

##2. Internet layer
These TCP segments are encapsulated into IP packets containing source IP addresses and destination IP addresses and are forwaarded across multiple networks using the router till they reach the web server.

##3. Transport layer
The request is thereafter broken into segments and sent through TCP for a reliable communication and a connection is formed using the three-way handshake (SYN.SYN-ACK and ACK) to ensure data integrity.
 
##4.  Application layer
When a user enters "https://www.linkein.com" in a web browser, HTTPS is used to request for the web page from the server

Real-World Scenario:

1. Type "https://www.linkedin.com" in your browser
2. The DNS resolves the domain name to an IP address
3. A TCP connection is established with the web server
4. An HTTPS request is sent by the browser to the wepage
5. The web servers sends an HTTPS response to the browser containing the web page content
6. The data received by the broswer is reconstructed and displays it  