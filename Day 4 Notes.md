1. Networking Deep:
Topics:
- OSI Model
- Ports
- TCP / UDP


2. OSI Model (Open System Interconnection):

OSI model has 7 layers:

7. Application
6. Presentation
5. Session
4. Transport
3. Network
2. Data Link
1. Physical


3. Application Layer:
- Provides user interface to access network
- Provides protocols like HTTP, FTP

Example:
- File transfer uses FTP


4. Presentation Layer:
- Data formatting
- Data encryption
- Data compression
- Converts sender data into receiver understandable form


5. Session Layer:
- Creates and manages session (start communication)
- Synchronization (checkpoint)
- If data lost, resumes from last point
- Terminates session (end)


6. Transport Layer:
- Divides data into segments
- Error checking (data received correctly or not)
- Flow control (receiver handling capability)

Protocols:
- TCP (Transmission Control Protocol)
  - Reliable
  - Confirms data delivery

- UDP (User Datagram Protocol)
  - Fast
  - Unreliable


7. Network Layer:
- Divides data into packets
- Uses IP address of sender and receiver
- Finds best path to send data
- Routers work at this layer


8. Data Link Layer:
- Node to node delivery
- Uses MAC address
- Error detection


9. Physical Layer:
- Actual hardware level
- Bit transmission (0,1)
- Cable, signal, voltage


10. Ports:
Ports are logical numbers used to identify specific service/application on a device.

Example:
- IP address = house address
- Port = specific room


11. Common Ports:

20  → FTP (data transfer)
21  → FTP (control)
22  → SSH (secure remote login)
23  → Telnet (remote login, insecure)
25  → SMTP (email sending)
53  → DNS (domain lookup)
67/68 → DHCP (IP assignment)
80  → HTTP (web traffic)
110 → POP3 (email receiving)
443 → HTTPS (secure web traffic)


12. Types of Ports:

- Well-known ports:
  Standard services (HTTP, FTP, etc.)

- Registered ports:
  Specific applications

- Dynamic / Private ports:
  Temporary use (client side)


13. Lab Commands:

netstat -an
- Shows active ports and connections

ping google.com
- Checks connectivity
- Observes communication


14. Key Learnings:

- OSI model explains how data travels in layers
- Each layer has specific function
- TCP is reliable, UDP is fast
- Ports identify services
- Network communication follows layered approach


15. Summary:

Networking = Layers + Protocols + Ports + Communication
