+++
title = "FAQ: Apillon Web3 Storage"
date = "2023-05-18T12:49:33+0000"
description = "Find answers to your questions on the Apillon Web3 Storage service, how to store files on a decentralized network, and more."
draft = false
+++

### FAQ: Apillon Web3 Storage


#### Find answers to your questions on the Apillon Web3 Storage service, how to store files on a decentralized network, and more.

[Apillon Web3 Storage service](#80e6)
[Crust Network, IPFS and IPNS](#0282)
[Decentralized file storage with Apillon](#a5c5)

### Apillon Web3 Storage service


#### What is the Web3 Storage service on Apillon?


Apillon Web3 Storage is a Web3-based storage service that allows you to increase the accessibility of your files (or that of your website or app) by storing them on a decentralized network of nodes around the globe.


#### How to use Apillon Web3 Storage?


To start using Apillon Web3 Storage service, you should first create a new bucket, a highly dynamic way of using decentralized storage.


For a step-by-step process, follow this guide. 👇

[Apillon Platform Closed Beta walk-through — Web3 StorageThe Apillon Platform Closed Beta is live and invites participants to share feedback. Learn more and help us improve…blog.apillon.io](https://blog.apillon.io/apillon-platform-closed-beta-walk-through-web3-storage-1e76bfaa928a)

#### How does it work?


When you upload files and store them with Apillon Web3 Storage buckets, they first land on AWS S3, a reputable centralized cloud provider, to ensure fast file capture.


Once the files are received, they proceed to the decentralized Apillon IPFS gateway, where Crust Network initiates the pinning and replication process.


As the files become accessible on the IPFS network, Crust Network spreads them through multiple IPFS nodes globally, ensuring file distribution and decentralized accessibility.


### Crust Network, IPFS, and IPNS


#### How do Crust, IPFS, and IPNS help store files decentrally (and keep them editable)?


Apillon Web3 Storage implements AWS S3 as a cache to optimize the upload of large files, IPFS, and Crust Network to pin files on multiple IPFS nodes.

[IPFS](https://ipfs.tech/)
[Crust Network](https://crust.network/)

IPFSWhen you upload a file to IPFS, it’s split into smaller chunks and cryptographically hashed. It also receives a unique fingerprint called a content identifier (CID), which acts as a permanent record of your file as it is at that point in time.

[IPFS](https://ipfs.tech/)

Crust NetworkCrust Network is a decentralized cloud storage provider on Polkadot. It supports multiple storage-layer protocols such as IPFS, and delivers instantly accessible on-chain storage functions. Crustʼs technical stack also supports data manipulation and computing.

[Crust Network](https://crust.network/)

IPNSThe InterPlanetary Name System (IPNS) allows for creating mutable pointers to CIDs, a type of links that are updateable and mutable, without harming the content, its addressing and verifiability. While the CID created during file hashing on IPFS is immutable, the IPNS allows you to update website data and files frequently without having to create a new CID every time.

[InterPlanetary Name System](https://docs.ipfs.tech/concepts/ipns/#mutability-in-ipfs)
[How Apillon platform supports Web3 file updates with IPFS & IPNSUpdatability of data is essential, but tricky to achieve in Web3. Apillon lets you store online files decentrally and…blog.apillon.io](https://blog.apillon.io/how-apillon-platform-supports-web3-file-updates-with-ipfs-ipns-53534f985be)

### Decentralized file storage with Apillon


#### Storage bucket


What is a storage bucket on the Apillon platform?Storage bucket represents a more dynamic way of using decentralized storage in Web3 development. It is a virtual container holding directories and files in a hierarchical structure with optional multiple subdirectories.Storage buckets are necessary when using the Apillon Web3 Storage service. Once ready, they enable decentralized file storage both on the Apillon dashboard and via the API endpoints.


What’s the capacity of storage buckets and how many can I create?The current freemium plan of the Apillon dashboard allows you to use one 5 GB bucket of decentralized storage. In future versions, the option to choose 100 GB storage buckets under paid plans will be made available.If you want to have your decentralized storage capacity increased, please contact our admins on the Apillon Discord channel with the requirements of your specific Web3 project.

[Apillon Discord channel](https://discord.gg/apillon)

What is the cost of a storage bucket?In the current stage, the Apillon platform only offers freemium plans, meaning all supported services are free of charge.Even when the platform upgrades to paid subscription plans, a form of a freemium plan will continue existing and supporting smaller-scale Web3 projects.


#### Storing and deleting files


What kind of data can I upload to Apillon?You can upload all kinds of data and any file types you want. However, uploading ethically sensitive material is prohibited.You can upload files directly from your local drive, or you may use API to sync with other Web3 services you might use and maintain a dynamic approach to sourcing data from different apps and platforms.


Where are my files stored?The files you upload via Apillon Web3 Storage service are stored on IPFS and pinned on Crust Network. No files are stored locally on the Apillon dashboard or Apillon’s server.


What happens to my files if Apillon ceases operating?The Apillon platform serves as a gateway between the Web2 and Web3 worlds. As such, the platform and all its logic live on AWS. Only when a file is uploaded via Web3 Storage it lives permanently on the decentralized network, regardless of whether the Apillon platform is down.To access IPFS-based files outside Apillon and ensure uninterrupted access, you should keep their IPFS links.


How to delete files from Apillon Web3 Storage?The decentralized storage with Apillon and Crust’s pinning and replication services is paid upfront for a minimum of 6 months. Apillon has no control over amending that period, so all files you deploy to Apillon storage buckets will remain accessible for that long.If you decide to delete a file before the end of the 6-month period, Apillon does not extend the storage lease on Crust, and the file gets deleted on all IPFS instances.Apillon further artificially lowers the file deletion period to 3 months, making file storage more dynamic. After this period, the deleted files in your storage bucket are emptied, and your storage bucket capacity can accept new files.


#### API connectivity


How to use Apillon Web3 Storage service in external projects?To integrate the Apillon Web3 Storage module in external projects, apps or websites, use the Apillon API, which is a set of RESTful API endpoints. Unless clearly marked as public, all routes are private and require an API key.To use Apillon Web3 Storage APIs, you should first create a bucket on the Apillon dashboard.The process of uploading files via Apillon Web3 Storage API is following:

[Apillon dashboard](https://wiki.apillon.io/build/app.apillon.io/service/storage)

Source the Apillon Web3 Storage API. 👇

[Apillon API | Apillon WikiApillon Wikiwiki.apillon.io](https://wiki.apillon.io/build/3-apillon-api.html#web3-storage-api)

Please note that Apillon documentation for API connectivity is a matter of continuous editing and improvement.


Does API work if the Apillon Web3 Storage service is down?In case Apillon Web3 Storage service is down, so is its API, and in this case you can’t call the smart contract from the API.However, once the smart contract using Web3 Storage service is deployed, it’s live on the blockchain network, so it can be called from a wallet and works normally.


For more details on the Crust-supported Web3 Storage service on Apillon platform, check out the guide below and Apillon Wiki.

[Apillon Platform Closed Beta walk-through — Web3 StorageThe Apillon Platform Closed Beta is live and invites participants to share feedback. Learn more and help us improve…blog.apillon.io](https://blog.apillon.io/apillon-platform-closed-beta-walk-through-web3-storage-1e76bfaa928a)
[Apillon Web3 services | Apillon WikiApillon integrates multiple parachains and offers access to them in a unified way via modules on the developer…wiki.apillon.io](https://wiki.apillon.io/build/2-web3-services.html#web3-storage)
