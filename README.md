# quickstart-atos-evidian-safekit
## Evidian SafeKit on AWS

This Quick Start deploys an Evidian SafeKit cluster automatically on the Amazon Web Services (AWS) Cloud. SafeKit is a software-only high-availability product with synchronous real-time replication, network load balancing, and automatic failover. 

SafeKit helps companies secure 24/7 operation of critical applications. It addresses business continuity, disaster recovery, and scalability for Windows and Linux applications with redundancy and with active or passive backup servers. It does not require specific hardware, specific network configuration, or specific external storage. It lends itself to the AWS Cloud because it is hardware agnostic.  

Customers can configure clusters for a given application using one or more application modules: mirror modules, farm modules, or a combination. Mirror modules use primary and secondary servers with real-time file replication and failover. Farm modules use network load balancing combined with failover for up to four servers.

The Quick Start offers two deployment options:

- [Deploy SafeKit mirror into a new VPC](https://fwd.aws/8VgKN) (Figure 1)
- [Deploy SafeKit farm into a new VPC](https://fwd.aws/4wRxE) (Figure 2)

<p align="center">
    <img src="https://d1.awsstatic.com/partner-network/QuickStart/datasheets/atos-evidian-safekit-mirror-architecture.5f208798f73a70e937f69b4df63087eaca1fb6d6.png">
</p>
<p align="center">Figure 1. Quick Start architecture for SafeKit mirror on AWS</p>
<br/><br/> 
<p align="center">
    <img src="https://d1.awsstatic.com/partner-network/QuickStart/datasheets/atos-evidian-safekit-farm-architecture.b48391a6ffa458a12be2d4b03204f764335bc242.png">
</p>
<p align="center">Figure 2. Quick Start architecture for SafeKit farm on AWS</p>

For architectural details, step-by-step instructions, and customization options, see the [deployment guide](https://fwd.aws/jKegE).

To post feedback, submit feature ideas, or report bugs, use the **Issues** section of this GitHub repo.

If you'd like to submit code for this Quick Start, please review the [AWS Quick Start Contributor's Kit](https://aws-quickstart.github.io/). 
