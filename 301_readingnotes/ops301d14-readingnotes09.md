### Reading Notes 09

**Q:** What are the differences between SPAN and TAP?

- **SPAN (Port Mirroring):**
  - Copies packets from source ports to a destination port.
  - Inexpensive, flexible, and remotely configurable.
  - Good for capturing intra-switch traffic on multiple ports.

- **TAP (Network TAP):**
  - Passively captures traffic by replacing cables between two points.
  - Typically has A, B, and monitor ports.
  - No risk of dropped packets, monitors all packets, but costly.

**Q:** What types of network devices can support network traffic mirroring?

- **SPAN (Port Mirroring):**
  - Commonly supported in most switches.

- **TAP (Network TAP):**
  - Requires a dedicated hardware device (Network TAP).

**Q:** How can network traffic mirroring be used for network security?

- **SPAN (Port Mirroring):**
  - Used for monitoring and collection devices like APS.
  - May assist in security applications but has limitations during switch congestion.

- **TAP (Network TAP):**
  - Suitable for security applications, non-obtrusive, undetectable, and handles full-duplex networks well.

**Q:** Are there any legal or ethical considerations when using network traffic mirroring?

- You need to have explicit consent form a company before mirroring their traffic. Otherwise, it's just hacking.

#### Source: https://accedian.com/blog/capture-network-traffic-span-vs-tap/
