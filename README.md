# Local Network TLS Example

This repository contains example code showcasing how to utilize zero-configuration networking (Zeroconf) and establish secure Transport Layer Security (TLS) connections for messaging and file exchange within a local network environment.

## Requirements:
- Python zeroconf library
- Python socket module
- Python ssl module

### Registration
The code demonstrates registration of services using mDNS (Multicast DNS), allowing devices to announce their availability on the network without requiring a central server.

### Advertise

### Find Services

### Establish TLS Connection
The provided examples illustrate the implementation of public key cryptography and key exchange mechanisms to establish secure TLS connections between devices within the local network.

### Save Contact
Contact information is conveniently stored in a .json file format, containing the hostname and corresponding public key of devices for easy access and management.


> Folder structure options and naming conventions for software projects

### Directory layout
    .
    ├── src/
    │   ├── __init__.py
    │   ├── register.py
    │   ├── advertise.py
    │   ├── find_services.py
    │   ├── tls_connection.py
    │   └── save_contact.py
    ├── test/
    │   ├── __init__.py
    │   ├── test_register.py
    │   ├── test_advertise.py
    │   ├── test_find_services.py
    │   ├── test_tls_connection.py
    │   └── test_save_contact.py
    ├── contacts.json
    ├── LICENSE
    ├── README.md
    └── requirements.txt
