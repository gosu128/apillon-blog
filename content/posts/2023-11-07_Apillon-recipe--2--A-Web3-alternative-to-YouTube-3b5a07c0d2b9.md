+++
title = "Apillon recipe #2: A Web3 alternative to YouTube"
date = "2023-11-07T10:27:26+0000"
description = "In the second episode of Web3 recipes, you will learn how to create a Web3 Storage for video files, connect it with client-side UIs, and…"
draft = false
+++

### Apillon recipe #2: A Web3 alternative to YouTube


#### In the second episode of Web3 recipes, you will learn how to create a Web3 Storage for video files, connect it with client-side UIs, and host the platform on a decentralized network.

[Why a Web3 alternative to YouTube?](#582c)
[Web3 Storage and Hosting for videos](#a440)
[Step 1: Create a Web3 Storage bucket](#6ded)
[Step 2: Build a client-side video upload UI](#b6f2)
[Step 3: Host on Web3](#a704)
[Step 4: Connect your domain](#040a)
[Step 5: Connect UI to Storage buckets](#2c10)
[Step 6: Enhance UI, upgrade features, launch](#a991)

### Why a Web3 alternative to YouTube?


Indeed, why? Why compete with a behemoth the size of YouTube? Well, you don’t need to compete per se. You can just tap into a decentralized way of redefining the infinite rabbit hole (and goldmine) that is the video content industry.


### Web3 Storage and Hosting for videos


With the Apillon platform, you can easily upgrade your video platform to the Web3 level, using primarily the Web3 Storage and Web3 Hosting services.

[Web3 Storage](https://wiki.apillon.io/build/2-web3-services.html#web3-storage)
[Web3 Hosting](https://wiki.apillon.io/build/2-web3-services.html#web3-hosting)

Both represent condensed and purposed technology of Crust Network, a Polkadot parachain, which pins the linked files to IPFS nodes worldwide.


The whole process can be done by utilizing the Apillon dashboard Web3 services and API keys.

[FAQ: Apillon Web3 StorageFind answers to your questions on the Apillon Web3 Storage service, how to store files on a decentralized network, and…blog.apillon.io](https://blog.apillon.io/faq-apillon-web3-storage-c99a9b0e8b12)
[FAQ: Apillon Web3 HostingDive into the details of decentralized hosting for your website with Apillon, the technologies behind it, and more.blog.apillon.io](https://blog.apillon.io/faq-apillon-web3-hosting-81d5477661e7)

Ready to start building? Let’s go.


### Step 1: Create a Web3 Storage bucket


Log into the Apillon dashboard, and in the menu on the left, navigate to Storage. Create a new storage bucket by clicking the yellow button.

[Storage bucket](https://wiki.apillon.io/build/2-web3-services.html#storage-bucket)

In the pop-up, enter your bucket name to easily distinguish it from other-purpose decentralized storage buckets. Add a description, too, and click “Create bucket & continue to management”.


### Step 2: Build a client-side video upload UI


For your Web3 video platform to serve the intended purpose, let your audience upload videos to the decentralized storage.


For that, you need the following:


For the website template, you may use pre-made Apillon templates, such as the NFT website templates available on the Apillon GitHub.

[Apillon GitHub](https://github.com/orgs/Apillon/repositories?type=all)

Now, even though these templates serve the purpose of displaying NFT collections, they’re based on the JavaScript, ReactJS, and VueJS frameworks and a component that allows users to connect their wallets, which can be easily replicated for your video platform.

[JavaScript](https://github.com/Apillon/nft-template)
[ReactJS](https://github.com/Apillon/nft-template-react)
[VueJS](https://github.com/Apillon/nft-template-vue)

Simply clone the chosen GitHub repository, remove unnecessary parts for displaying NFTs, and instead, build the front-end and business logic that allows users to drag and drop videos into the website and send the files to Apillon Web3 Storage.


Learn more. 👇

[React and Vue join JavaScript in Apillon’s NFT website template libraryYou can now use NFT website templates in two more languages and customize them to showcase Apillon-minted NFTs.blog.apillon.io](https://blog.apillon.io/react-and-vue-join-javascript-in-apillons-nft-website-template-library-939005ac8770)

### Step 3: Host on Web3


To host your website, you need a scalable service that supports the growth of your Web3 video platform. With Apillon, you can host it on IPFS via Crust Network.


In the Apillon dashboard, navigate to Hosting and click “Add first website”.


Enter your website’s name and description and hit “Create website”.


In the next step, you’ll be asked to upload website contents to host them in a decentralized manner.


Now, upload the website contents to the Apillon dashboard and move them to Web3 Hosting. Click “Upload directory” or drag and drop separate files. Select the website files from your local drive and click “Upload”.


Once your files are uploaded and appear on the Apillon dashboard, click the folder name to view more details, such as file size and status. Next, click “Deploy to staging” in the top right corner before moving it to the production phase.


This could take up to 5 min to complete.


Once deployed, you can see the files’ IPNS link, indicating that the contents were deployed to a decentralized network and remain mutable — this is crucial for projects like websites, which require frequent updates of their contents and features.


If you click on the IPNS file, you’re taken to an IPFS-based address that holds your website files under it.


Go back to the Apillon dashboard and deploy the contents to production by clicking the yellow button in the top right corner.


Once the deployment is successful, it’s time to link your website’s domain.


### Step 4: Connect your domain


Under Domain preview, click “Add domain” if you don’t have one yet or “Configure domain” if you already have one to use and configure for Apillon hosting.


In either case, you’ll need to log into your DNS server or domain registrar and add or edit the DNS records that come with your domain.


Update the above details with your domain provider to migrate from centralized to Web3 hosting with Apillon, backed by Crust’s pinning on IPFS.


### Step 5: Connect UI to Storage buckets


For the purpose of this guide, let’s go with a simple architectural scheme — create two separate Web3 Storage API keys to unlock different user rights:

[5.1 Video upload UI: API key with Read and Write permissions](#205c)
[5.2 Video player UI: API key with Read-only permissions](#1c66)

#### 5.1 Connect video upload UI to Web3 Storage


The first Web3 Storage API key should have both Read and Write permissions. Hooking the key to your Web3 video platform front-end will allow users to connect, upload, and watch videos.


To generate the first API key to connect your client-side UI to Apillon Web3 Storage buckets, go to the Apillon dashboard menu, navigate down to Project settings, and under the API keys tab, click “Generate new key”.


Enter the API Key name, and enable the creation of the API key for Storage service — make sure both Read and Write permissions are checked. Click “Generate”.


Once the API key details show up in a pop-up window, make sure to save the API key’s secret — it’s an essential part of unlocking your API key.


Once the first API key for your Web3 video project UI is ready, click on the three dots on the right, and “Copy API key to clipboard”.


Finally, use the newly generated API key to connect your client-side UI to Apillon Web3 Storage buckets containing uploaded videos.


The next thing you need to do is create another Web3 Storage API key to only display videos on your Web3 video platform. 👇


#### 5.2 Connect video player UI to Web3 Storage


To prevent abuse of your Web3 video platform, create another, separate UI that only allows playing, not uploading videos.


For that part, you need another Web3 Storage API key, but this time, holding only Read permissions.


On the Apillon dashboard, click “Generate new key”.


Enter the name of this API key to distinguish it from the previous one, and make sure only Read permissions are checked. Click “Generate”.


Once the API key details show up, save the API key secret and proceed.


Your read-only API key to Web3 Storage is now ready, and you can use it in a separate front end to display videos on your platform.


### Step 6: Enhance UI, upgrade features, launch


The last thing on your to-do list is to play around with options for your UI. Allow your fans to watch videos and upload them to contribute to your platform’s growth, add user-friendly features, and top it off with a nice design.


And to spice it up with some more Web3 flavor, consider adding other decentralized services in its future versions:


This is how you can create a decentralized video viewing and sharing platform with Apillon. Of course, you can always add your touch by designing the UI from scratch or tweaking the APIs to your project’s preference — go wild.


Stay tuned for more Web3 service upgrades on the Apillon platform and advance your video business with a full focus on a decentralized approach, user autonomy with DIDs, and digital ownership through NFTs.


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