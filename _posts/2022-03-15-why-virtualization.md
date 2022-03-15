---
toc: true
layout: post
description: What is the buzz about virtualization? Why is it required?
categories: [virtualization, hypervisor, blog, VMs]
title: Whys and Hows of virtualization
image: images/dilbert_virtualization.jpg
---

Let’s start with an imaginary story:

*Once upon a time - there was a bank (Gringotts Wizarding Bank maybe). The employees (or Goblins), being the most sincere and hard working - had all their information duly entered into ledgers. Any one having an account with them - had to physically come in and identify themselves, entries being made into the record keeping books and only then accompanied to their lockers. Now Goblins might have magical skills to maintain and search this mammoth of physical ledgers - but the day the dragon unleashed itself and burnt the entire bank down - it was all gone.* 😱

This might be a story but the problem is very real. Before the advent of computers - we indeed used to have banks with all the data, records and everything being maintained in physical books. With computers - the data started to be virtualized. The data was stored in and fetched from databases. Applications were developed to ease the user experience - and these applications started to be hosted on server systems.

Here came the second twist in the story. Imagine today - we are using an application on our laptops. Now, our laptop can have any combination of:

- processors (intel i3/i5/i7/i9/.., m1) and architectures (amd, arm...)
- graphic cards (NVDIA, RADEON...)
- Operating System (windows, macOS, Linux flavours)

This was not very different even earlier. Different companies were bringing different hardware/platforms to the market and the user base was growing diverse by the day.😵 An analysis[^1] states - before virtualization, only 15-30% of server systems were utilized. Why? Because hardware and OS were tightly coupled. Each server machine was a giant, high performance system with a limitation of only one OS. So, the need for different OS for supporting different Eco-systems could not be handled by a single server.

Now you may ask, why would the servers have such high resources? They could be built as per the need.🤷‍♀️ There was the problem of scalability. Imagine today you are building an application - and you have a small user base. Tomorrow as you grow, the user base grows exponentially. To support that high load, the system should be equipped - people cannot imagine changing servers every once in a while. So - that was the catch net. Which caused massive under-utilization, high costs and a lot more issues.

Virtualization came to the rescue. What exactly is virtualization? It is a way to make things virtual!! Don’t kill me for this one.. But indeed - it is more like creating anything - from an operating system, an application to an entire server - logical instead of physical.  The same servers could be used as the base hardware and the virtual operating systems could run on the main host operating system. 

![]({{ site.baseurl }}/images/movementToVirtualization.png "Source credit: www.ibm.com")

This opened up an arena of limitless possibilities.[^3] [^4]

- **The costs came down** - fewer hardware servers and related resources could achieve much more computational efficiency. This in place reduced the manual effort needed to maintain the huge number of physical servers, the costs of cooling, carbon footprint and more.
- **There was marked reduction in downtime and disaster recovery was faster** - Again manual effort - if a physical server goes down, it needs to be manually taken care of. If a virtual server goes down - it can be quickly replicated to create a new virtual server while the root cause analysis of the disaster is done in the backend.
- **Scalability** - Anyone could create additional resources as required by many applications, such as by adding extra servers – all on an as-needed basis, without any significant investments in time or money.

Now we get it - yes indeed it was a game changer. But - how does it do this? How does virtualization work?

For that - let’s introduce the concept of hypervisors.[^2] Hypervisor is a software, like a thin layer that works on top of the host and facilitates virtualization. What it does is - it manages and allocates the physical resources to the Virtual Machines (VMs) , thus enabling multiple operating systems and applications to run in parallel. Even VMs can be moved from one physical server to another real quick.

![]({{ site.baseurl }}/images/Hypervisors.png "Source credit: www.ibm.com")

**Types of Hypervisors:**

- **Type 1 (Bare Metal Hypervisors)** - runs directly on host hardware. Most frequently type used - more secure, reduces latency.
- **Type 2 (Hosted Hypervisors)** - Has layer of host operating system between physical server and hypervisor. Mostly used for end user virtualization. Less frequently used.

We will delve deep into the actual working of hypervisors in a separate blog. That is a vast topic in itself.

So I hope I have been able to make you relate to the concept of virtualization a little more than where you were at the beginning of this blog. In the next post, we will discuss of the advent of cloud..

Hope to see you there.. Okka Bye 👋🏻 👩🏻‍💻



[^1]: https://phoenixnap.com/kb/what-is-server-virtualization

[^2]: https://developer.ibm.com/articles/cl-hypervisorcompare

[^3]: https://www.ibm.com/cloud/blog/5-benefits-of-virtualization

[^4]: https://www.businessnewsdaily.com/6014-pros-cons-virtualization.html