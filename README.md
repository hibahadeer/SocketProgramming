# Python Socket Programming Example

This repository contains a simple Python script demonstrating socket programming, the script establishes a TCP connection to GitHub's server using Python's socket module.

## Prerequisites

- Python 3.x
- Basic understanding of networking concepts

## Explanation

- **socket.AF_INET, socket.SOCK_STREAM**: Creates a socket using IPv4 and TCP protocol.

- **socket.socket()**: Creates a socket object.

- **socket.gethostbyname('www.github.com')**: Resolves GitHub's hostname to an IP address.

- **s.connect((host_ip, port))**: Establishes a connection to GitHub on port 80.

- **Handle exceptions for socket errors and host resolution errors.**
