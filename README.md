# Services in Hybrid Cloud
This blog outlines a methodology that can be employed to develop, build, deploy and manage services in a hybrid cloud environment.

## Hybrid Cloud
For the purpose of this blog, _Hybrid Cloud_ means an infrastructure platform that is composed of one or more of the following components:
1. **Physical hardware**: physical servers, networking equipment, etc.
2. **Virtualised hardware**: KVM, VMWare, HyperV based virtual farms.
3. **Private cloud infrastructure**: enterprise (or individual) owned and managed software defined infrastructure
4. **Public cloud infrastructure**: software defined infrastructure leased from a service provider

# Use case
![Student acquisition process](https://raw.githubusercontent.com/finiteloopme/hybrid-cloud-services/master/student-acquisition-process.png)

## Overview
The use-case we will use for the purpose of this discussion is a student acquisition process employed by universities.

Student acquisition and student retention is a big challenge faced by all the universities.

## Demo student
- The domain name on OpenShift must be**unidomain**
- The EAP application name must be **twitter**
- [Register search criteria for Twitter](http://twitter-unidomain.rhcloud.com/register-data-feed)
- [Dashboard to investigate cache](http://twitter-unidomain.rhcloud.com/dashboard-data-stream)
- [Twitter integration source code](https://github.com/finiteloopme/data-stream-demo)

# Further reading
1. [Microservices](https://developerblog.redhat.com/tag/microservices/)
2. [Wildfly Swarm](https://github.com/wildfly-swarm/wildfly-swarm)
