# Delphinus DNS
Delphinus DNS is a non-caching, non-recursing DNS server that serves
authoritative answers for A, AAAA, CNAME, DNSKEY, DS, MX, NAPTR, NS,
NSEC3, NSEC3PARAM, PTR, RRSIG, SOA, SRV, SSHFP, TLSA, and TXT resource
records.

For more information please visit DelphinusDNS's [website](https://delphinusdns.org).

## Installation

```shell
$ doas pkg_add delphinusdnsd-1.4.1
```

## Thanks

* Peter J. Philipp for developing the software in the first place and for his patience answering all my questions
* Brian Robert Callahan for sharing this awesome [guide](https://www.youtube.com/watch?v=z_TnemhzbXQ) on how to port software for OpenBSD
* gonzalo for helping with post-install instructions
