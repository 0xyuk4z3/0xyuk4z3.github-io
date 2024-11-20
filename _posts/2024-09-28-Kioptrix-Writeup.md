---
title: "Kioptrix box Writeup"

image: 

date: 2024-09-28 00:00:00 +/-0800

categories: [Writeups]

tags: [vulnerable-box]     # TAG names should always be lowercase
---
Let's start by finding out the IP address of our target box by running `arp-scan -l`

![1727509593567](../assets/img/2024-09-28-Kioptrix-Writeup/1727509593567.png)

Next is to run an nmap scan using the IP that we have obtained from the arp-scan.

nmap -T4 -A 

nmap -sS 

![1727511329312](../assets/img/2024-09-28-Kioptrix-Writeup/1727511329312.png)

The machine seems to have several services and ports open. Some things that are worthy to note are the ssh and http servers. We can further examine them.

![1727513075201](../assets/img/2024-09-28-Kioptrix-Writeup/1727513075201.png)

![1727532789146](../assets/img/2024-09-28-Kioptrix-Writeup/1727532789146.png)

![1727532143120](../assets/img/2024-09-28-Kioptrix-Writeup/1727532143120.png)

![1727533423005](../assets/img/2024-09-28-Kioptrix-Writeup/1727533423005.png)


metasploit


![1727533686263](../assets/img/2024-09-28-Kioptrix-Writeup/1727533686263.png)

![1727533817741](../assets/img/2024-09-28-Kioptrix-Writeup/1727533817741.png)

![1727533929132](../assets/img/2024-09-28-Kioptrix-Writeup/1727533929132.png)

![1727534379288](../assets/img/2024-09-28-Kioptrix-Writeup/1727534379288.png)


![1727545741010](../assets/img/2024-09-28-Kioptrix-Writeup/1727545741010.png)


![1727546724786](../assets/img/2024-09-28-Kioptrix-Writeup/1727546724786.png)![1727546763898](../assets/img/2024-09-28-Kioptrix-Writeup/1727546763898.png)

![1727546788846](../assets/img/2024-09-28-Kioptrix-Writeup/1727546788846.png)


![1727546987209](../assets/img/2024-09-28-Kioptrix-Writeup/1727546987209.png)

![1727547016017](../assets/img/2024-09-28-Kioptrix-Writeup/1727547016017.png)


Manual Exploit
