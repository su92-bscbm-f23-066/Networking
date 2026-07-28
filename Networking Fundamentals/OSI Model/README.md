
# OSI Model

## Overview

The **OSI (Open Systems Interconnection) Model** is a conceptual framework used to understand how data travels from one device to another over a network. It divides network communication into seven layers, making it easier to understand, troubleshoot, and design networks.

## Why It Matters

- Simplifies troubleshooting by dividing network communication into separate layers.
- Provides a standardized framework for communication between devices from different vendors.
- Forms the foundation of modern networking concepts.
- Helps network engineers understand how different protocols work together.

## The Seven Layers

| Layer | Name | Examples |
|:-----:|------|----------|
| 7 | Application | HTTP, HTTPS, DNS, FTP |
| 6 | Presentation | SSL, TLS, Encryption, Compression |
| 5 | Session | Session establishment and management |
| 4 | Transport | TCP, UDP |
| 3 | Network | IP, Routers |
| 2 | Data Link | MAC Address, Switches |
| 1 | Physical | Cables, Fiber Optics, Electrical Signals |

## Mnemonic

**All People Seem To Need Data Processing**

- **A** = Application
- **P** = Presentation
- **S** = Session
- **T** = Transport
- **N** = Network
- **D** = Data Link
- **P** = Physical

## Real-World Example

When you open **www.google.com**:

1. The browser creates an HTTP request.
2. The request is encrypted using TLS/SSL if HTTPS is used.
3. A communication session is established.
4. TCP provides reliable data delivery.
5. IP determines the destination address.
6. The switch forwards frames using MAC addresses.
7. Data is transmitted through cables or wireless signals.

## Key Takeaways

- The OSI Model consists of **seven layers**.
- Each layer has a specific responsibility.
- Routers primarily operate at **Layer 3 (Network)**.
- Switches primarily operate at **Layer 2 (Data Link)**.
- Hubs operate at **Layer 1 (Physical)**.
- Understanding the OSI Model makes troubleshooting network issues easier.

## References

- Cisco CCNA Official Certification Guide
- IEEE Networking Standards
- RFC Standards

