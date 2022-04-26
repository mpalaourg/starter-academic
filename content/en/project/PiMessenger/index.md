---
title: Pi Messenger
summary: Devices communication (Raspberry Pi 0) through Wi-Fi using minimum energy possible.
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

The goal is to communicate with other devices (Raspberry Pi 0), through Wi-Fi to exchange messages. Each device will represent a node in the communication network and will be responsible for generating and sending new messages, but also for forwarding messages to others so that the information is transmitted to all devices and eventually each message to be delivered to its recipient.

The functionality of the project required a two-way, simultaneous communication between the devices. Thus, a **TCP Connection** was used, with the **Server** and the **Client** running in parallel on different **threads**. Furthermore, an additional thread was used to create messages, the **Creator**. The access of the functions to the same resources - such as files - led to the use of **mutexes**, so that each resource is locked and unlocked by the same thread, and used by a single thread at a time.

The Server Thread waits in Passive Mode for devices to connect and process the messages it receives. In addition, to save energy, the Client Thread does not try to send continuously, but at regular intervals of 1 min. When it "wakes up", it checks which devices in the list are active and sends all the messages it owes them, and then moves on to the next device. Finally, to create the new messages, an interrupt was set and connected to the Creator Thread (to avoid waking up the Client), with the interrupt time being randomly selected at the time of the Creator's creation between 1 and 5 minutes and is fixed from there on.
