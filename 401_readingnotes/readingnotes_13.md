# Reading Notes 13

What are the benefits of a forward proxy?
- Bypassing state or institutional browsing restrictions.
- Blocking access to certain content.
- Protecting user identity online.

Explain the differences between a forward and a reverse proxy?
- A forward proxy sits between client machines and the internet, acting as a middleman for client requests, primarily used for bypassing restrictions, blocking content, or maintaining anonymity.
- A reverse proxy is positioned in front of web servers, intercepting requests from clients to the servers. It enhances security, performance, and reliability, unlike the forward proxy which focuses on client anonymity and access control.

Explain to your manager why your organization might benefit from implementing a reverse proxy?
- A reverse proxy can improve the security of our web servers by masking their IP addresses, thus protecting against targeted attacks like DDoS.
- It can enhance website performance and user experience through load balancing, distributing incoming traffic evenly across multiple servers.
- The reverse proxy can also speed up content delivery and reduce server load by caching content and handling SSL encryption, which reduces the load on the origin servers.
- Implementing a reverse proxy, possibly through a CDN service Like Cloudfare CND, can be cost-effective while providing these significant performance and security benefits.


#### source: https://www.cloudflare.com/learning/cdn/glossary/reverse-proxy/