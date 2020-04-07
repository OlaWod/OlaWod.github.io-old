---
layout: post
title: 'Computer Networks'
subtitle: 'Terminologies.'
date: 2020-04-07 17:00:00 +0800
author: OlaWod
color: rgb(98,170,255)
cover: '../assets/img/cover.png'
tags: Unarchived
---
# Zero.

TCP/IP : Transmission Control protocol / Internet Protocol : an Internet protocol suite

Application layer  : SMTP, HTTP, DNS, FTP, POP3, Telnet

Transport layer 	: TCP, UDP

Internet layer 	   : IP, ICMP, ARP

Link layer 			  : PPP, Ethernet



IP address : eg, 192.30.255.113		'ifconfig -a' : see ur IP address.

DNS : Domain Name System			'ping github.com' : see IP address of this domain name, 

​															   'ping 192.30.255.113'

MAC : Media Access Control			 MAC address : eg, 02:42:c0:a8:2a:04



an IP address has 2^16 ports (0 - 65535)

> port numbers:
> - 22        SSH
> - 20/21  FTP
> - 23       Telnet
> - 25       SMTP
> - 80 /8080      HTTP

> PDU : Protocol Data Unit
> - bit
> - frame
> - packet
> - segment
> - data

# One. Link layer

PPP : Point to Point Protocol

MTU : Maximum Transmission Unit

# Two. Internet layer

A : 1.0.0.0 - 127.255.255.255 (<u>**0**1111111</u>.11111111.11111111.11111111)

B : 128.0.0.0 - 191.255.255.255 (<u>**10**111111.11111111</u>.11111111.11111111)

C : 192.0.0.0 - 223.255.255.0 (<u>**110**11111.11111111.11111111</u>.11111111)



IPv6 : eg, 2000:0000:0000:0000:0001:2345:6789:abcd

TTL : Time To Live



ARP : Address Resolotion Protocol : IP address → MAC address

RARP : Reserve ARP

ICMP : Internet Control Message Protocol (ping, traceroute)

IGMP : Internet Group Management Protocol

# Three. Transport layer

UDP : User Datagram Protocol

TCP : Transmission Control protocol

# Four. Application layer

DNS : Domain Name System

FTP : File Transfer Protocol

HTTP : HyperText Transfer Protocol

SMTP : Simple Mail Transfer Protocol

POP3 : Post Office Protocol Version 3

