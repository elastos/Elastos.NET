# Elastos.NET - Blockchain Powered Internet

### Overview

Elasots.NET is a portal repository to introduce Elastos serivce infrastructures related with Network. As so far as writing this document,  This repostiory includes the instroductions of:

- **Elastos Carrie** --  Peer-to-peer encrypted communication network;
- **Elastos Hive** -- File storage network can be accessed from everywhere.

All of service infrastructures are totally implemented as **Decentralized** network infrastructures  and delivers the services to the DApps on Elastos eco-system.  

### Layout of Contents

- [Elastos.NET](#elasotos-net)
  - [Overview](#overview)
  - [Layout of Contents](#layout-of-contents)
- [Elastos Carrier](#elastos-carrier)
  - [Carrier Introduction ](#carrier-introduction)
  - [Carrier SDKs](#carrier-sdks)
  - [Carrier Crawler](#carrier-crawler)
  - [DittoBox](#dittobox)
  - [Carrier Demo Apps](#carrier-demo-apps)
- [Elastos Hive](#elastos-hive)
  - [Hive Introduction](#hive-introduction)
  - [Hive Service](#hive-service)
  - [Hive SDKs](hive-sdks)
- [Contributions](#contributions)
- [License](#license)

# Elastos Carrier

### Carrier Introduction

A quote from the repository of **Elastos.NET.Carrier.Native.SDK** as an introduction to **Carrier **:
```
Elastos Carrier is a decentralized and encrypted peer-to-peer (P2P) communication
framework that routes network traffic between virtual machines and Decentralized
Applications (DApps).
```

### Carrier SDKs

Elastos Carrier SDKs  includes the following repositories:

- [Elastos.NET.Carrier.Native.SDK](https://github.com/elastos/Elastos.NET.Carrier.Native.SDK)
- [Elastos.NET.Carrier.Android.SDK](https://github.com/elastos/Elastos.NET.Carrier.Android.SDK)
- [Elastos.NET.Carrier.iOS.SDK](https://github.com/elastos/Elastos.NET.Carrier.iOS.SDK)
- [Elastos.NET.Carrier.Bootstrap](https://github.com/elastos/Elastos.NET.Carrier.Bootstrap)

As repsitories described, we supply **Carrier Native SDK** with c-style APIs and for almost typical platforms (**MacOS**, **Linux**, **Windows**, **Android**, **iOS** and **RaspberryPi** etc). And on top them,  we also supply **Android SDK** for android developers as well as **iOS SDK** for Apple developers.

To be noticed, all of repositories listed above are mainly under the maintenance from **Elastos Core Team**.

Besides that,  there are the repositories about **Carrier SDKs**  that have been developed and being under maintenance from Elastos community as well:

* [Elastos.NET.Carrier.Nodejs.SDK](https://github.com/elastos/Elastos.NET.Carrier.Nodejs.SDK)
* [Elastos.NET.Carrier.Java.SDK](https://github.com/elastos/Elastos.NET.Carrier.Java.SDK)

Any contributions to Elastos carrier would be appreciated in any way. 

### Carrier Crawler

In order to crawl all active carrier nodes as much as possible on Elastos carrier network, we also developed an **elacrawler** application with the following repository:

- [Elastos.NET.Carrier.Crawler](https://github.com/elastos/Elastos.NET.Carrier.Crawler)

We think this repository would be popular among the Elastos carrier **Geeks**.

### DittoBox

A quote from the repository of **DittoBox** as an introduction:

```
Introduction

DittBox is a demo application integrating ownCloud over elastos carrier network, and
through which we can access or save personal files to ownCloud server that could be
deployed at home behind the router.

Highlights

This app demonstrates that all traditional http(/https)-based application can be
refactored to elastos carrier apps running over carrier network. Being elastos carrier
web app, the app server can be deployed without requirement of direct network
accessibiblity.

For example, through elastos carrier network, you can deploy ownCloud server in local
network at your home, and access ownCloud service at anywhere.
```

The repositories of **DittoBox** are listed below:
- [Elastos.DittoBox.Android](https://github.com/elastos/Elastos.DittoBox.Android)
- [Elastos.DittoBox.iOS](https://github.com/elastos/Elastos.DittoBox.iOS)
- [Elastos.DittoBox.Server](https://github.com/elastos/Elastos.DittoBox.Server) 

### Carrier Demo Apps

Besides **DittoBox**, we also have developed some other carrier applications as demos to show how to  develop dApps with **Carrier SDKs** and what capabilities or usages  the carrier DApps can cope with or privide.

All repositories to carrier demos are listed below:

- [Elastos.Carrier.Demo.Remoter.iOS](https://github.com/elastos/Elastos.Carrier.Demo.Remoter.iOS)
- [Elastos.Carrier.Demo.Remoter.Android](https://github.com/elastos/Elastos.Carrier.Demo.Remoter.Android)
- [Elastos.Carrier.Demo.FileTransfer.Android](https://github.com/elastos/Elastos.Carrier.Demo.FileTransfer.Android)

# Elastos Hive 

### Hive Introduction

An quote from repository of Hive **DevDocs** as an introduction:

```
Elastos Hive is a basic service infrastructure that provide storage capabilities to
dApps with decentralized characteristics, which leveraged standard IPFS/Cluster open
source projects with some necessary refits.
```

Elastos Hive project is mainly made of two parts:

* **Hive Services** - Backbone services composited of Hive **IPFS** and **Cluster** daemons.
* **Hive SDKs** - SDKs used by front-end dApps.

### Hive Services

Elastos Hive use **ipfs** and **ipfs-cluster** as the base infrastructure to save Elastos data, and it includes the followings repositories:

- [Elastos.NET.Hive.DevDocs](https://github.com/elastos/Elastos.NET.Hive.DevDocs)
- [Elastos.NET.Hive.IPFS](https://github.com/elastos/Elastos.NET.Hive.IPFS)
- [Elastos.NET.Hive.Cluster](https://github.com/elastos/Elastos.NET.Hive.Cluster)
- [Elastos.NET.Hive.HttpAPITests](https://github.com/elastos/Elastos.NET.Hive.HttpAPITests)

Before you try to involve into Hive storage network, you have to reference HTTP APIs documents in repo **DevDocs**.

### Hive SDKs

Elastos Hive SDKs is a set of APIs to provide for front-end dApps, and will provide for most platforms via these repositories:

- [Elastos.NET.Hive.Native.SDK](https://github.com/elastos/Elastos.NET.Hive.Native.SDK) -- **In Progress** 
- [Elastos.NET.Hive.Java.SDK](https://github.com/elastos/Elastos.NET.Hive.Java.SDK)  -- **To implement**
- [Elastos.NET.Hive.Android.SDK](https://github.com/elastos/Elastos.NET.Hive.Android.SDK) -- **In Progess**
- [Elastos.NET.Hive.iOS.SDK](https://github.com/elastos/Elastos.NET.Hive.iOS.SDK)  -- **To implement**

# Contributions

We sincerely hope developers from Elastos community around world to join with us.

# License
This project is licensed under the terms of the [MIT license](https://github.com/elastos/Elastos.NET/blob/master/LICENSE).