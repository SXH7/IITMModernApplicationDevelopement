# 1.8 What is a protocol?

Created: September 22, 2024 4:21 PM
Class: Modern App Developement 1
Week: Week 1

# What is a protocol?

A protocol means basic rules that are to be followed by both sides of a communication to talk to each other.
If there was no protocol and we opened a port and start typing text while the other side is expecting images we’ll get nowhere.

- Server expects requests
    - Nature of requests.
    - Nature of client.
    - Expected results.
- Client expects response
    - Ask server for something.
    - Relay expected response.
    - Read and process result.

## HTTP

- Primarily text based.
- Requests are “GET”, “POST”, “PUT”, etc
    - Headers convey information about message in text, like status codes, information about client, user agent.
    - GET is used for simple requests which just asks for information and takes back data.
    - POST is used for more complex data, large text blocks, files, etc.
    - Other requests like PUT, DELETE, etc.
        - Used very rarely in web 1.0
        - Used heavily in web 2.0
        - Basics of APIs

# Python web server

Running this in the terminal starts a python web server (replace with python3 on linux).

```bash
python -m http.server
```

To view the output just enter “http://localhost:8000” on a browser. 8000 is the default port.

The output will be a directory listing of everything in directory the command was run from. 
If there was a file named “index.html” in the directory it will just display that html file instead of the directory listing. This is a convention. index.html is returned if nothing else is specified in the GET request.