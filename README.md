# Multi-Client TCP Chatroom

This project implements a basic terminal-based multi-client chatroom using Python's socket programming and threading. It facilitates real-time communication between multiple clients connected to a centralized server over TCP.

## Overview

- A server instance listens for incoming client connections.
- Multiple clients can connect concurrently to the server using a terminal interface.
- Messages sent by any client are broadcast to all other connected clients.
- Each message is tagged with the sender’s IP address for identification.
- The server handles client sessions using separate threads.

## Features

- Concurrent handling of multiple clients via threading
- Real-time broadcast of text messages
- Simple, terminal-based user interface
- IP-based user identification
- Graceful handling of client disconnects

## Usage Instructions

1. Launch the server script on the host machine where the chatroom will be hosted.
2. Each user should then execute the client script, providing the server’s IP address and the designated port number.
3. Once connected, clients can send and receive text messages in real-time.
4. To terminate a session, clients can close their terminal window or use Ctrl+C to exit.

This project requires only standard Python libraries and runs in any standard Python 3 environment.
