30-06-2023 @ 00:11

Status: #idea

Tags: 

# Server Virtualization

Server Virtualization is the process of dividing a physical server into several virtual servers, called **virtual private servers**. Each virtual private server can run independently.

The concept of Server Virtualization widely used in the [IT](https://www.javatpoint.com/it-full-form) infrastructure to minimizes the costs by increasing the utilization of existing resources.

## Types of Server Virtualization

### 1. Hypervisor

In the Server Virtualization, Hypervisor plays an important role. It is a layer between the [operating system](https://www.javatpoint.com/os-tutorial) (OS) and [hardware](https://www.javatpoint.com/hardware). There are two types of hypervisors.

- Type 1 hypervisor ( also known as bare metal or native hypervisors)
- Type 2 hypervisor ( also known as hosted or Embedded hypervisors)

The hypervisor is mainly used to perform various tasks such as allocate physical hardware resources (CPU, RAM, etc.) to several smaller independent virtual machines, called "**guest**" on the host machine.

### 2. Full Virtualization

Full Virtualization uses a **hypervisor** to directly communicate with the [CPU](https://www.javatpoint.com/cpu-full-form) and physical server. It provides the best isolation and security mechanism to the virtual machines.

The biggest disadvantage of using hypervisor in full virtualization is that a hypervisor has its own processing needs, so it can slow down the application and server performance.

**VMWare ESX server** is the best example of full virtualization.

### 3. Para Virtualization

Para Virtualization is quite similar to the Full Virtualization. The advantage of using this virtualization is that it is **easier to use**, **Enhanced performance**, and **does not require emulation overhead**. Xen primarily and [UML](https://www.javatpoint.com/uml) use the Para Virtualization.

The difference between full and pare virtualization is that, in para virtualization hypervisor does not need too much processing power to manage the OS.

### 4. Operating System Virtualization

Operating system virtualization is also called as system-lever virtualization. It is a **server virtualization technology** that divides one operating system into multiple isolated user-space called **virtual environments**. The biggest advantage of using server visualization is that it reduces the use of physical space, so it will save money.

**Linux OS Virtualization** and **Windows OS Virtualization** are the types of Operating System virtualization.

**FreeVPS**, **OpenVZ**, and **Linux Vserver** are some examples of System-Level Virtualization.

#### Note: OS-Level Virtualization never uses a hypervisor.

### 5. Hardware Assisted Virtualization

Hardware Assisted Virtualization was presented by **AMD and Intel**. It is also known as **Hardware virtualization**, **AMD virtualization**, and **Intel virtualization**. It is designed to increase the performance of the processor. The advantage of using Hardware Assisted Virtualization is that it requires less hypervisor overhead.

### 6. Kernel-Level Virtualization

Kernel-level virtualization is one of the most important types of server virtualization. It is an **open**-**source virtualization** which uses the [Linux](https://www.javatpoint.com/linux-tutorial) kernel as a hypervisor. The advantage of using kernel virtualization is that it does not require any special administrative software and has very less overhead.

**User Mode Linux** (UML) and **Kernel-based virtual machine** are some examples of kernel virtualization.

## Advantages of Server Virtualization

There are the following advantages of Server Virtualization -

**1. Independent Restart**

In Server Virtualization, each server can be restart independently and does not affect the working of other virtual servers.

**2. Low Cost**

Server Virtualization can divide a single server into multiple virtual private servers, so it reduces the cost of hardware components.

**3. Disaster Recovery<**

Disaster Recovery is one of the best advantages of Server Virtualization. In Server Virtualization, data can easily and quickly move from one server to another and these data can be stored and retrieved from anywhere.

**4. Faster deployment of resources**

Server virtualization allows us to deploy our resources in a simpler and faster way.

**5. Security**

It allows uses to store their sensitive data inside the data centers.

## Disadvantages of Server Virtualization

There are the following disadvantages of Server Virtualization -

1. The biggest disadvantage of server virtualization is that when the server goes offline, all the websites that are hosted by the server will also go down.
2. There is no way to measure the performance of virtualized environments.
3. It requires a huge amount of RAM consumption.
4. It is difficult to set up and maintain.
5. Some core applications and databases are not supported virtualization.
6. It requires extra hardware resources.

## Uses of Server Virtualization

A list of uses of server virtualization is given below -

- Server Virtualization is used in the testing and development environment.
- It improves the availability of servers.
- It allows organizations to make efficient use of resources.
- It reduces redundancy without purchasing additional hardware components.

---
# References
