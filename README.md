
# Python Networking and Cybersecurity Scripts

Welcome to my Python networking and cybersecurity scripts repository! This repository contains a collection of Python scripts that I have developed to enhance my skills and knowledge in the field of cybersecurity. Each script demonstrates fundamental concepts and techniques used in network programming and cybersecurity.

## Scripts Included

1. **TCP Client** (`tcp_client.py`): 
   - A simple TCP client that connects to a specified server, sends data, and receives a response. This script demonstrates basic TCP socket programming and data exchange over a network.

2. **UDP Client** (`udp_client.py`): 
   - A straightforward UDP client that sends data to a specified server and receives a response. This script showcases the use of UDP sockets for lightweight, connectionless communication.

3. **Netcat** (`netcat.py`): 
   - A versatile network utility script inspired by the traditional Netcat tool. This script can be used to read and write data across network connections using the TCP/IP protocol. It supports features such as port listening, command execution, and file transfers.

4. **TCP Server** (`tcp_server.py`): 
   - A basic TCP server that listens for incoming connections, receives data from clients, and sends responses. This script highlights server-side socket programming and handling multiple client connections.

## Motivation

I am passionate about learning and growing in the field of cybersecurity. Through these scripts, I aim to deepen my understanding of network protocols, socket programming, and various cybersecurity techniques. This repository serves as a testament to my dedication and motivation to enhance my skills and contribute to the cybersecurity community.

## Getting Started

To run any of these scripts, you will need Python installed on your system. You can download Python from [python.org](https://www.python.org/).

### Running the Scripts

1. **Clone the repository**:

   ```git git@github.com:nchatharoo/python_networking.git```
   
   ```cd python_networking```
   

2. **Run the desired script**:
   - TCP Client:
     ```
     python3 TCP_client.py
     ```
   - UDP Client:
     ```
     python3 UDP_client.py
     ```
   - Netcat:
     ```
     python3 netcat.py
     ```
   - TCP Server:
     ```
     python3 TCP_server.py
     ```

## Usage

### TCP Client

- Connects to a specified TCP server.
- Sends a message and receives a response.
- Example usage:
  ```
  python3 tcp_client.py
  ```

### UDP Client

- Sends a message to a specified UDP server.
- Receives a response.
- Example usage:
  ```
  python3 udp_client.py
  ```

### Netcat

- A versatile networking tool.
- Can be used to listen on a port, connect to a server, execute commands, and transfer files.
- Example usage:
  ```
  python3 netcat.py -t <target> -p <port> -l -c
  ```

### TCP Server

- Listens for incoming TCP connections.
- Receives data from clients and sends responses.
- Example usage:
  ```
  python3 tcp_server.py
  ```

## Contributing

I welcome contributions to this repository. If you have any improvements, suggestions, or additional scripts that you would like to share, please feel free to open a pull request or submit an issue.

## Contact

If you have any questions or would like to connect, please reach out to me at nchatharoo@icloud.com.

Thank you for visiting my repository. I am excited to continue my journey in cybersecurity and look forward to sharing more scripts and knowledge in the future.
