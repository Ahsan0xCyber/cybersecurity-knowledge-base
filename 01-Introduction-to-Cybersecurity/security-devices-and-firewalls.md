# Security Devices and Firewalls

## 1. Security Devices

Security devices and technologies protect networks, systems, and data from unauthorized access and cyber threats.

- **Router:** Connects different networks and forwards packets.
- **Firewall:** Filters network traffic according to security rules.
- **IDS (Intrusion Detection System):** Detects suspicious or malicious traffic and generates alerts.
- **IPS (Intrusion Prevention System):** Detects and blocks malicious traffic.
- **VPN (Virtual Private Network):** Creates an encrypted tunnel for secure communication.
- **Anti malware:** Detects and blocks malicious software.

## 2. Types of Firewalls

- **Network-Layer Firewall:** Filters traffic using IP addresses.
- **Transport-Layer Firewall:** Uses port numbers and connection information.
- **Application-Layer Firewall:** Filters traffic based on application protocols and content.
- **Context-Aware Firewall:** Uses context such as users, devices, applications, and threats.
- **Host-Based Firewall:** Protects an individual computer.
- **NAT Firewall:** Translates private IP addresses to public addresses and can reduce direct exposure of internal hosts.
- **Proxy Server:** Intermediates client requests and can filter web traffic.
- **Reverse Proxy:** Sits in front of backend servers and can protect, distribute, and manage incoming requests.

## 3. Port Scanning

A **port** identifies a network service or application endpoint.

**Port scanning** probes a host to identify accessible ports and potentially running services.

### Port States

- **Open:** A service is accepting connections on the port.
- **Closed:** The host is reachable, but no service is listening on the port.
- **Filtered:** A firewall or other filter prevents the scanner from determining whether the port is open.

### Why Port Scanning Matters

- Administrators use it to verify network security.
- Attackers may use it during reconnaissance.
- Exposed services may increase the attack surface.

**Important:** An open port does not automatically mean a vulnerability exists.

### External Port Scanning

Scanning a public IP address can help identify services exposed to the Internet, including services made reachable through port forwarding.

**Safety:** Scan only systems you own or have explicit permission to test.
