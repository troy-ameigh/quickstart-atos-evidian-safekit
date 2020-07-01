# quickstart-atos-evidian-safekit
## Evidian SafeKit on AWS

Inside the Atos cybersecurity division, Evidian has developed SafeKit, a software-only high-availability product that helps companies secure 24/7 operation of critical applications. It does not require specific hardware, specific network configuration, or specific external storage. It lends itself to the Amazon Web Services (AWS) Cloud because it is hardware agnostic.

This Quick Start is for people who want to try the Evidian SafeKit product for building high-availability clusters with synchronous real-time replication, network load balancing, and automatic failover. SafeKit addresses business continuity, disaster recovery, and scalability for Windows and Linux applications with redundancy and with active or passive backup servers.

SafeKit works with various software clusters. Customers can configure clusters for a given application using one or more application modules: mirror modules, farm modules, or a combination. Mirror modules use primary and secondary servers with real-time file replication and failover. Farm modules use network load balancing combined with failover for up to four servers.

The Quick Start offers two deployment options:

- [Deploy SafeKit mirror into a new VPC](https://fwd.aws/8VgKN)
- [Deploy SafeKit farm into a new VPC](https://fwd.aws/4wRxE)

![Quick Start architecture for SafeKit mirror on AWS](https://d1.awsstatic.com/partner-network/QuickStart/datasheets/atos-evidian-safekit-mirror-architecture.5f208798f73a70e937f69b4df63087eaca1fb6d6.png)

![Quick Start architecture for SafeKit farm on AWS](https://d1.awsstatic.com/partner-network/QuickStart/datasheets/atos-evidian-safekit-farm-architecture.b48391a6ffa458a12be2d4b03204f764335bc242.png)

For architectural details, step-by-step instructions, and customization options, see the [deployment guide](https://fwd.aws/jKegE).

To post feedback, submit feature ideas, or report bugs, use the **Issues** section of this GitHub repo.

If you'd like to submit code for this Quick Start, please review the [AWS Quick Start Contributor's Kit](https://aws-quickstart.github.io/). 
