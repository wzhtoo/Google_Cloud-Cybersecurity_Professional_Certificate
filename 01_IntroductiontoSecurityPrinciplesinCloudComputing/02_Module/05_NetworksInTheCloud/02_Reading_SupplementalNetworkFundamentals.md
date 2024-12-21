# 02_Reading_Supplemental Network Fundamentals

[Reading_Supplemental Network Fundamentals &#128279;](https://www.coursera.org/learn/introduction-to-security-principles-in-cloud-computing/supplement/b3ElO/supplemental-network-fundamentals)

[https://www.youtube.com/watch?v=9SIjoeE93lo 🔗](https://www.youtube.com/watch?v=9SIjoeE93lo)

- What is a network?
  - A system that allows multiple devices to communication with one another.

# OSI Model (Open Systems Interconnection Model)

The OSI Model is a conceptual framework that standardizes how communication occurs between different systems in a network. It is divided into seven layers, each with specific functions. Below is a detailed explanation of each layer:

## 1. Physical Layer (Layer 1)

**Purpose:** Deals with the physical connection between devices and the transmission of raw data (bits) over a network.

**Functions:**

- Defines hardware specifications (cables, switches, hubs, etc.).
- Manages data encoding, signaling, and transmission.
- Converts digital bits into electrical, optical, or radio signals and vice versa.

**Examples:**

- Ethernet cables, Wi-Fi signals, fiber optics, connectors.

## 2. Data Link Layer (Layer 2)

**Purpose:** Ensures reliable transmission of data across the physical link. Divided into two sublayers:

- **MAC (Media Access Control):** Controls access to the physical medium.
- **LLC (Logical Link Control):** Handles error detection and flow control.

**Functions:**

- Creates and manages frames (structured chunks of data).
- Handles error detection and correction (e.g., CRC checks).
- Provides physical addressing through MAC addresses.

**Examples:**

- Ethernet, Wi-Fi (IEEE 802.11), ARP (Address Resolution Protocol).

## 3. Network Layer (Layer 3)

**Purpose:** Responsible for logical addressing, routing, and forwarding of data packets across networks.

**Functions:**

- Assigns IP addresses to devices.
- Routes packets using algorithms to find the best path to the destination.
- Breaks data into packets and reassembles them.

**Examples:**

- IPv4, IPv6, routers, ICMP (ping, traceroute).

## 4. Transport Layer (Layer 4)

**Purpose:** Ensures reliable data transfer between devices and provides error detection and recovery.

**Functions:**

- Manages end-to-end communication.
- Divides data into segments or datagrams.
- Ensures reliability (in TCP) or faster delivery without guarantees (in UDP).
- Handles flow control and error recovery.

**Examples:**

- **TCP (Transmission Control Protocol):** Reliable, connection-oriented protocol (e.g., for web pages).
- **UDP (User Datagram Protocol):** Fast, connectionless protocol (e.g., for video streaming).

## 5. Session Layer (Layer 5)

**Purpose:** Establishes, maintains, and terminates communication sessions between applications.

**Functions:**

- Synchronizes dialogue between devices.
- Manages sessions to ensure data flows in the correct order.
- Supports checkpointing for long transfers, so interrupted sessions can resume.

**Examples:**

- APIs, NetBIOS, RPC (Remote Procedure Call).

## 6. Presentation Layer (Layer 6)

**Purpose:** Ensures data is in a readable format for the application layer. It acts as a translator.

**Functions:**

- Handles data encryption (e.g., SSL/TLS) and decryption.
- Compresses data to optimize transmission.
- Converts data formats (e.g., ASCII to binary, image formats like JPEG, PNG).

**Examples:**

- SSL/TLS for secure communication, JPEG, MPEG, GIF.

## 7. Application Layer (Layer 7)

**Purpose:** Provides the interface for end-user applications to access network services.

**Functions:**

- Handles high-level APIs and user interfaces.
- Ensures proper protocols are used for different services (e.g., web browsing, email, file transfer).

**Examples:**

- HTTP/HTTPS (web browsing).
- FTP (file transfer).
- SMTP (email).
- DNS (domain name resolution).

## How Data Moves Through the OSI Model

When data is sent:

1. It starts at the **Application Layer** and moves down through the layers, where it is packaged into **segments (Layer 4)**, **packets (Layer 3)**, **frames (Layer 2)**, and **bits (Layer 1)**.
2. At the receiving end, the process is reversed, with each layer interpreting its relevant information.

## Analogy for Understanding

Imagine sending a letter:

- **Application Layer (7):** You write the letter and address it.
- **Presentation Layer (6):** The letter is translated into a format (language) the recipient understands.
- **Session Layer (5):** Ensures the conversation starts and ends properly.
- **Transport Layer (4):** Packages the letter into an envelope and ensures delivery (e.g., via certified mail).
- **Network Layer (3):** Decides the route to send the letter (e.g., through postal offices).
- **Data Link Layer (2):** The postal worker delivers the envelope to the correct mailbox.
- **Physical Layer (1):** The physical journey of the letter (e.g., trucks, planes, etc.).

## Why is the OSI Model Important?

- **Standardization:** Provides a universal reference for network communication.
- **Troubleshooting:** Helps pinpoint issues in specific layers.
- **Interoperability:** Ensures devices from different manufacturers can communicate.
- **Learning Tool:** Simplifies understanding of complex network systems.
