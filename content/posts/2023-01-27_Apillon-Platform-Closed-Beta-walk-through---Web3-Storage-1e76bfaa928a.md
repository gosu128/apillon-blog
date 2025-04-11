+++
title = "Apillon Platform Closed Beta walk-through — Web3 Storage"
date = "2023-01-27T10:50:41+0000"
description = "The Apillon Platform Closed Beta is live and invites participants to share feedback. Learn more and help us improve Web3 Storage service."
draft = false
+++

### Apillon Platform Closed Beta walk-through — Web3 Storage


#### The Apillon Platform Closed Beta is live and invites participants to share feedback. Learn more about the Web3 Storage service, test, suggest, and help us improve.

[Good to know](#3f68)
[Account log in and access code](#a4ea)
[Create a Web3 project](#3bbb)
[Web3 Storage](#5a96)
[Share your feedback](#2a29)

Apillon Closed Beta gives you an opportunity to try and test the platform’s Web3 services while still in the development phase. As we strive to deliver only the best features to the developer community, we invite registered users to share feedback and suggestions on what could be done better or differently. Every opinion counts.

[Apillon launches an invitation-only Closed Beta of the Web3 development platformApillon is excited to offer the first test and a chance for a practical walk-through of a simplified Web3 building…blog.apillon.io](https://blog.apillon.io/apillon-launches-an-invitation-only-closed-beta-of-the-web3-development-platform-a075c38273a3)

In this walk-through post, we take you from registration to taking advantage of Web3 Storage, one of the services available in Apillon Closed Beta.


But first, there are some things you should keep in mind.


### Good to know


In its current state, Apillon is a Web3 hybrid platform, and certain services are still being run by centralized providers to ensure fast development and optimal UI. However, the platform’s back end is designed to gradually progress towards a fully Web3 infrastructure, and newer versions will deliver more decentralized services.


You should also understand that Apillon Closed Beta delivers no guarantees, either regarding functionalities or access, as it is intended for testing purposes only. Beta features are also limited in some aspects and will become more accessible as the platform evolves.


Now, let’s begin.


### Account log in and access code


To participate in the Apillon Closed Beta and test its features, go to http://app.apillon.io/ and create an account. If you already have one, simply log in.

[http://app.apillon.io/](http://app.apillon.io/)

At the bottom of the intro page, you will find a Closed Beta code you need to access Closed Beta functionalities. Copy and paste it to our closed-beta channel on Apillon Discord. Soon after, you should receive an email invitation to Closed Beta with access to Apillon Web3 services.

[Apillon Discord](https://discord.gg/yX3gTw36C4)

Once your access is granted, you can proceed to starting your first Web3 project with Apillon.


### Create a Web3 project


In the top left corner of the screen, click Add new project, set your project name and description in the pop-up window, and click Create new project.


Once created, you can check more details under Project overview in the menu on the left.


Now, it’s time to try and test Web3 services.


In the Closed Beta, you can attach Web3 Storage and Web3 Hosting service. In this guide, we’ll focus on using the Web3 Storage service.


### Web3 Storage


Apillon Web3 Storage is a Web3-based storage service that allows you to increase the accessibility of your files (or that of your website or app) as they are stored on a decentralized network of nodes around the globe.


#### Underlying technologies


Apillon Web3 Storage implements AWS S3 as cache to optimize upload of large files, IPFS, and Crust Network to pin files on multiple IPFS nodes.

[IPFS](https://ipfs.tech/)
[Crust Network](https://crust.network/)

IPFSWhen you upload a file to IPFS, it gets split into smaller chunks and cryptographically hashed. It also receives a unique fingerprint called a content identifier (CID), which acts as a permanent record of your file as it is at that point in time.

[IPFS](https://ipfs.tech/)

Crust NetworkCrust Network is a decentralized cloud storage provider on Polkadot. It supports multiple storage-layer protocols such as IPFS, and delivers instantly accessible on-chain storage functions. Crustʼs technical stack also supports data manipulation and computing.

[Crust Network](https://crust.network/)

Storage bucketFor more dynamic use of decentralized storage and Web3 development, Apillon introduces the concept of storage buckets. To start using Web3 Storage, you should first create a new bucket.


#### Web3 file storage process


Now, with theory out of the way, it’s time to get hands dirty.


Here is what happens to your files when you store them decentrally with Apillon:


Create a storage bucketTo begin, you should first create a storage bucket. Navigate to the menu on the left, and under Services, click Storage, and then New bucket.


In the pop-up window, set the name and description for the bucket. In Closed Beta, only buckets of 5GB storage space are available. Click Create bucket & continue to management.


Once your storage bucket is ready, it allows you to store files from either the Apillon dashboard or the API endpoints.


Upload filesNow, you can add files and folders with a simple click or drag and drop.


Choose your file, confirm its upload in the pop-up, and click Refresh to update the file list below.


On the file list, you can see details, such as File CID, Download link, File size, and Content type. Under Actions, you can also mark your files for deletion to free up your storage bucket space (see more below).

[below](#94e0)

Once your file is uploaded successfully and appears on the list, you can copy its IPFS-based URL and paste it into a new browser tab. Your file should appear under that URL, meaning it’s now successfully stored on a decentralized IPFS network of nodes via Crust.


Upload foldersYou can also use Web3 storage to upload a folder, for example, containing your website files. The IPFS-based link that you find on the Apillon storage bucket list should lead to your decentrally stored website files.


Create directoryFor faster management and easier navigation, you can also create file directories. Click Create directory on the right, set its name and description, and organize your files.


#### File deletion


To better understand file deletion with Apillon Web3 Storage, you should be aware that the storage lease for every file on IPFS that passes through Crust’s pinning and replication service is paid upfront for a minimum of 6 months, which is out of Apillon’s control. This means that all files that you upload to Apillon Web3 storage buckets will remain accessible for that long.


File marked for deletionIf you decide to delete a file before the expiration of the 6-month storage lease on Crust, the file is marked for deletion. Doing that, the storage lease will not be extended, and once the storage lease is up, your file will be deleted from all IPFS instances, and the storage load of deleted files in your storage bucked will be emptied, so you can upload new files.


3-month deletion periodWeb3 Storage lease period by Crust lasts 6 months. However, to deliver a better experience to our users, Apillon artificially lowers the deletion period to 3 months. This way, you can continue uploading new files faster and update your Web3 storage contents more frequently.


### Share your feedback


Now that you understand how to navigate Apillon Closed Beta and its Web3 Storage service, feel free to test it in all kinds of scenarios.


We’re looking forward to hearing about your experience with the Apillon platform and what features would you need most in your work.


Join us in Apillon Discord, and in the closed-beta channel, share your thoughts and feedback, so we can improve the platform and accelerate Web3 adoption for all developers regardless of background.

[Apillon Discord](https://discord.gg/yX3gTw36C4)

We’ll see you on the other side!


### ⧓ About Apillon


The Apillon platform serves as a unified gateway to the Web3 services provided by linked Polkadot parachains. Following the multi-chain vision, Apillon powers the transition of developers to Web3, simplifying its adoption in the real economy, and expanding its versatility as the ecosystem grows. With Apillon, Web3 services are within reach for every developer, regardless of their background and experience with blockchain technology.


Website | Wiki | GitHub | Twitter | Telegram | LinkedIn | Reddit

[Website](https://apillon.io/)
[Wiki](https://wiki.apillon.io/)
[GitHub](https://github.com/Apillon-web3)
[Twitter](https://twitter.com/apillon)
[Telegram](https://t.me/Apillon)
[LinkedIn](https://www.linkedin.com/company/apillon/)
[Reddit](https://www.reddit.com/r/apillon/)