# Elastos.NET - Blockchain Powered Internet

## Overview

Elasots.NET is a portal repository to introduce Elastos serivce infrastructures related with Network. As so far as writing this document,  This repostiory includes the instroductions of:

- **Elastos Carrier** --  Peer-to-peer encrypted communication network;
- **Elastos Hive ** -- File storage network can be accessed from everywhere

All of service infrastructures are totally implemented as **Decentralized** network infrastructures  and delivers the services to the DApps on Elastos eco-system.  

## Layout of Contents

- [Elastos.NET](#elasotos-net)

  - [Overview](#overview)

  - [Layout of Contents](#layout-of-contents)

- [Elastos Carrier](#elastos-content)
  - [Introduction ](#introduction)

  - [Carrier SDKs](#carrier-sdks)

  - [Carrier Crawler](#carrier-crawler)

  - [DittoBox](#dittobox)

  - [Carrier Demo Apps](#carrier-demo-apps)

- [Elastos Hive](#elastos-hive)

  - [Introduction](#introduction)

  - [Hive Service](#hive-service)

  - [Hive SDKs](hive-sdks)

- [Contributions](#contributions)
- [Acknowledgments](#acknowledgements)
- [License](#license)

# Elastos Carrier

## 1. Introduction

A quote from the repository of  [Elastos.NET.Carrier.Native.SDK](https://github.com/elastos/Elastos.NET.Carrier.Native.SDK) as an introduction of **Carrier **:

```
Elastos Carrier is a decentralized and encrypted peer-to-peer (P2P) communication framework that routes network traffic between virtual machines and Decentralized Applications (DApps).
```

## 2. Carrier SDKs

Elastos Carrier respositories includes the followings respotiories:

- [Elastos.NET.Carrier.Native.SDK](https://github.com/elastos/Elastos.NET.Carrier.Native.SDK)
- [Elastos.NET.Carrier.Android.SDK](https://github.com/elastos/Elastos.NET.Carrier.Android.SDK)
- [Elastos.NET.Carrier.iOS.SDK](https://github.com/elastos/Elastos.NET.Carrier.iOS.SDK)
- [Elastos.NET.Carrier.Bootstrap](https://github.com/elastos/Elastos.NET.Carrier.Bootstrap)

It's worthy of mention that we supply **Carrier Native SDK** with c-style APIs and for almost all of popular platforms (**MacOS**, **Linux**, **Windows**, **Android**, **iOS** and **RaspberryPi** etc). And on top them,  we also supply **Android SDK** for android developers as well as **iOS SDK** for Apple developers.

To be noticed, all of repositories listed above are mainly under the maintenances from **Elastos Core Team**.

Besides that,  some repositories about **Carrier** also are also provided:

* [Elastos.NET.Carrier.Nodejs.SDK](https://github.com/elastos/Elastos.NET.Carrier.Nodejs.SDK)
* [Elastos.NET.Carrier.Java.SDK](https://github.com/elastos/Elastos.NET.Carrier.Java.SDK)

But the respositories listed above are mainly under the maintenances from **Community Developers**. We are so lucky to have them with us. **THANKS guys**!!!

## 3. Carrier Crawler

We have a specific respotory

- [Elastos.NET.Carrier.Crawler](https://github.com/elastos/Elastos.NET.Carrier.Crawler)

to crawl all active carrier nodes on whole Elastos carrier network, and we think it  would be popular among the Elastos Carrier Geeks.

## 4. DittoBox

A quote from the repository of **DittoBox** as an introduction:

```
Introduction

DittBox is a demo application integrating ownCloud over elastos carrier network, and through which we can access or save personal files to ownCloud server that could be deployed at home behind the router.

Highlights

This app demonstrates that all traditional http(/https)-based application can be refactored to elastos carrier apps running over carrier network. Being elastos carrier web app, the app server can be deployed without requirement of direct network accessibiblity.

For example, through elastos carrier network, you can deploy ownCloud server in local network at your home, and access ownCloud service at anywhere.
```

The repositories of **DittoBox** are listed below:

- [Elastos.DittoBox.Android](https://github.com/elastos/Elastos.DittoBox.Android)
- [Elastos.DittoBox.iOS](https://github.com/elastos/Elastos.DittoBox.iOS)
- [Elastos.DittoBox.Server](https://github.com/elastos/Elastos.DittoBox.Server) 

## 5. Carrier Demo Apps

Beside **DittoBox**, we also have developed some other carrier applications to demonstrate how to  develop an DApps with **Carrier SDK** and what capabilities or usages  the carrier DApps can cope with.

- [[Elastos.NET.Carrier.Samples.Android](https://github.com/elastos/Elastos.NET.Carrier.Samples.Android)]

- [Elastos.Carrier.Demo.Remoter.Android](https://github.com/elastos/Elastos.Carrier.Demo.Remoter.Android)

- [Elastos.Carrier.Demo.FileTransfer.Android](https://github.com/elastos/Elastos.Carrier.Demo.FileTransfer.Android)

- [Elastos.Carrier.Demo.Remoter.iOS](https://github.com/elastos/Elastos.Carrier.Demo.Remoter.iOS)

We sincerely hope developers from Elastos community around world to join with us.

# Elastos Hive 

## 1. Introduction

An quote from repository of Hive **DevDocs** as an introduction:

```
Elastos Hive is a basic service infrastructure that provide storage capabilities to dApps with decentralized characteristics, which leveraged standard IPFS/Cluster open source projects with some necessary refits.
```

Elastos Hive project is made of two parts:

- Hive Services - Backbone services compostied of Hive **IPFS** and **Cluster** daemons. 
- Hive SDKs - SDKs used front-end DApps.

## 2. Hive Services

Elastos Hive services repositories:

- [Elastos.NET.Hive.DevDocs](https://github.com/elastos/Elastos.NET.Hive.DevDocs)
- [Elastos.NET.Hive.IPFS](https://github.com/elastos/Elastos.NET.Hive.IPFS)
- [Elastos.NET.Hive.Cluster](https://github.com/elastos/Elastos.NET.Hive.Cluster)
- [Elastos.NET.Hive.HttpAPITests](https://github.com/elastos/Elastos.NET.Hive.HttpAPITests)

## 3. Hive SDKs

Elastos SDKs repositories:

- [Elastos.NET.Hive.Native.SDK](https://github.com/elastos/Elastos.NET.Hive.Native.SDK) -- **In Progress** 
- [Elastos.NET.Hive.Java.SDK](https://github.com/elastos/Elastos.NET.Hive.Java.SDK)  -- **Listed and might implement**
- [Elastos.NET.Hive.Android.SDK](https://github.com/elastos/Elastos.NET.Hive.Android.SDK) -- **In Progess**
- [Elastos.NET.Hive.iOS.SDK](https://github.com/elastos/Elastos.NET.Hive.iOS.SDK)  -- **Listed, and will implement **

# Contributions

We welcome any contribution to Elastos Hive projects.

# Acknowledgments

A sincere thank you to all teams and projects that we rely on directly or indirectly, especially`go-ipfs` Project.

# License
This project is licensed under the terms of the [MIT license](https://github.com/elastos/Elastos.NET/blob/master/LICENSE).