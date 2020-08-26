# system-design
Holds notes for system design
## General
- [System Design Primer](https://github.com/donnemartin/system-design-primer)
- [Twelve factor app](https://12factor.net/)

## DNS
- [Intro to how DNS Works](https://howdns.works/ep1/)
- [Intro to DNS Concepts](https://ns1.com/resources/dns-types-records-servers-and-queries#:~:text=3%20types%20of%20DNS%20servers,AAAA%2C%20CNAME%2C%20MX%20and%20NS)
### Routing Schemes
- [Types of routing schemes](https://en.wikipedia.org/wiki/Routing#Delivery_schemes)
- Anycast
  - [Anycast DNS](https://ns1.com/resources/anycast-dns#:~:text=Multicast%E2%80%94one%2Dto%2Dmany,subset%20of%20all%20accessible%20nodes.&text=Geocast%E2%80%94a%20specialized%20form%20of,identified%20by%20their%20geographical%20locations.)
- Geocast
  - [Microsoft Geolocation based traffic](https://docs.microsoft.com/en-us/windows-server/networking/dns/deploy/primary-geo-location)
  - [How geographic routing works](https://ns1.com/resources/how-geographic-routing-works#:~:text=The%20basic%20concept%20behind%20geographic,physically%20closest%20to%20the%20requestor.&text=The%20location%20of%20the%20IP,the%20DNS%20query%20was%20received.)
### Nameservers
- [Authoritative vs Recursive](https://ns1.com/resources/whats-the-difference-authoritative-and-recursive-dns-explained)
#### Libraries
- [Intro to BIND](http://www.firewall.cx/linux-knowledgebase-tutorials/system-and-network-services/829-linux-bind-introduction.html)
  - Authoritative or Recursive
- [Unbound](https://github.com/NLnetLabs/unbound)
  - Recursive ONLY
### Secure DNS
- [DNS over TLS vs. over HTTPS](https://www.cloudflare.com/learning/dns/dns-over-tls/)

# Android Design
## Intro
- [Preparing for Android System Design Interview](https://medium.com/@lokeshloke/preparing-for-an-android-system-design-interview-84991519807a)
- [Mobile System Design Interview](https://medium.com/@goncharov.artemv/grokking-the-mobile-system-design-interview-6a06fa94491b)

## Key Metrics
- App Performance
- Battery Life
