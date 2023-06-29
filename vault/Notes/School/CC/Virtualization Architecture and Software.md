w27-06-2023 @ 22:49

Status: #idea

Tags: #syllabus #cloud 

# Virtualization Architecture and Software
**Virtualization** plays a very important role in the cloud computing technology, normally in the cloud computing, users share the data present in the clouds like application etc., but actually with the help of virtualization users shares the Infrastructure.

The **main usage of Virtualization Technology** is to provide the applications with the standard versions to their cloud users, suppose if the next version of that application is released, then cloud provider has to provide the latest version to their cloud users and practically it is possible because it is more expensive.

To overcome this problem we use basically virtualization technology, By using virtualization, all severs and the software application which are required by other cloud providers are maintained by the third party people, and the cloud providers has to pay the money on monthly or annual basis.
![[Virtualization Architecture in Cloud]]

Virtualization is generally achieved through the hypervisor. A hypervisor enables the separation of operating systems with the underlying hardware. It enables the host machine to run many virtual machines simultaneously and share the same physical computer resources. There are two methods through which virtualization architecture is achieved described below:

- **Type one: The first hypervisor type is termed** a bare-metal hypervisor. They directly run over the top of the hardware of the host system. They deliver effective resource management and ensure the high availability of resources. It delivers direct access to the hardware system, ensuring better scalability, performance, and stability.
- **Type two: The second hypervisor type is** the hosted hypervisor. This is installed on the host operating system, and the virtual operating system runs directly above the hypervisor. It is the kind of system that eases and simplifies system configuration.

---
# References