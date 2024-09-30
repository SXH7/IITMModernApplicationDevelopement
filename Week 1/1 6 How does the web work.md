# 1.6 How does the web work?

Created: September 22, 2024 3:32 PM
Class: Modern App Developement 1
Week: Week 1

# Web Server

Any computer that has an internet connection can act as a web server.
We just need a software that can listen to incoming network connections on a fixed port and respond accordingly. The incoming connection will have a header which specifies which port it wants to connect to.

At the most basic level, a server needs to listen for requests, find out what the client wants (a file in this instance) and then send it. The OS handles things like opening and closing ports, the more basic stuff.

The protocol specifies what the request is, what kind of responses are acceptable and other relevant stuff. 
The part that says how the communication between client and server should go is the Hyper Text Transfer Protocol (HTTP)

# HTTP

## Hyper Text

Hyper Text is regular text documents that just have certain codes inside it that provide instructions on how to do certain things (like formatting, redirecting to other documents) as long as there is something to interpret it.

## Hyper Text Transfer Protocol

Simple, mostly text based protocol. Client sends request, server responds with a Hyper Text document.