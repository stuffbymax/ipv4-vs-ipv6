# Understanding IPv4 and IPv6

## What is IPv4?

IPv4 is the first version of the internet protocol to be widely used. It stands for, unsurprisingly, **Internet Protocol Version 4**. It was first released in 1983 and is still in use today.

IP addresses using this protocol are groups of 11 digits separated by periods, called dotted hexadecimal notation. An example of an IPv4 address would be:

```
192.168.10.150
```


Each number in an IP address stores information that tells data packets where to go. Each group of numbers can store one byte of information, and there are four groups in each IPv4 address, which adds up to 32 bits total of information storage. For that reason, the IPv4 addressing system is known as a **32-bit system**.

This system allows for up to **4.3 billion unique addresses**, which sounds like a lot until you realize just how many people and devices are connected to the internet today. Devices in the **Internet of Things (IoT)** also need IP addresses. That explosion of use as our lives become increasingly internet-connected means the IPv4 addressing system is running out of space. Enter IPv6.

## What Is IPv6?

IPv6 is a newer version of the internet protocol with longer addresses containing both numbers and letters. Though newer than version 4, it's not that new: it was first deployed in **1999**.

IPv6 addresses have **128 bits** of information storage. They're written in hexadecimal colon notation, meaning each group of numbers and letters is separated from the next by a colon (`:`) instead of a period.

An example IPv6 address would look like this:

```
3002:0bd6:0000:0000:0000:ee00:0033:6778
```


This longer addressing system supports **2^128 unique addresses**, or 1,028 times the number of IPv4. 4.3 billion multiplied by 1,028 is... enough unique IP addresses that we won't have to worry about running out of them anytime soon.

The main differences between the two are the length of each IP address and the overall number of unique addresses available, but there are additional, more technical variations between the two versions.

## Main Features of IPv4

- Connectionless Protocol
- Allows creation of a simple virtual communication layer over multiple devices
- Requires less memory
- Increased ease of remembering addresses
- Already supported on millions of devices

## Main Features of IPv6

- No NAT (Network Address Translation) allowing end-to-end connectivity at the IP layer
- Multi-casting (transmission of a data packet to multiple destinations at once) is included standard
- Prevents private address collisions
- Simpler header format
- Simplified, more efficient routing overall
- True quality of service (QoS), or "flow labeling"
- Built-in security layer (IPsec)
- Flexible options and extensions
- Easier administration (no more DHCP)

## Key Takeaways

IPv6 is more secure, more flexible, and allows for a much greater number of unique addresses than IPv4. IPv4 and IPv6 are also written in different formats, with IPv4 made up of numbers separated by periods and IPv6 addresses made up of numbers and letters, separated by colons.

