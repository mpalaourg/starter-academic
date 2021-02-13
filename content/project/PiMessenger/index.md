---
title: Pi Messenger
summary: Communicate with other devices (Raspberry Pi 0) through WiFi using minimum energy possible.
tags:
- Raspberry Pi 0
- embedded systems
- threading
- networking
- C
date: "2016-04-27T00:00:00Z"

image:
  caption: ""
  focal_point: Smart

url_code: "https://github.com/mpalaourg/RTES_FinalTask"
url_pdf: ""
url_slides: ""
url_video: ""
---

<div style="text-align: justify"> <p>
The goal is to communicate with other devices (Raspberry Pi 0), through WiFi to exchange messages. Each device will represent a node in the communication network and will be responsible for generating and sending new messages, but also for forwarding messages to others so that the information is transmitted to all devices and eventually the message will be delivered to its recipient.

The characteristics of the project required a two-way, simultaneous communication between the devices. Thus, <b>TCP Connection</b> was used, with the <b>Server</b> and the <b>Client</b> running in parallel on different <b>threads</b>. Furthermore, an additional thread was used to create messages, the <b>Creator</b>. Τhe access that all functions had to the same resource -such as files- made it necessary to use <b>mutexes</b>, so that each resource is locked and unlocked by the same thread, i.e. to be used by a single thread at a time.

Server Thread waits in Passive Mode for devices to connect and process the messages it receives. In addition, to save energy, the Client Thread does not try to send continuously, but at regular intervals of 1 min. When it "wakes up", it checks which devices in the list are active and sends them all the messages it owes, then moves on to the next device. Finally, to create the new messages, an interrupt was set and connected to the Creator Thread (to avoid waking up the Client), with the interrupt time being randomly selected at the time of the Creator creation between 1 and 5 minutes and is stable from there on.
</p> </div>
