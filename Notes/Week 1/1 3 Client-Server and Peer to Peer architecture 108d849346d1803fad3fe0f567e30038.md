# 1.3 Client-Server and Peer to Peer architecture.

Created: September 21, 2024 4:51 PM
Class: Modern App Developement 1
Week: Week 1

# Client-Server Architecture

There is a server who’s primary function is to store data and respond to requests.

There are clients that are end users and they will send requests.

There is network that acts as a data pipe, connecting the two.

- Explicit differentiation between client and server.
- Could run locally.
    - One part of your system acts as a client and another as a server on the local network.
    - Conceptually still a networked system even when client and servers are on the same machine.
- Clients don’t have to be users.
    - Could be a machine or a software that sends requests to a server with no user interaction.
- Examples.
    - Email.
    - Messaging service.
    - Databases. These also act as client server even when running locally.

# Peer to Peer Model

There is no set central server. Data is distributed in peers that are all considered equal.

- All Peers are considered equal.
    - But some peers are more equal than others (nice reference).
        - Some peers are more valuable, for example a peer with high bandwidth is more valuable than a mobile device with limited bandwidth.
- Error tolerant.
    - Just need a master/introducer. No central server. If a big valuable peer crashes it does not bring down the entire system like it would if there was a central server.
    - If master crashes a new master can be selected.
- Limited scope.
    - P2P systems cannot be applied everywhere, for example an Emails server HAS to be centralized, can’t be p2p.
    - Examples: Torrent, Blockchain, Online games.