---
title : "SDN learning path and experience"
date : 2024-08-31 19:00:00 +800
categories : [Path]
tags : [Path]
---

# SDN and NFV: The Networking Game Changers 🔧🌐
Lately, SDN (Software-Defined Networking) and NFV (Network Functions Virtualization) have been buzzing words in the networking field. Let me break down what they really mean and why they're changing the game.

SDN is essentially about decoupling the control plane from the network devices (like routers and switches). Think of the control plane as the “brain” that decides how traffic flows (similar to how a routing table builds into a forwarding information base (FIB)). In SDN, this central brain manages a flow table, determines the best path for data, and sends instructions to the devices. The switches and routers, in turn, act as the “muscle,” forwarding traffic based on the controller's commands.

## What Problem Does SDN Solve? 🤔
Network management becomes much simpler. With SDN, network admins can manage and control the entire network from one central point. This centralization allows for automated policy enforcement and more efficient traffic management—critical for mitigating constantly evolving security threats. Plus, SDN makes networks vendor-neutral by using protocols like OpenFlow, so you’re not stuck using proprietary solutions from a single vendor. This enables seamless integration across different devices, creating a more unified and flexible network.

NFV, on the other hand, virtualizes network functions—think firewalls, load balancers, routers, and intrusion detection systems—shifting them from specialized hardware to software. This means network services can be more easily modified or updated, as software is easier to change than hardware. In short, SDN and NFV make networking more like software development, enabling faster changes and innovation.

## Why I Started Learning SDN 💡
I first got into SDN while working on my Final Year Project: Automation of Network Flow Routing for Cyber Attack Mitigation in SDN. (Stay tuned—I’ll share more about this project once it’s completed!) To make it happen, I’m using ONOS, Mininet, and a few other tools. Finding reliable resources to learn SDN is tough; even AI tools like GPT sometimes give inconsistent answers. This is probably because SDN is still evolving and requires a deep dive into documentation to understand it fully.

The SDN I’m working with is not the simplified network automation offered by major vendors, which often come with specialized devices and simple interfaces (thanks to Zero Touch Provisioning (ZTP)). Instead, this SDN approach empowers developers to build and program custom features.

## Essential Resources for Learning SDN and NFV 📚
To kickstart your SDN journey, here are some resources and insights that have helped me:

### Containerization Basics:

Learn Docker and Kubernetes to understand how containerized environments work. Check out this [DevOps Directive course](https://courses.devopsdirective.com/) for a good foundation.
Get a grasp of gRPC, gNMI, and how northbound and southbound APIs interact in SDN.

### Research Papers:

Access research papers from [IEEE](https://ieeexplore.ieee.org/Xplore/home.jsp) to build a solid understanding of SDN concepts (northbound/southbound APIs, east-west traffic, security challenges, and comparative studies of different controllers). Use your university login for free access.

### Mininet:

Mininet is essential for simulating network topologies using Open vSwitch. For tutorials and practical steps, start with the [Mininet walkthrough](https://mininet.org/walkthrough/). You can even try p4mininet or Stratum Mininet if you’re looking to integrate P4 switches and containers.

### Controllers:

Spin up your controllers using Docker or Kubernetes—manual installation can be a hassle with old dependencies that might break your system. ONOS and OpenDaylight are popular options. For [ONOS](https://wiki.onosproject.org/), visit their wiki (use Wayback Machine if it’s down).

### P4 Programming:

P4 allows you to program the data plane for custom packet processing (e.g., protocol development, security bypass detection, DDoS mitigation). Start with [P4 tutorials](https://github.com/p4lang/tutorials) for basics, and move to [advanced guides](https://github.com/opennetworkinglab/ngsdn-tutorial) when you’re ready.

### Container Networking:

Learn about container networking concepts from [Kubenet](https://learn.kubenet.dev/).

### SDN Resources in Chinese:

If you can read Chinese, [Feisky’s SDN book](https://feisky.gitbooks.io/sdn/content/) is a fantastic resource.

## Coding is Key 🔧

Many SDN resources come with automated scripts, so to fully understand the mechanics, it’s important to read the code. ONOS tutorials (e.g., sdn-ip, fabric) are a great way to dive deeper into the codebase.

## Network Automation ≠ SDN 🤔

While some people lump network automation under SDN, there are differences. For me, I think Network Automation is subset of SDN but it is not the entire of it. Network automation often means using Python modules like Paramiko or tools like Ansible for configuration management. Learning Netconf and Restconf also helps for automation purposes. There are a lot youtube videos out there, check them out to learn! 

## Final Thoughts 💭

SDN and NFV have transformed the field of networking, making it more adaptable, programmable, and ready for the future. While the learning curve can be steep, the payoff is worth it. I hope these resources and my experience help you on your journey—stay curious and keep experimenting! 😊

Happy learning, and feel free to reach out if you have any questions or need more insights. 🚀

**Above blog is generated with the help of GPT XD**