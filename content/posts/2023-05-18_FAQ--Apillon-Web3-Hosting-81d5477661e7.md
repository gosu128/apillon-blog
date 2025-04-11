+++
title = "FAQ: Apillon Web3 Hosting"
date = "2023-05-18T12:47:10+0000"
description = "Dive into the details of decentralized hosting for your website with Apillon, the technologies behind it, and more."
draft = false
+++

### FAQ: Apillon Web3 Hosting


#### Interested in decentralized hosting? Dive into the details of hosting your website on Web3 with Apillon, the technologies behind it, and more.

[Apillon Web3 Hosting service](#0adc)
[Crust Network, IPFS and IPNS](#ffe8)
[Decentralized website hosting with Apillon](#85ee)

### Apillon Web3 Hosting service


#### What is the Web3 Hosting service on Apillon?


Apillon Web3 Hosting is a Web3-based storage service that allows you to increase the accessibility of your website or app and make it unstoppable from third-party impact, as it gets hosted on a decentralized network of nodes worldwide.


#### How to use Apillon Web3 Hosting?


Before hosting your website with Apillon Web3 Hosting service, you should first upload the contents of your website to the Apillon dashboard.


To host your website on a decentralized network, follow this guide. 👇

[Apillon Platform Closed Beta walk-through — Web3 HostingThe Apillon Platform Closed Beta is live and seeks feedback from brave testers. Try the Web3 Hosting service, and see…blog.apillon.io](https://blog.apillon.io/apillon-platform-closed-beta-walk-through-web3-hosting-78cc23dee9e5)

#### How does it work?


When you upload files on Apillon, they first land on AWS S3, a reputable centralized cloud provider, to ensure fast file capture. Once received, the files proceed to the Apillon node and become accessible through the IPFS gateway until moved from staging to production.


As you push files from staging to production, they move to the decentralized Apillon IPFS gateway, where the pinning and replication process starts with Crust.


Here, you can connect a custom domain to the website or app, and start the SSL certificate generation process in the Apillon gateway.


Finally, you can migrate your domain’s DNS records to Apillon, and launch your website or app using decentralized hosting.


### Crust Network, IPFS and IPNS


#### How do Crust, IPFS, and IPNS add to decentralized website hosting (and keep them editable)?


Apillon Web3 Hosting service is very similar to the Web3 Storage service in that it uses storage buckets to store website or app-related data. It implements AWS S3 as a cache to optimize the upload of large files, IPFS, Crust Network to pin files on multiple IPFS nodes, and IPNS to enable file updates.

[Web3 Storage service](https://blog.apillon.io/faq-apillon-web3-storage-c99a9b0e8b12)
[IPFS](https://ipfs.tech/)
[Crust Network](https://crust.network/)
[IPNS](https://docs.ipfs.tech/concepts/ipns/)

IPFSWhen you upload a file to IPFS, it’s split into smaller chunks and cryptographically hashed. It also receives a unique fingerprint called a content identifier (CID), which acts as a permanent record of your file as it is at that point in time.

[IPFS](https://ipfs.tech/)

Crust NetworkCrust Network is a decentralized cloud storage provider on Polkadot. It supports multiple storage-layer protocols such as IPFS, and delivers instantly accessible on-chain storage functions. Crustʼs technical stack also supports data manipulation and computing.

[Crust Network](https://crust.network/)

IPNSThe InterPlanetary Name System (IPNS) allows for creating mutable pointers to CIDs, a type of links that are updateable and mutable, without harming the content, its addressing and verifiability. While the CID created during file hashing on IPFS is immutable, the IPNS allows you to update website data and files frequently without having to create a new CID every time.

[InterPlanetary Name System](https://docs.ipfs.tech/concepts/ipns/#mutability-in-ipfs)
[How Apillon platform supports Web3 file updates with IPFS & IPNSUpdatability of data is essential, but tricky to achieve in Web3. Apillon lets you store online files decentrally and…blog.apillon.io](https://blog.apillon.io/how-apillon-platform-supports-web3-file-updates-with-ipfs-ipns-53534f985be)

### Decentralized website hosting with Apillon


#### Domains


Can Google and other search engines display an Apillon-hosted website?If you have a standard Web2 domain, Google and other search engines can find and index your website.However, if you only have a direct IPFS file/address that is not in the http format, only certain browsers can open the website linked to it, such as Opera and Brave. The http:// address is readable by all browsers, whereas the ipfs:// address can be read only by some.


What kind of domains can you host with Apillon Web3 Hosting?Apillon Web3 Hosting supports all standard domains.However, the platform does not support the hosting of domain name servers (DNS). You can keep your domain at your original DNS and only forward its corresponding records to Apillon. This way, domain management always takes place outside Apillon.Typically, domains use standard domain name servers, which are centralized, leaving websites exposed to third-party impact, including hacks or censorship. With Apillon, you can host your original website on a decentralized network and keep it permanently accessible or create a website backup hosted on Web3 to keep the contents live in case the original website goes down for whatever reason.


Can I connect an Unstoppable domain to Apillon Hosting?A Web3-native Unstoppable domain can be redirected to Apillon, as the Unstoppable domain platform itself offers a field to input an IPFS link.However, Unstoppable domains reside on Ethereum and Polygon networks as NFTs, leaving standard DNSs unable to resolve and index them in internet browsers, so make sure to have this in mind before deploying.

[Unstoppable domain](https://unstoppabledomains.com/)

Are Apillon-hosted websites part of traditional DNS?Serving merely as a gateway from Web2 to Web3, Apillon can host Web2 domains that are part of traditional DNS.


Where does my Apillon-hosted domain live?It remains where it was before. Apillon is not in a position to hold your domain, so you can hold your mail exchanger (MX) records with another service provider.


#### Website or app hosting


What kind of websites can I host with Apillon?Apillon Web3 Hosting supports only client-side rendering with HTML and JavaScript, not server-side rendering. Hence, only static pages can be hosted decentrally with Apillon.If you want to use Apillon Web3 Hosting to host dynamic pages, such as WordPress, you’d need a middleware, such as Gatsby, to make them static and push them to the Apillon server.


How will I be able to view a Web3-hosted website?In the Web3 Hosting process, you get an IPNS link to access the website. The link ensures to always display the website, even when a domain is not linked yet.


What is the cost of hosting a website with Apillon?Since Web3 Hosting stores your website contents decentrally using Web3 Storage buckets, the cost of hosting a website with Apillon is the cost of Apillon Web3 Storage.In the current stage, the Apillon platform only offers freemium plans, meaning all supported services are free of charge.Even when the platform upgrades to paid subscription plans, a form of a freemium plan will continue existing and supporting smaller-scale Web3 projects.The HTTPS certificate is provided by Apillon free of charge for all the hosted websites.


What happens to my website if the Apillon platform ceases operating?The domain remains under your control with its DNS outside Apillon anyway. The A record can easily be altered instantaneously so you can move your domain elsewhere.


How to delete files from an Apillon-hosted website?Each file hosting that passes through Crust’s pinning and replication service is paid upfront for a minimum period of 6 months. Apillon has no control over amending that period, so all files you deploy to Apillon hosting will remain accessible for that long.If you decide to delete a file before the end of the 6-month period, Apillon does not extend the storage lease on Crust once the 6-month period expires, which leads to file deletion on all IPFS instances.Apillon further artificially lowers the file deletion period to 3 months, making file storage more dynamic. After this period, the deleted files in your storage bucket are emptied, and your storage bucket capacity can accept new website files.


#### API connectivity


How to deploy a webpage via Apillon Web3 Hosting API?Apillon Web3 Hosting provides endpoints that can be used to implement CI/CD.To use Apillon Web3 Hosting APIs, you should first upload website or app contents to the Apillon dashboard.The process of deploying a webpage through Apillon API is as follows:

[CI/CD](https://en.wikipedia.org/wiki/CI/CD)
[Apillon dashboard](https://app.apillon.io/dashboard/service/hosting)

Source the full Apillon Web3 Hosting API. 👇

[Apillon API | Apillon WikiApillon Wikiwiki.apillon.io](https://wiki.apillon.io/build/3-apillon-api.html#web3-hosting-api)

Please note that Apillon documentation for API connectivity is a matter of continuous editing and improvement.


Does API work if the Apillon Web3 Hosting service is down?In case the Apillon Web3 Hosting service is down, so is its API, and you can’t call the smart contract from the API.However, once the smart contract using the Web3 Hosting service is deployed, it’s live on the blockchain network, so it can be called from a wallet and works normally.


For more details about the Crust-supported Web3 Hosting service on the Apillon platform, check out the guide below and Apillon Wiki.

[Apillon Platform Closed Beta walk-through — Web3 HostingThe Apillon Platform Closed Beta is live and seeks feedback from brave testers. Try the Web3 Hosting service, and see…blog.apillon.io](https://blog.apillon.io/apillon-platform-closed-beta-walk-through-web3-hosting-78cc23dee9e5)
[Apillon Web3 services | Apillon WikiApillon integrates multiple parachains and offers access to them in a unified way via modules on the developer…wiki.apillon.io](https://wiki.apillon.io/build/2-web3-services.html#web3-hosting)
