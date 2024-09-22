# P2P  Network Project 

# THE PROJECT


### What is Peer-to-Peer Network

P2P network is a distributed network architecture that doesn't need a central server for communication. In p2p network, each computer that joined the network called Peer (or Node) and they are connected to each other directly. Mainly this network is used in file sharing and blockchain applications.



### About the project

This project is a simple implementation of a peer-to-peer network using Python. The project will include the
following features:
-   **Node creation**: Each node will have a unique id and will be able to connect to
other nodes.
-   **Message sending**: Each node will be able to send messages to other nodes.
-   **Message receiving**: Each node will be able to receive messages from other nodes.
-   **Node discovery**: Each node will be able to discover other nodes in the network.
-   **Network visualization**: The network will be visualized using a graph library.
-   **Node removal**: Each node will be able to remove itself from the network.
-   **Network shutdown**: The network will be able to shut down.
-   **Node status**: Each node will be able to check its status in the network.
-   **Network status**: The network will be able to check its status.
-   **Network size**: The network will be able to check its size.


### How does it work

The project will use the following components:
-   **Node class**: This class will represent each node in the network. It will have methods
for connecting to other nodes, sending messages, receiving messages, discovering other nodes,
removing itself from the network, checking its status, and shutting down the network.
-   **Network class**: This class will represent the network. It will have methods for
discovering nodes, checking the network status, and shutting down the network.
-   **Graph library**: This library will be used to visualize the network.
-   **Message class**: This class will represent messages sent between nodes.
-   **Connection class**: This class will represent connections between nodes.
-   **Discovery class**: This class will be used to discover other nodes in the network.
-   **Status class**: This class will be used to check the status of nodes and the network
-   **Shutdown class**: This class will be used to shut down the network.

### File structure
```bash

│   commands.py
│   Message.py
│   Network.py
│   Node.py
│   node1.py
│   node2.py
│
│
├───helpers
│   │   cmd_helper.py
│   │   terminal_helper.py
│   │   __init__.py
│
│
├───settings
│   │   includes.py
│   │   terminal_set.py
│   │   __init__.py
│
```
<br>
<br>

## Usage


In **Node .py** file , there a **Node class** , which includes all attritibues and methods  of a Node. 

Network.py consists of a **Network class** which inherited from  Node class. So, a connection is established by using an instance of this class. 

In Node class, there are GENESIS_NODE_ADDR and GENESIS_NODE_PORT variables which is the genesis node's connection address known by everyone.

## Run 

```python
python3 node1.py
```
Use Another Terminal 

```python
python3 node2.py
```



# More


![The-Peer-to-Peer-blockchain-network-structure-8-and-the-infrastructure-of-edge](https://github.com/user-attachments/assets/784dec07-0d9d-4a78-a1c7-284039ac4a21)




