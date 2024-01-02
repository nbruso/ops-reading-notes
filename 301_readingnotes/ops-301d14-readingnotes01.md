# Ops 301 Reading Notes 1

## Layers of OSI Model

1. **What does "OSI" stand for?**
   - OSI stands for Open Systems Interconnection.

2. **List the 7 layers of the OSI model and what each one is responsible for.**
   - **1. Physical Layer:** Responsible for establishing physical connections between devices. Deals with bits.
   - **2. Data Link Layer:** Ensures error-free node-to-node delivery of messages. Deals with frames.
   - **3. Network Layer:** Handles the transmission of data between hosts in different networks. Deals with packets.
   - **4. Transport Layer:** Provides end-to-end delivery of messages, acknowledgment, and error control. Deals with segments.
   - **5. Session Layer:** Manages connection establishment, maintenance, and termination. Ensures security.
   - **6. Presentation Layer:** Translates, encrypts/decrypts, and compresses data as needed. Deals with the presentation format.
   - **7. Application Layer:** Implements network applications, provides an interface, and displays received information to users.

3. **Distinguish which layers are the "hardware layers," and which layers are the "software layers." What does that even mean?**
   - **Hardware Layers (or Lower Layers):** Physical Layer, Data Link Layer, and Network Layer. These layers deal with the physical aspects of data transmission and are implemented by hardware devices like cables, hubs, switches, routers, etc.
   - **Software Layers (or Upper Layers):** Transport Layer, Session Layer, Presentation Layer, and Application Layer. These layers are more concerned with the software aspects of communication, involving processes, protocols, and user interfaces.

4. **How can the OSI model be used in troubleshooting?**
   - The OSI model provides a systematic way to understand and troubleshoot network issues. Network professionals can analyze each layer and pinpoint where an issue may be occurring. For example:
     - **Physical Layer Issues:** Problems with cables, connectors, or hardware devices.
     - **Data Link Layer Issues:** Address resolution, framing, or errors in node-to-node delivery.
     - **Network Layer Issues:** Routing problems or issues with logical addressing.
     - **Transport Layer Issues:** Problems with end-to-end delivery, segmentation, or acknowledgment.
     - **Session Layer Issues:** Connection establishment, maintenance, or security problems.
     - **Presentation Layer Issues:** Translation, encryption, or compression problems.
     - **Application Layer Issues:** Problems with specific network applications or user interfaces.

## What is Wireshark and How is it used?

1. **What is Wireshark?**
   - Wireshark is a network protocol analyzer, capturing and analyzing packets from a network connection to provide insights into network traffic.

2. **What is a packet?**
   - A packet is a discrete unit of data in a network, like an Ethernet network. It represents the fundamental unit of information transmitted over a network.

3. **What 3 high-level things does Wireshark accomplish?**
   - Wireshark accomplishes three main tasks:
     - *Packet Capture:* Captures real-time network traffic, grabbing entire streams of packets.
     - *Filtering:* Allows slicing and dicing of captured data using filters to obtain specific information.
     - *Visualization:* Permits in-depth analysis of network packets, visualizing entire conversations and streams.

4. **How could these be used for nefarious purposes? For benevolent purposes?**
   - **Nefarious Purposes:**
     - *Packet Capture:* Malicious actors could use Wireshark to capture sensitive data, including passwords or confidential information, from unsecured networks.
     - *Filtering:* Attackers might use filtering to target specific types of traffic, focusing on vulnerabilities or exploiting weaknesses.
     - *Visualization:* Understanding network communication could aid in crafting sophisticated attacks or identifying potential vulnerabilities.

   - **Benevolent Purposes:**
     - *Packet Capture:* Network administrators can use Wireshark to troubleshoot and diagnose performance issues, ensuring the smooth functioning of the network.
     - *Filtering:* Filtering helps focus on specific issues, making it easier to identify and address network problems.
     - *Visualization:* Analyzing network conversations helps cybersecurity professionals identify and mitigate potential threats, enhancing overall network security.

## Sources: 
1. https://www.geeksforgeeks.org/open-systems-interconnection-model-osi/
2. https://www.comptia.org/content/articles/what-is-wireshark-and-how-to-use-it
