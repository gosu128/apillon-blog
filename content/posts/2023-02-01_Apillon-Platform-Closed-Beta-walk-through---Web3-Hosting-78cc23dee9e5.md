+++
title = "Apillon Platform Closed Beta walk-through — Web3 Hosting"
date = "2023-02-01T11:05:52+0000"
description = "The Apillon Platform Closed Beta is live and seeks feedback from brave testers. Try the Web3 Hosting service, and see how it works for you."
draft = false
+++

### Apillon Platform Closed Beta walk-through — Web3 Hosting


#### The Apillon Platform Closed Beta is live and seeks feedback from brave testers. Learn more about the Web3 Hosting service, test, suggest, and help us improve.

[Good to know](#3f68)
[Account log in and access code](#a4ea)
[Create a Web3 project](#3bbb)
[Web3 Hosting](#f2ee)
[Share your feedback](#2a29)

In Apillon Closed Beta, you can try the platform’s Web3 services before it’s ready for public launch. We count on every participant to help us improve the platform’s offering and add to faster adoption of Web3, one feedback at a time.

[Apillon launches an invitation-only Closed Beta of the Web3 development platformApillon is excited to offer the first test and a chance for a practical walk-through of a simplified Web3 building…blog.apillon.io](https://blog.apillon.io/apillon-launches-an-invitation-only-closed-beta-of-the-web3-development-platform-a075c38273a3)

In this walk-through guide, we take you from account registration to deploying your website with Web3 Hosting, one of the services available in Apillon Closed Beta.


But before we begin, you should keep in mind a few things.


### Good to know


In its current state, Apillon is a Web3 hybrid platform. This means that certain services are still run by centralized providers to ensure fast development and optimal UI. However, the platform’s infrastructure will gradually become fully decentralized, and newer versions will deliver more services for faster development of Web3 products.


Moreover, Apillon Closed Beta delivers no guarantees, either regarding functionalities or access, and it is intended for testing purposes only. Beta features are limited in some aspects and will become more accessible as the platform evolves.


Now, let’s dive in.


### Account log in and access code


To test the features available in the Apillon Closed Beta, you first need an Apillon account. Go to http://app.apillon.io/ to create one, or simply log in if you are already a registered user.

[http://app.apillon.io/](http://app.apillon.io/)

At the bottom of the intro page, you can find a Closed Beta code. Copy and paste it to our closed-beta channel on Apillon Discord. Once you receive an email invitation, you can access Closed Beta and the available Web3 services.

[Apillon Discord](https://discord.gg/yX3gTw36C4)

Once the door opens, you can start plotting your first Web3 project with Apillon.


### Create a Web3 project


Start by adding a new project. In the top left corner of the screen, click Add new project, set its name and description in the pop-up window, and click Create new project.


Once done, you can check more details under Project overview in the menu on the left.


Now, it’s time to attach Web3 services.


In the Closed Beta, you can attach Web3 Storage and Web3 Hosting service. The process of Web3 Storage was described in our previous post. And here, we take a look at the Web3 Hosting service.

[our previous post](https://blog.apillon.io/apillon-platform-closed-beta-walk-through-web3-storage-1e76bfaa928a)

Let’s begin.


### Web3 Hosting


Apillon Web3 Hosting is a Web3-based hosting service that allows you to increase the accessibility of your website or app and make it unstoppable, as it gets hosted on a decentralized network of nodes around the globe.


#### Underlying technologies


Apillon Web3 Hosting implements AWS S3 as a cache to optimize the upload of large files, IPFS, and Crust Network to pin files on multiple IPFS nodes.

[IPFS](https://ipfs.tech/)
[Crust Network](https://crust.network/)

IPFSThe InterPlanetary File System (IPFS) is a distributed system for peer-to-peer access and transfer of files, websites, apps, and data. When you upload a file to IPFS, it gets split into smaller chunks and cryptographically hashed. It also receives a unique fingerprint called a content identifier (CID), which acts as a permanent record of your file as it is at that point in time.

[InterPlanetary File System](https://docs.ipfs.tech/)

Crust NetworkCrust Network is a decentralized cloud storage provider on Polkadot. It supports multiple storage-layer protocols, such as IPFS, and delivers instantly accessible on-chain storage functions. Crustʼs technical stack also supports data manipulation and computing.

[Crust Network](https://crust.network/)

Storage bucketDecentralized hosting of a website or an app on Apillon is very similar to using storage buckets, a more dynamic way of managing file storage on Web3. It takes advantage of the underlying Crust Network and IPFS protocol to host your Web3 website or application.


Learn more about Web3 Storage and storage buckets. 👇

[Apillon Platform Closed Beta walk-through — Web3 StorageThe Apillon Platform Closed Beta is live and invites participants to share feedback. Learn more and help us improve…blog.apillon.io](https://blog.apillon.io/apillon-platform-closed-beta-walk-through-web3-storage-1e76bfaa928a)

IPNSThe InterPlanetary Name System (IPNS) allows for creating mutable pointers to CIDs, a type of links that are updateable and mutable, without harming the content, its addressing and verifiability. While the CID created while hashing files on IPFS is immutable, the IPNS allows you to update website data and files frequently without having to create a new CID every time.

[InterPlanetary Name System](https://docs.ipfs.tech/concepts/ipns/#mutability-in-ipfs)

#### Web3 website/app hosting process


Here is what happens to your website or app when it’s hosted decentrally with Apillon:


#### Decentralized deployment


Deploying a website or application with decentralized hosting on Apillon is just a matter of minutes and a few steps.


First, log in to your Apillon dashboard.

[Apillon dashboard](https://app.apillon.io/login)

In the menu on the left, under Services, navigate to Hosting, and click Add first website.


In the pop-up window, enter your webpage name, description, and domain name. Click Create webpage and proceed to the deployment process.


Next, upload files and folders or drag and drop your static website files and wait for the upload to finish.


For faster management and easier navigation, you can also create file directories. Click Create directory on the right, set its name and description, and organize your files.


Once the file upload is complete, Crust Network starts pinning and replicating files automatically.


Next, proceed to move the uploaded website files to the staging phase. Click Deploy to staging in the top right.


Now, check what’s been deployed in the Preview tab. Under Domain preview, you can see your files’ IPFS-based domain — click on it and see your files hosted on IPFS.


The details listed below tell about your website or app’s Environment, Deployment status, total Size, and Update time. If everything looks good, you can move it to the production phase.


Click Deploy to production. Once the deployment process is done, your website or app will be hosted on your custom domain to the world wide web on a decentralized network of nodes.


#### File editing


During Apillon Closed Beta, the Web3 Hosting service does not support single file changes since hosting is treated as batch file upload. This means that as your deploy a new version of your website or app, its contents are rewritten, and new files get pinned and replicated on Crust Network.

[Apillon Discord](https://discord.gg/yX3gTw36C4)

#### File deletion


Storage lease for every file on IPFS that passes through Crust’s pinning and replication service is paid upfront for a minimum of 6 months, which is out of Apillon’s control. This means that all files that you upload to Apillon Web3 storage buckets will remain accessible for that long.


File marked for deletionIf you decide to delete a file before the expiration of the 6-month storage lease on Crust, the file is marked for deletion. Doing that, the storage lease will not be extended, and once the storage lease is up, your file will be deleted from all IPFS instances, and the storage load of deleted files in your storage bucked will be emptied, so you can upload new files and redeploy your website or app.


3-month deletion periodWeb3 Storage lease period by Crust lasts 6 months. However, to deliver a better experience to our users, Apillon artificially lowers the deletion period to 3 months. This way, you can continue uploading new files faster and update your Web3 website/app contents more frequently.


#### Website/app redeployment


In case you want to redeploy the website or app with new changes to files or folders, repeat the process above simply by uploading the whole website or app via Apillon Hosting view.


### Share your feedback


Now that you know how to navigate Apillon Closed Beta and its Web3 Hosting service, feel free to play around with it and see how it works for you.


We’re eager to hear your feedback and suggestions on what could be improved and what type of features would serve you better as you build Web3 products.


Share your thoughts in Apillon Discord’s closed-beta channel, and help us improve the platform for greater adoption in the developer community.

[Apillon Discord](https://discord.gg/yX3gTw36C4)

See you there!
