# OSI Model and TCP/IP Model

Networking models provide a standardized way for devices to communicate over a network.
The two most commonly used models are:
1. OSI (Open Systems Interconnection) Model
2. TCP/IP (Transmission Control Protocol/Internet Protocol) Model

## OSI Model
- The OSI Model consists of 7 layers, each responsible for specific networking functions.
  1. Physical Layer
  2. DataLink Layer
  3. Network Layer
  4. Transport Layer
  5. Session Layer
  6. Presentation Layer
  7. Application Layer

### 7.Application Layer
- Provides network services to end users.
- Allows applications to communicate over a network
- Handles email, web browsing, file transfers, etc
- Examples
  HTTP/HTTPS
  FTP
  SMTP
  DNS
- Devices
  User Applications
  Web Browsers

### 6.Presentation Layer
- Data formatting and translation
- Encryption and Decryption
- Data compression
- Examples
  SSL/TLS
  JPEG
  PNG
  ASCII
- Function
  Ensures data sent by one system can be understood by another.

### 5.Session Layer
- Establishes communication sessions
- Maintains sessions
- Terminates sessions
- Examples
  NetBIOS
  RPC
- Function
  Manages conversations between applications

### 4.Transport Layer
- End-to-end communication
- Error detection and recovery
- Flow control
- Segmentation and reassembly
- Protocols
  TCP
  UDP
- PDU
  Segment

### 3.Network Layer
- Logical addressing
- Routing packets
- Path selection
- Protocols
  IP
  ICMP
  OSPF
- Devices
  Routers
- PDU
  Packet

### 2.Data Link Layer
- Physical addressing (MAC Address)
- Error detection
- Frame synchronization
- Devices
  Switches
  Bridges
- PDU
  Frame

### 1.Physical Layer
- Transmission of raw bits
- Defines cables, connectors, signals, and voltages
- Devices
  Hubs
  Repeaters
  Cables
- PDU
  Bits

### OSI Layer Mnemonic
All People Seem To Need Data Processing

## TCP/IP Model
- The TCP/IP model is the proctical networking model used on the Internet
- It consists of 4 layers
  1. Application Layer
  2. Transport Layer
  3. Internet Layer
  4. Network Access Layer

### 1.Application Layer
- Combines OSI Layers 5,6, and 7
- Provides services to applications
- Handles data respresentation and communication
- Protocols
  HTTP
  HTTPS
  FTP
  DNS
  SMTP

### 2.Transport Layer
- Reliable communication
- Error checking
- Flow control
- Protocols
  TCP
  UDP

### 3.Internet Layer
- Logical addressing
- Routing packets across networks
- Protocols
  IP
  ICMP
  ARP

### 4.Network Access Layer
- Physical transmission of data
- MAC addressing
- Frame creation
- Technologies
  Etherent
  Wi-Fi

## TCP/IP vs OSI Model
<img width="859" height="576" alt="image" src="https://github.com/user-attachments/assets/fd4f0156-0605-4af8-b2ea-43e235782647" />
