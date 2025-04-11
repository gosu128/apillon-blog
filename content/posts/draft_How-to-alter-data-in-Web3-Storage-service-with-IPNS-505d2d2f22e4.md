+++
title = "How to alter data in Web3 Storage service with IPNS"
date = "2025-04-01T13:45:24"
description = "Subtitle"
draft = false
+++

### How to alter data in Web3 Storage service with IPNS


#### Subtitle

[Why decentralized storage matters for NFT metadata and your next NFT collectionInstead of overdoing what meets the eye, NFT projects should focus more on metadata and its storage to keep it…blog.apillon.io](https://blog.apillon.io/why-decentralized-storage-matters-for-nft-metadata-and-your-next-nft-collection-b7b90fc3762)

IPFSWhen you upload a file to IPFS, it’s split into smaller chunks and cryptographically hashed. It also receives a unique fingerprint called a content identifier (CID), which acts as a permanent record of your file as it is at that point in time.

[IPFS](https://ipfs.tech/)

Crust NetworkCrust Network is a decentralized cloud storage provider on Polkadot. It supports multiple storage-layer protocols such as IPFS, and delivers instantly accessible on-chain storage functions. Crustʼs technical stack also supports data manipulation and computing.

[Crust Network](https://crust.network/)

IPNSThe InterPlanetary Name System (IPNS) allows for creating mutable pointers to CIDs, a type of links that are updateable and mutable, without harming the content, its addressing and verifiability. While the CID created during file hashing on IPFS is immutable, the IPNS allows you to update website data and files frequently without having to create a new CID every time.

[InterPlanetary Name System](https://docs.ipfs.tech/concepts/ipns/#mutability-in-ipfs)
[How Apillon platform supports Web3 file updates with IPFS & IPNSUpdatability of data is essential, but tricky to achieve in Web3. Apillon lets you store online files decentrally and…blog.apillon.io](https://blog.apillon.io/how-apillon-platform-supports-web3-file-updates-with-ipfs-ipns-53534f985be)

Create a bucket, and name it.


Upload files and confirm upload.


Once they are uploaded, you can see they’re uploaded to IPFS. By copying the IPFS-based download link and copying it into the browser field, you can see the file on the IPFS.


For more details, click on the file name and read them in the window that appears on top right.


Apart from what can be seen on the list, these include date of expiration on blockchain and replicas.


Under the IPNS tab, create your first IPNS record (if you haven’t got one yet).


Go back to your files, and under the three dots on the right side, choose Publish to IPNS.


In the pop-up window, choose the IPNS record you want to publish to, or Create a new one if you prefer. Click Publish to IPNS.


IPNs is published in the background. You will be notified when it is done.


Now, under the IPNS tab, you can see the file has been published on IPFS with IPNS. Click on the copy icon to copy the link and paste it into browser or simply click the link and see your file on IPFS/IPNS on a decentralized network.


Now it’s permanently accessible? I only need a link to it? So I should save the link outside the Apillon platform in case something happens with it?


how to upload files in bulk to IPNS? why just one at a time?


do IPNS records work as folders or files? can’t I upload more files to a single IPNS record?


When you click on the link, your file appears in the browser, stored on a decentralized network. If you use Brave (or Opera?) browser, you should see an IPFS icon at the right of the URL bar.


Click on it to open the file under the IPNS link.


Now, how to edit the file/its metadata on IPNS?
