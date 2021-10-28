# How does the Internet work?

## What is the Internet?

* **The internet** is simply a wire.
* **The internet** useful because two computers connected directly to this wire can communicate.

<p align="center">
   <img alt="internet model" src="https://github.com/KLD-VN/Internet/blob/main/how_does_the_internet_work/internet_model.jpeg" />
</p>

### What is the Intranets and Extranets

* **Intranet** are *private* networks that are restricted to members of a particular organization.

```diff
+Ex:
Host web pages for sharing department or team information, shared drives for managing key documents and files, etc. 
```

* **Extranets** is network open all or part of a private network to allow sharing and collaboration with other organizations.
* They are typically used to safely and securely share information with clients and stakeholders who work closely with a business.

```diff
+Ex
Information and file sharing, collaboration tools, discussion boards, etc.
```

<p align="center">
   <img alt="internet model" src="https://github.com/KLD-VN/Internet/blob/main/how_does_the_internet_work/internet_schema.png" />
</p>

## What is the Server?

* **A Server** is a special computer connected directly to the **Internet**.
* **Web pages** are files on that servers hard drive.
* **Each server** have a unique address ex: 72.14.205.100 (google.com), 69.63.176.140 (facebook.com)

## What is the IP address?

<p align="center">
   <img alt="ip address" src="https://github.com/KLD-VN/Internet/blob/main/how_does_the_internet_work/ip_address.png" />
</p>

* **IP address** is a unique address help computers find each other. 

## What is DSL?

* **DSL (Digital Subscriber Line)** is a family of technologies that are used to transmit **digital data** over **telephone lines**

<p align="center">
   <img alt="dsl" src="https://github.com/KLD-VN/Internet/blob/main/how_does_the_internet_work/dsl.jpeg" />
</p>

## What is Router?

* A **router** is a [networking_device] that forwards [data packets] between [computer network]

<p align="center">
   <img alt="routing" src="https://github.com/KLD-VN/Internet/blob/main/how_does_the_internet_work/routing.svg" />
</p>

## What is ISP?

* An **Internet Service Provider (ISP)** is an organization that provides many different services for accessing, using, or participating in the **Internet**

<p align="center">
   <img alt="internet model" src="https://github.com/KLD-VN/Internet/blob/main/how_does_the_internet_work/isp.png" />
</p>

## What is IRC?

* **IRC**(Internet Relay Chat) is a worldwide chat system requiring an Internet connection and an IRC client, which sends and receives messages via the IRC server.
[networking_device]: https://en.wikipedia.org/wiki/Networking_device
[data packets]: https://en.wikipedia.org/wiki/Network_packet
[computer network]: https://en.wikipedia.org/wiki/Computer_network


## Deeper dive

### A simple network

* two computer communicate with each other through 1 cable

<p align="center">
   <img alt="simple network" src="https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work/internet-schema-1.png" />
</p>

* Problem when there are many computers that need to comunicate with each other

<p align="center">
   <img alt="simple network" src="https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work/internet-schema-2.png" />
</p>

* Solve this problem -> using `router` (tiny computer)
* **Router** makes sure that a message sent from a given computer arrives at the right destination computer.

The number of cables to connect corresponds to the number of computers

<p align="center">
   <img alt="simple network" src="https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work/internet-schema-3.png" />
</p>

### A network of networks

* By connecting computers, then routers to routers, we are able to scale infinitely.

<p align="center">
   <img alt="simple network" src="https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work/internet-schema-5.png" />
</p>

* **Modem** -> turns the information from our network into information manageable by the telephone infrastructure and vice versa 

```diff
+ Bản dịch:

Modem này biến thông tin từ mạng của chúng tôi thành thông tin có thể quản lý được bởi cơ sở hạ tầng điện thoại và ngược lại

```

<p align="center">
   <img alt="simple network" src="https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work/internet-schema-6.png" />
</p>

* Send the messages from our network to the network we want to reach (Internet Service Provider `IPS`)

* **IPS** is company that manages some special `routers` -> all linked together + access other IPSs' routers

```
The Internet consists of this whole infrastructure of networks

Bản dịch:
   Internet bao gồm toàn bộ cơ sở hạ tầng của các mạng
```

## What does Network infrastructure Mean?

* **Network** infrastructure is the hardware and software resources of ans entire network that enable network connectivity

* Networking hardware:
   * Routers
   * Switches
   * LAN cards
   * Wireless routers
   * Cables

* Networking software:
   * Network operations and management
   * Operating systems
   * Firewall
   * Network security applications

* Network service
   * T-1 Line
   * DSL
   * Satellite
   * Wireless protocols
   * IP addressing

## Finding computers

* Computer linked to a network -> has a unique address that identifies it -> `IP address`

* **Domain** -> name ip address -> easy to remember + human readable


<p align="center">
   <img alt="simple network" src="https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work/dns-ip.png" />
</p>


## Internet and web

* **Internet** -> technical infrastructure which allows billions of computers to be connected all together

* **web** -> files are files located on the server hard driver (1 computer directly connected to the internet)

```
The Internet is an infrastructure and Web is a service built on the top of the infrastructure.
```