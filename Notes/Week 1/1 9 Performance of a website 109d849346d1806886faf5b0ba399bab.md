# 1.9 Performance of a website

Created: September 22, 2024 4:58 PM
Class: Modern App Developement 1
Week: Week 1

# Latency

Time at which request was sent - time at which response was received.

Speed of data transfer can be a limiting factor on the performance.

If time taken for data to go one way between client and server is 10ms and we want to wait for response before sending another request we’ll need to wait 20ms every time, that means we are limited to 50 requests/second.

# Response size

If for every response we need to send 1kb of data and we have a 100mbps(10MB/s) connection we are limited to 10k requests/second. Exceed that and the server will crash.

The google home page itself is 144kb of text, that’s the amount of data that needs to be sent every time someone requests google.com

Google search (google.com) receives approx 60k requests per second (data is a few years old, it has to be higher today). 

60,000 x 144kb = 8,640,000kbps = 8.6gbps = 8GB/s

# Memory

The python server we ran in the last lesson consumed about 6mb of memory.

# Storage

Server storage is also a major limiting factor, google search indexing alone takes 100 Petabytes of storage.