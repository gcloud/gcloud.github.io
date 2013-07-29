---
title: Go Packages for Cloud Services
---

Packages
----
- [Compute](docs/compute.html)
- [Identity](docs/identity.html)
- [Storage](docs/storage.html)


Goals
-----
 - Standard API to cloud providers
 - Library that can be included in other Go programs
 - Multiple interfaces (http, zmq, tcp) for programs written in other languages
 - Command line interface for utility


Advantages
----------
 - unified vocabulary
 - flexibility
 - ease of use
 - speed


Approach
--------
Similiar to libcloud, pkgcloud, fog, the aim is to create a set of packages in Go. The advantage will be an easily imported library or a portable binary for interaction from other programs. Few dependencies will be needed to launch a complete cloud management platform.


Services
--------
- Compute
- Identity
- Object Storage
- DNS (future)
- Load Balancers (future)
