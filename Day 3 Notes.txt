1. Networking:
Networking is a collection of computing devices that are connected to communicate and share resources.

Connection types:
- Wired (cable)
- Wireless (WiFi)

Each device in a network is called a node or host.


2. Basic Idea:
- Every device has an IP address
- We access systems using domain names (e.g. google.com)
- DNS converts domain into IP address
- Communication happens through HTTP/HTTPS


3. Components of Networking:
- Devices: PC, Mobile, Server
- Medium: WiFi, Cable, Internet
- Protocols: HTTP, HTTPS, TCP/IP


4. Internet Flow:
User → Browser → DNS → IP → Server → Response → Browser

- User sends request
- DNS finds IP address
- Server processes request
- Server sends response
- Browser shows result


5. IP Address:
An IP address is a unique identifier of a device on a network.

Example:
192.168.1.1


6. Types of IP:

Public IP:
- Visible on internet
- Assigned by ISP
- Unique globally
- Accessible from anywhere

Private IP:
- Used inside local network
- Not visible on internet

Private IP ranges:
- 10.0.0.0 – 10.255.255.255
- 172.16.0.0 – 172.31.255.255
- 192.168.0.0 – 192.168.255.255


7. NAT (Network Address Translation):
- Converts private IP into public IP
- Allows multiple devices to use one public IP


8. DNS (Domain Name System):
DNS converts domain names into IP addresses.

Example:
google.com → 142.x.x.x

Without DNS, users would need to remember IP addresses.


9. HTTP vs HTTPS:

HTTP:
- Data is sent in plain text
- Not secure

HTTPS:
- Data is encrypted
- Uses SSL/TLS
- Secure communication


10. HTTP Request Analysis:
- Browser sends request to server
- Server sends response

Example:
GET /?q=mobile

- Method: GET
- Parameter: q=mobile
- Status: 200 (OK)


11. HTTP Methods:

- GET: Fetch data
- POST: Send data
- PUT: Replace data
- PATCH: Update data
- DELETE: Delete data


12. APIs (Application Programming Interface):
API is a bridge between client and server.

- Handles requests
- Processes data
- Sends response

Example:
GET /api/products?q=mobile


13. Commands Practiced:

ipconfig:
- Shows IPv4 address
- Shows default gateway

ping google.com:
- Checks connectivity
- Shows response time
- Confirms network is working


14. Key Learnings:

- Internet works on request-response model
- Every device has an IP address
- DNS converts domain to IP
- HTTP/HTTPS handle communication
- User input goes to server through requests
- APIs manage data exchange


15. Summary:
Networking = Devices + IP Address + Communication
