# Elequent JS Notes - Chapter 13

## Networks and the Internet
A basic computer __network__ is two or more computers connected with each other for the purpose os communicating data electronically. 
- The __Internet__ is a global computer network

A __network protocol__ describes a style of communication over a network such as for sending email, fetching email, sharing files, and browsing websites.
- Hypertext Transfer Protocol (HTTP) is a protocol for retrieving named resources

The Transmission Control Protocol (TCP) is a protocol that helps computers send and receive bits of data to each other. 
- One computer must be waiting, or _listening_, for other computers to start talking to it
- Each listener has a __port__ associated with it to listen for different types of messages
- Most protocols specify port numbers that should be used by default
- Another computer can then establish a connection by connecting to the target machine using the correct port number
- The listening computer is called the __server__
- The connecting computer is called the __client__

## The Web
The __World Wide Web__ is a set of protocols and formats that allow for the visiting of web pages in a browser. Each document on the Web is named by a __Uniform Resource Locator (URL)__, which looks similar to this:
- http://eloquentjavascript.net/13_browser.html 
- {http://} is the protocol
- {eloquentjavascript.net} is the server
- {13_browser.html} is the path to a specific resource 

Machines connected to the internet get and IP address, which is a number that can be used to send messages to that machine. 
- a __domain name__, such as eloquentjavascript.net, is a unique reference to an IP address 

## HTML
Hypertext Markup Language is the document format used for web pages. An HTML document contains text and __tags__ that give structure to the text. 
- The tags (< and >) provide information about the structure of the document. 

HTML documents have a head and a body. The head contains information about the document, and the body contains the document itself. To be able to include angle brackets in the text of a document, another form of special notation has to be introduced.
- A plain opening angle bracket is written as __&lt;__ and a closing bracket is __&gt;__
- An ampersand char followed by a name or char code and a semicolon is called an __entity__ and will be replaced by the char it encodes

