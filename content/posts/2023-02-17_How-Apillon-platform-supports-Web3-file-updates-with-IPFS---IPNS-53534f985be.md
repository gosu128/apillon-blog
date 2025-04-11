+++
title = "How Apillon platform supports Web3 file updates with IPFS & IPNS"
date = "2023-02-17T10:42:02+0000"
description = "Updatability of data is essential, but tricky to achieve in Web3. Apillon lets you store online files decentrally and keep them updated."
draft = false
+++

### How to keep your decentrally stored and hosted website up-to-date with IPFS & IPNS on Apillon


#### Updatability of data is essential, but tricky to achieve in Web3. With Apillon, you can store online files decentrally and keep them up to date without a heavy toll on storage, costs, or development time.

[Data mutability matters, even more so in Web3](#3f4a)
[Decentralized file storage](#e857)
[Data mutability](#406b)
[IPFS and IPNS on the Apillon platform](#6adb)

It’s one thing to upload and host a file, website, or app to a decentralized network to increase accessibility and security. But quite another to keep them regularly updated.


Here is how Apillon achieves decentralized storage with the option to frequently and cost-effectively update decentrally hosted websites and apps by integrating IPFS and IPNS.


### Data mutability matters, even more so in Web3


Digital assets, files, places, and tools are comprised of data that take up online storage space. And most require frequent updates, for example, websites, apps, and digital files like NFTs, and execute them through built-in upgrades or user contributions.


Much like in a traditional online environment, data should remain controllably mutable in Web3 to:

[Tadej Vengust](https://medium.com/u/cb13ee9d721d)
[Why decentralized storage matters for NFT metadata and your next NFT collectionInstead of overdoing what meets the eye, NFT projects should focus more on metadata and its storage to keep it…blog.apillon.io](https://blog.apillon.io/why-decentralized-storage-matters-for-nft-metadata-and-your-next-nft-collection-b7b90fc3762)

The ability to update data of online assets, files, and spaces is essential. But things get a bit complicated in Web3. How to achieve this on websites or apps that are hosted and store their data and files decentrally?


### Decentralized file storage


With Apillon, you can host your website or app and store its files through IPFS and Crust Network.


#### IPFS


IPFS is a distributed system that allows you to store and access online files, websites, and apps. When you upload a file, it gets a new hash and content identifier (CID), a unique, immutable fingerprint pointing to it. But IPFS could be difficult to implement and doesn’t inherently support file edits.

[IPFS](https://ipfs.tech/)

#### Crust Network


Crust Network is a decentralized cloud storage provider on the Polkadot network. It supports multiple storage-layer protocols, including IPFS, and delivers instantly accessible on-chain storage functions. Crustʼs technical stack also supports data manipulation and computing.

[Crust Network](https://crust.network/)

Ok, but what about the editability of data stored on a decentralized storage?


### Data mutability


Every time you upload a file or website on a decentral network of nodes through IPFS, it gets a new hash and a content identifier (CID) used as the content address.


And here is the drawback. IPFS allows you only to upload files, not to update them. What you uploaded earlier still exists on IPFS under the same CID, while a newly uploaded file, even if it’s just a new version of the existing file, gets a new CID. And every new file or website upload on Crust Network gets pinned to all contributing nodes without replacing its older versions.


So whenever you share a link to your IPFS-based file or website, it always points to the CID or the version it assumed when uploaded. In order to access the latest version of the file or website, you would have to share a new CID that was generated with the latest upload.


Generating a new CID for every file or website upload takes a toll on the storage space, and it’s simply impractical and costly.


The Apillon platform solves this by further integrating IPNS.


#### IPNS


IPNS, the InterPlanetary Name System, allows you to update data and files through mutable pointers without changing the CID, saving transaction fees and time.

[IPNS](https://docs.ipfs.tech/concepts/ipns/)

IPNS’s mutable pointers get updated every time a website or app publishes a change and work as updateable links that retain their functionality of content addressing. This way, when you share a link to your decentrally hosted website, it always points to the latest version, so you can rest assured the users access its up-to-date contents.


Now, with IPNS-based uploads, the old version of a file, website, or app does not get automatically deleted. On the Apillon platform, the old versions of Web3-hosted websites are deleted after the 6-month period. Or, upon user decision, they can remain permanently accessible, an essential feature to support the self-sovereignty of decentralized storage users.


Every Web3 project planning to upload, store, and host websites, apps, or other files that require content updates should consider utilizing IPNS, too. And with Apillon, it’s just a matter of clicks.


### IPFS & IPNS on the Apillon platform


To sum up, Web3 assets, files, websites, and apps that aim to deliver the intended value, good security, and high agility should store and host data in a decentralized way while enabling frequent and easy updates.


At the time of writing, the Apillon platform delivers the IPFS and IPNS connectivity in its Web3 Hosting service. In future upgrades, IPFS and IPNS will also be made available in the Web3 Storage service.


#### Apillon Web3 Hosting with file updateability


With Apillon, you can host your website or app on a decentralized network to make it permanently accessible, unstoppable from third-party impact, and easily updatable.


Apillon Web3 Hosting service implements AWS S3 as a cache to optimize the upload of large files, IPFS, and Crust Network to pin files on multiple IPFS nodes. Besides, it supports IPNS for frequent updates of uploaded files and data.

[IPFS](https://ipfs.tech/)
[Crust Network](https://crust.network/)
[IPNS](https://docs.ipfs.tech/concepts/ipns/)
[Apillon Platform Closed Beta walk-through — Web3 HostingThe Apillon Platform Closed Beta is live and seeks feedback from brave testers. Try the Web3 Hosting service, and see…blog.apillon.io](https://blog.apillon.io/apillon-platform-closed-beta-walk-through-web3-hosting-78cc23dee9e5)

Among the first on the market, Apillon lets you take advantage of Crust Network, IPFS, and IPNS at one spot to launch, host, and update your Web3 website or app easily, faster, and at a significantly lower price than doing it manually.


Test the waters and use Apillon for your next Web3 project.


### ⧓ About Apillon


The Apillon platform serves as a unified gateway to the Web3 services provided by linked Polkadot parachains. Following the multi-chain vision, Apillon powers the transition of developers to Web3, simplifying its adoption in the real economy, and expanding its versatility as the ecosystem grows. With Apillon, Web3 services are within reach for every developer, regardless of their background and experience with blockchain technology.


Website | Wiki | GitHub | Twitter | Telegram | LinkedIn | Reddit

[Website](https://apillon.io/)
[Wiki](https://wiki.apillon.io/)
[GitHub](https://github.com/Apillon-web3)
[Twitter](https://twitter.com/apillon)
[Telegram](https://t.me/Apillon_io)
[LinkedIn](https://www.linkedin.com/company/apillon/)
[Reddit](https://www.reddit.com/r/apillon/)