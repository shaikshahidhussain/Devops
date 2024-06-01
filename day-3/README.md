# DevOps<br> Day 3: Understanding Virtual Machines

This README file covers the details of the content discussed in Day 3.

## Table of Contents
1. [Introduction](#introduction)
2. [Real-World Scenario](#real-world-scenario)
3. [Understanding Servers](#understanding-servers)
4. [Virtualization Concept](#virtualization-concept)
5. [Hypervisors](#hypervisors)
6. [Practical Example with AWS](#practical-example-with-aws)
7. [Conclusion](#conclusion)
 
## Introduction

Today is Day 3 of our DevOps Zero to Hero course. In this session, we will discuss the concept of virtual machines, which is crucial for DevOps.

## Real-World Scenario

To understand virtual machines, let’s use a real-world example:

Imagine you have a one-acre land where you've built your dream house. You realize that you only need half an acre to live comfortably. To utilize the remaining half acre efficiently, you construct another house and rent it out. Now, both you and your tenant are living happily without interfering with each other's resources. This is an efficient use of your land.

## Understanding Servers

In the software industry, we use servers to deploy applications. Here's a basic definition:
- **Server:** A server is a system that provides resources, data, services, or programs to other computers, known as clients, over a network.

### Example Setup:
- A company, example.com, purchases five servers from HP.
- Each server has significant resources (e.g., 100 GB RAM, 100 cores).
- These resources are often underutilized, leading to inefficiency.

## Virtualization Concept

To improve efficiency, we use virtualization:
- **Virtualization:** Creating virtual (rather than actual) versions of something, such as a server, a storage device, or network resources.
- **Virtual Machines (VMs):** Logical partitions within a physical server, each acting as an independent server with its own OS, CPU, memory, and storage.

### Benefits:
- Better resource utilization
- Cost-effective
- Scalability

## Hypervisors

A hypervisor is software that creates and runs VMs by logically partitioning the physical server.
### Popular Hypervisors:
- VMware
- Xen

### How it Works:
1. Install a hypervisor on the physical server.
2. Create multiple VMs on this server.
3. Each VM operates independently.

## Practical Example with AWS

Let’s see how this works in a cloud environment like AWS:

### AWS Data Centers:
- Located in various regions (e.g., Mumbai, Singapore, Ohio).
- Each data center contains numerous physical servers.

### VM Creation Process:
1. Request a VM from AWS specifying the region (e.g., Mumbai).
2. AWS allocates a VM from the physical servers in that region.
3. AWS provides access details (e.g., IP address, key pair) for the VM.

### Efficiency:
- AWS uses virtualization to serve millions of users efficiently.
- Hypervisors manage resource allocation and VM creation.

## Conclusion

Virtual machines are a critical component of modern IT infrastructure, allowing for efficient use of resources and improved scalability. Understanding VMs and hypervisors is essential for any DevOps engineer.

<strong>Happy learning! 📚✨</strong>


<h2>Follow Abhishek Veramalla for more about these <strong>Devops</strong> Journey</h2>
<h3>Follow these link for more info:<br><br> <a href="https://youtu.be/lgUwYwBozow?list=RDCMUCnnQ3ybuyFdzvgv2Ky5jnAA" target="_blank">Day-3 Devops ZERO-HERO</h3>

Thank you for your support!
