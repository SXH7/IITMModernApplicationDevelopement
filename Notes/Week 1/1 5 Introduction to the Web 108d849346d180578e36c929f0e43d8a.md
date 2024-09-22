# 1.5 Introduction to the Web.

Created: September 21, 2024 5:28 PM
Class: Modern App Developement 1
Week: Week 1

# Why the web?

Web is platform independent, we can think of it as a cross platform Operating System.

Web is built on sound principles and we need to know what we can and cannot do on a web based app.

# Background

There existed many different networks, many universities had their own networks but they all had different formats and worked in different ways so they couldn’t talk to each other.

## Protocol

A protocol is a set of rules that a network follows, at that time each network had their own unique protocol. A protocol consists of rules on things like how to format protocols, what kind of data formatting to use, what kind of header information, etc.

## Inter Network

An inter network protocol would be a higher level protocol allowing different network following different protocols to communicate with each other.

### Internet Protocol (IP)

This protocol decided on what header to use, what packet types to use and how to interpret the data. This turned into the standard from December 1983.

### Transmission Control Protocol (TCP)

TCP made data transfer a two step process, “a” will not just fire data at “b” hoping it reaches it’s destination, “b” will also have to send a confirmation message to close the loop. TCP and IP work hand in hand.

### Domain Names

In the earlier days, to communicate using IP we needed to know the machines IP address, which was not very convenient. Domain names used names instead of IP.

### Hyper Text

Text itself is raw data. With hypertext we can embed instructions on how to interpret that text.

# World Wide Web

The web is basically a collection of a huge number of servers each of which have documents that can be “served”. Each of them their own way of formatting that document, how to display the page, hyperlinks. This connection to each other is what makes the web. 

### How is the web different from the internet?

Internet is a connection of servers, web is a connection of different “documents”.

Originally the web was limited to static pages, limited styling and there were a lot of browser compatibility issue (every browser did things their own way).

### Web 2.0 (started from 2004)

- Dynamic pages.
- HTTP is just a transport mechanism.
- Client sided processing and rendering.
- Changes were made to HTTP which made it so that websites could easily make dynamic pages and the server could keep track of users. Servers are no longer just serving files, they are computing and generating information needed.
- Browsers started getting more powerful because computation power increased.
- This is where the platform independence truly started.