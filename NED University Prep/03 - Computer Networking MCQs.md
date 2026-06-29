# Computer Networking (5 Questions) — IPv4 Addressing & Network Topology

## A. IPv4 Addressing

**Q1.** How many bits does an IPv4 address have?
A) 16  B) 32  C) 64  D) 128
**Answer: B) 32**

**Q2.** An IPv4 address is normally written as:
A) Hexadecimal numbers separated by colons  B) Four decimal numbers (0–255) separated by dots  C) A single binary string  D) A single decimal number
**Answer: B)** — e.g. 192.168.1.1 (this format is called "dotted decimal notation")

**Q3.** What is the maximum value of any single segment (octet) in an IPv4 address?
A) 128  B) 255  C) 256  D) 512
**Answer: B) 255** — each octet is 8 bits, and 8 bits can represent 0–255

**Q4.** Which of these is a **valid** IPv4 address?
A) 192.168.1.300  B) 192.168.1.1  C) 192.168.1  D) 192.168.1.1.1
**Answer: B)** — the others either exceed 255, have too few segments, or have too many.

**Q5.** Which IP range is reserved for "loopback" (a device talking to itself, e.g. 127.0.0.1 = localhost)?
A) 10.0.0.0/8  B) 127.0.0.0/8  C) 192.168.0.0/16  D) 172.16.0.0/12
**Answer: B) 127.0.0.0/8**

**Q6.** Which of these is a **private** IP address (not directly routable on the public internet)?
A) 8.8.8.8  B) 192.168.1.1  C) 1.1.1.1  D) 172.217.0.0
**Answer: B) 192.168.1.1** — private ranges are 10.0.0.0/8, 172.16.0.0/12, and 192.168.0.0/16

**Q7.** In IPv4 **Class A** addresses, the first octet range is:
A) 1–126  B) 128–191  C) 192–223  D) 224–239
**Answer: A) 1–126**

**Q8.** In IPv4 **Class B** addresses, the first octet range is:
A) 1–126  B) 128–191  C) 192–223  D) 224–239
**Answer: B) 128–191**

**Q9.** In IPv4 **Class C** addresses, the first octet range is:
A) 1–126  B) 128–191  C) 192–223  D) 224–239
**Answer: C) 192–223**

**Q10.** A "subnet mask" is used to:
A) Encrypt network traffic  B) Separate the network portion from the host portion of an IP address  C) Assign MAC addresses  D) Block viruses
**Answer: B)**

**Q11.** In CIDR notation, what does the "/24" in `192.168.1.0/24` mean?
A) 24 hosts are allowed on the network  B) The first 24 bits represent the network portion of the address  C) The address has 24 segments  D) The port number is 24
**Answer: B)**

## B. Network Topology

**Q12.** In a **STAR** topology, all devices connect to:
A) Each other directly  B) A central hub or switch  C) A single shared cable  D) Nothing — it's wireless-only by definition
**Answer: B)**

**Q13.** In a **BUS** topology, all devices share:
A) A central hub  B) A single common cable (backbone)  C) Multiple redundant cables  D) A ring-shaped cable
**Answer: B)**

**Q14.** In a **RING** topology, data travels:
A) Through a central hub  B) In a circular path from one device to the next, around the ring  C) Directly between every pair of devices  D) In a random direction
**Answer: B)**

**Q15.** In a **MESH** topology, every device is connected to:
A) Only one central device  B) Every other device directly  C) A single shared cable  D) Nothing
**Answer: B)** — gives high redundancy/reliability but is expensive and complex to wire.

**Q16.** Which topology is most vulnerable to a **total network failure** if its one central device breaks down?
A) Mesh  B) Star  C) Ring  D) Bus
**Answer: B) Star**

**Q17.** A topology that combines two or more different topology types is called:
A) Star  B) Bus  C) Hybrid  D) Ring
**Answer: C) Hybrid**

## C. Bonus: Devices & Protocols (often asked alongside topology/IP questions)

**Q18.** Which device forwards data **between different networks** based on IP addresses?
A) Switch  B) Hub  C) Router  D) Repeater
**Answer: C) Router**

**Q19.** Which device simply **broadcasts** incoming data to all connected ports, with no intelligence about where it should actually go?
A) Router  B) Hub  C) Switch  D) Gateway
**Answer: B) Hub**

**Q20.** Which protocol is connection-oriented and guarantees **reliable** delivery of data?
A) UDP  B) TCP  C) IP  D) HTTP
**Answer: B) TCP**

**Q21.** Which protocol translates domain names (like `google.com`) into IP addresses?
A) DHCP  B) DNS  C) FTP  D) SMTP
**Answer: B) DNS**

**Q22.** Which protocol automatically assigns IP addresses to devices joining a network?
A) DNS  B) DHCP  C) HTTP  D) TCP
**Answer: B) DHCP**

---

## Quick-recall table

| Class | First octet range |
|---|---|
| A | 1–126 |
| B | 128–191 |
| C | 192–223 |

| Topology | Key weakness |
|---|---|
| Star | Central hub fails → whole network down |
| Bus | Cable break → whole network down |
| Ring | One device/link failure can break the loop |
| Mesh | Expensive, but most fault-tolerant |
