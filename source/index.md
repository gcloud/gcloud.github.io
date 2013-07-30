---
title: Go Packages for Cloud Services
---
GCloud delivers a set of open source packages and interfaces to easily manage services
across cloud providers. These packages and interfaces are written in [Go](golang.org) to
deliver a simple user experience with maximum flexibility and a high level of concurrency. The
result will be an easily imported library, a portable binary, http, zeromq, and basic socket interfaces.

Currently in the design phase, GCloud is creating the base api and test cases needed to write
the complete set of packages.

Read the [FAQ](faq.html)

Packages
----
- [Compute](docs/compute.html)
- [Identity](docs/identity.html)
- [Storage](docs/storage.html)


Features
--------
 - Standard API to cloud providers
 - Packages that can be included in other Go programs
 - Multiple interfaces (http, zmq, tcp) for programs written in other languages
 - Command line interface for utility


Advantages
----------
 - unified vocabulary
 - flexibility
 - ease of use
 - speed


Services
--------
- Compute
- Identity
- Object Storage
- DNS (future)
- Load Balancers (future)


Similar Libraries
-----------------
 - [libcloud](http://libcloud.apache.org/) (python)
 - [nodejs](https://github.com/nodejitsu/pkgcloud) (nodejs)

