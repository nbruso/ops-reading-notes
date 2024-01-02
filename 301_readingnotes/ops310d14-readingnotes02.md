# Part 1

### What is a Port?

**Explanation:**
A port is like a specific door at a big building. Each door is for different activities, like going to a gym or a library. Similarly, in computers, ports are like doors that let different kinds of information in and out.

### What does a Port Scanner send to a Port to Check the Current Status?

**Explanation:**
A port scanner is like a person knocking on doors to see if they're open. It sends a message to a computer door (port) to check if it's ready to talk. The response tells if the door is open, closed, or blocked.

### When a Port Scanner Sends a Request to Connect, What are the Three Possible Responses? Describe Them.

1. **Open, Accepted:**
   - **Explanation:** It's like knocking, and someone inside says, "Come in!" The computer door is open and ready to talk.

2. **Closed, Not Listening:**
   - **Explanation:** Knocking, but no one answers or a sign says, "We're closed." The computer door is closed and not accepting messages.

3. **Filtered, Dropped, Blocked:**
   - **Explanation:** Knocking, but no response. It's like a door you can't tell if someone's there. The computer door is blocked or protected.

### What is the Difference Between TCP and UDP?

**Explanation:**
- **TCP (Transmission Control Protocol):**
  - **Characteristics:** Like a certified letter delivery service. It makes sure your message gets there, and you know when it's delivered.

- **UDP (User Datagram Protocol):**
  - **Characteristics:** Like a quick messenger service. It delivers messages fast but doesn't check if they all arrived.

In simple terms, TCP is like a conversation, and UDP is like a quick shout across the room. They're used based on how important it is for all the information to get through.

# Part 2

### Port Numbers for Common Services

1. **Telnet:**
   - **Port:** 23
   - **Description:** Used for remote console access, but not secure.

2. **SSH (Secure Shell):**
   - **Port:** 22
   - **Description:** Secure alternative to Telnet for remote console access.

3. **DNS (Domain Name System):**
   - **Port:** 53 (UDP)
   - **Description:** Converts names to IP addresses. Critical for network name resolution.

4. **SMTP (Simple Mail Transfer Protocol):**
   - **Port:** 25 (plaintext) / 587 (encrypted with TLS)
   - **Description:** Sends server-to-server emails over the internet.

5. **HTTP (Hypertext Transfer Protocol):**
   - **Port:** 80
   - **Description:** Used for unencrypted web communication.

6. **HTTPS (Hypertext Transfer Protocol Secure):**
   - **Port:** 443
   - **Description:** Encrypted version of HTTP for secure web communication.

7. **RDP (Remote Desktop Protocol):**
   - **Port:** 3389
   - **Description:** Allows viewing the desktop of a remote Windows computer.

8. **NTP (Network Time Protocol):**
   - **Port:** 123 (UDP)
   - **Description:** Synchronizes date and time across network devices.

9. **SNMP (Simple Network Management Protocol):**
   - **Port:** 161 (Query) / 162 (Trap)
   - **Description:** Gathers statistics from network devices and sends alerts.

10. **Syslog:**
    - **Port:** 514 (UDP)
    - **Description:** Collects and centralizes log information from various devices.

11. **SIP (Session Initiation Protocol):**
    - **Ports:** 5060 / 5061
    - **Description:** Sets up, tears down, and manages VoIP phone calls.

12. **SMB (Server Message Block):**
    - **Port:** 445
    - **Description:** Commonly used for file transfers and printer jobs on Windows networks.

13. **LDAP (Lightweight Directory Access Protocol):**
    - **Port:** 389 (LDAP) / 636 (LDAPS)
    - **Description:** Accesses centralized user information databases securely.

14. **Database Protocols:**
    - **Microsoft SQL Server:** 1433
    - **Oracle SQLNet:** 1521
    - **MySQL:** 3306
    - **Description:** Used for accessing specific types of databases.

#### sources: 
##### https://www.varonis.com/blog/port-scanning-techniques
##### https://www.professormesser.com/network-plus/n10-008/n10-008-video/common-ports-n10-008/
