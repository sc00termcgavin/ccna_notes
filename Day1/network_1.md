# Network Fundamentals

## Table of contents

- [Network Fundamentals](#network-fundamentals)
  - [Table of contents](#table-of-contents)
  - [Network](#network)
  - [Routers](#routers)
  - [Switches](#switches)
    - [Layer2](#layer2)
    - [Layer3](#layer3)
  - [Firewall](#firewall)
    - [Host-Based Firewalls](#host-based-firewalls)
    - [Intrusion Prevention System (IPS)](#intrusion-prevention-system-ips)
  - [Access Points (APs)](#access-points-aps)
  - [Controllers (Wireless LAN Controllers - WLCs)](#controllers-wireless-lan-controllers---wlcs)
  - [Endpoints](#endpoints)
  - [Power over Ethernet (PoE)](#power-over-ethernet-poe)

## Network

A computer network is a digital telecommunications network which allows *nodes* to share resources

## Routers

* have fewer network interfaces/ports than switches
* are used to provide connectivity **between** LANs and therefor used to send data over the internet

## Switches

You typically don't connect end-hosts or PCs directly to each other, you aggregate the connections to a device called a "switch".

* Have many network interfaces/ports for end hosts to connect to (usually 24+)
* Provide connectivity to hosts within the same LAN (Local Area Network)
* Do not provide connectivity between LANs or over the internet

### Layer2

* Operate at the Data Link Layer
* Uses MAC addressing scheme to forward frames between devices.

### Layer3

* Operate at the Data Link or Network Layer.
* Uses IP addressing scheme like a router.
* Reduces network congestion by making faster routing decisions.

## Firewall

* Hardware devices that filter traffic between networks
* Monitor and control network traffic based on defiend rules. 
* They can be placed in or outside the network.
* Considered **Next Gen firewalls** when they include more advanced filtering capabilities.

### Host-Based Firewalls

Software applications that filter traffic entering and exiting a host machine like a PC.

### Intrusion Prevention System (IPS)

IPS monitor traffic and **Actively** blocks malicious activities before they reach the target. 

## Access Points (APs)

An Access Point (AP) is a device that enables wireless devices to connect to a wired network. It serves as a bridge between Wi-Fi clients and the local area network (LAN).

## Controllers (Wireless LAN Controllers - WLCs)

A Wireless LAN Controller (WLC) is a network device that manages multiple access points in a wireless network. It centralizes control and improves security, scalability, and performance.

## Endpoints

An endpoint is any device that connects to a network and serves as an access point for users or applications.

## Power over Ethernet (PoE)

Power over Ethernet (PoE) is a technology that allows network cables (Ethernet) to deliver both data and electrical power to connected devices.