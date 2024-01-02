## Reading Notes 10

1. **How can one host within a VPC any services that need to be public?**
   - Use NAT for private-to-public IP mapping.
   - Ensure secure connectivity with VPN.

2. **Examples of services in the publicly-accessible part of the VPC? The privately-accessible part?**
   - *Public:* Public-facing websites or apps using NAT.
   - *Private:* Internal services not intended for public access.

3. **Trade-offs of using a VPC vs traditional infrastructure?**
   - *Advantages:*
     - Scalability on demand.
     - Easy hybrid cloud deployment.
     - Better performance.
     - Enhanced security.

   - *Trade-offs:*
     - For large enterprises with strict security regulations, VPC's security advantages may be less significant.

4. **How is a VPC isolated within a public cloud?**
   - Subnets reserve private IP addresses.
   - VLANs partition the network.
   - VPN encrypts traffic over the public network.

5. **How does Cloudflare support virtual private clouds?**
   - Provides a single control plane performance, security, and reliability services.
   - Services include bot management, DNS, SSL, DDoS protection.
   - Enhances performance and secures any cloud deployment.

#### source: https://www.cloudflare.com/learning/cloud/what-is-a-virtual-private-cloud/