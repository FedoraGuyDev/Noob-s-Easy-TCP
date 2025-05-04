# Noob-s-Easy-TCP
Simple and ready to use GameMaker functions for networking using JSON 

## How to install
- [Download the .yymps](https://github.com/FedoraGuyDev/Noob-s-Easy-TCP/releases)
- Drag it into your project
- Include the script into your project

## Functions

### net_host(port, clients)
Initializes a TCP server on the specified port and prepares it to accept client connections.

### net_connect(ip, port)
Establishes a TCP connection to a server at the given IP address and port.

### net_package_send(socket, data)
Serializes the provided data into JSON format and sends it over the specified socket.

### net_server_update()
Handles incoming network events such as new connections and disconnections, updating the client list accordingly.

### net_recive_data()
Processes incoming data events, deserializing JSON data from the buffer.

### net_broadcast()
Sends the specified data to all connected clients.
