+++
title = "Guide: NFT Service — Create and deploy NFT collection on Moonbeam"
date = "2023-05-11T12:40:56+0000"
description = "In this guide, you will learn step-by-step how to go from raw data and files to a permanently deployed NFT collection on Moonbeam Network."
draft = false
+++

### Guide: NFT Service — Create and deploy NFT collection on Moonbeam


#### In this guide, you will learn step-by-step how to go from raw data and files to a permanently deployed NFT collection on the Moonbeam network in just a few steps.

[Things to know before you begin](#9c85)
[Step 1: Store NFT metadata](#4c66)
[Step 2: Compose NFTs](#20ea)
[Step 3: Mint NFTs](#2001)

The recently released integration of the Moonbeam Network’s smart contracts into the Apillon dashboard has brought about the first use case: a few-step deployment of an NFT collection.

[Make your own NFT collection in minutes — brought to Moonbeam by ApillonApillon’s new easy-to-use NFT Service is designed to cut the process short and make it beginner-dev-proof.blog.apillon.io](https://blog.apillon.io/make-your-own-nft-collection-in-minutes-brought-to-moonbeam-by-apillon-538fdf34fc5)

Read on to learn how to deploy your first NFT collection on the Moonbeam network using the drag-and-drop NFT Service on the Apillon dashboard without having to master the Web3 environment and specific protocols.


### Things to know before you begin


#### How will your NFT collection work?


👉 Duration: Deployment on blockchain makes your NFT collection immutable and non-removable. If specified, some NFTs could be made revokable but not deleted. If you are just testing, you might want to play with dummy files and not final ones.


👉 Hosting: Apillon supports Web3 Hosting with Crust and IPFS, so all the contents uploaded in the process of creating an NFT collection will be stored decentrally, too.

[Web3 Hosting with Crust and IPFS](https://wiki.apillon.io/build/2-web3-services.html#web3-hosting)

👉 Cost: Apillon currently offers all services in a freemium plan. Whatever you deploy in this stage remains a part of it and will not be part of future paid plans.


👉 Access: Deployment of an NFT collection makes it permanently traceable on the blockchain. When it comes to distributing NFTs, you can opt for different ways of sharing them with the public. Even though the initial Apillon wizard guides you step-by-step through the creation of an NFT collection, as a developer, you may still utilize the following recipe:

[Apillon Web3 Hosting](https://medium.com/apillon/apillon-platform-closed-beta-walk-through-web3-hosting-78cc23dee9e5)

👉 Editability: Deployment of NFT collection via the Apillon NFT service wizard does not support IPNS metadata mutability and gradual releases. They can be achieved by manually building metadata and NFTs using the Apillon infrastructure.


👉 Network: The current release of the NFT Service initially support Moonbeam Network (Mainnet) and Moonbase (Testnet). In upcoming versions, more network options will be made available.


#### What will you need?


To create your first NFT collection with Apillon, you will need the following:

[Apillon dashboard](https://app.apillon.io/register)
[NFT files](https://medium.com/apillon/guide-nft-service-pt-1-generate-nft-art-with-ai-and-get-files-ready-200168b6b303#eb24)
[NFT metadata](https://medium.com/apillon/guide-nft-service-pt-1-generate-nft-art-with-ai-and-get-files-ready-200168b6b303#a060)

Learn more about how to compile NFT files, from AI-generated content to metadata that defines them. 👇

[[Guide] NFT Service Pt. 1: Generate NFT art with AI and get files readyIn the first part of the guide through NFTs with Apillon, you will learn how to prepare your files for a smooth…blog.apillon.io](https://blog.apillon.io/guide-nft-service-pt-1-generate-nft-art-with-ai-and-get-files-ready-200168b6b303)

Now that you have everything at hand, your NFT collection could go live in a matter of minutes — stored decentrally, yours to host either on a decentralized network or with your existing website.


Let’s get started.


Go to the Apillon dashboard, navigate to Services in the menu on the left, and find NFTs. Click “Start creating NFTs”.


The whole process of launching an NFT collection with Apillon consists of three steps:


### Step 1: Store NFT metadata


To prevent your NFTs from vanishing from the face of Web3, the NFT files — the unique assets and the data that makes them unique — need to be stored on the web, and the best way to ensure permanent access is by storing them in a decentralized way.

[vanishing from the face of Web3](https://blog.apillon.io/why-decentralized-storage-matters-for-nft-metadata-and-your-next-nft-collection-b7b90fc3762)

When the dashboard asks, “Would you like to store your NFT metadata in a decentralized way”, you have two options (click on either to continue the process):

[Yes, proceed](#20ea)
[I have metadata online](#2001)

### Step 2: Compose NFTs


#### 2.1 Upload NFT metadata


Click or drag and drop your CSV file. The platform will automatically create a Web3 Storage bucket in the background and connect it to your NFT collection.

[Web3 Storage bucket](https://wiki.apillon.io/build/2-web3-services.html#storage-bucket)
[Web3 Storage bucket](https://wiki.apillon.io/build/2-web3-services.html#storage-bucket)

Now, the name of the uploaded file appears on the dashboard. If you mistakenly chose the wrong one, click the delete icon and do it all over.


Click “Proceed”.


In the Metadata attributes pop-up window, select which metadata elements would serve as attributes of NFTs, and choose their format (e. g., a “String” represents text-form values).


Click “Confirm attributes”.


#### 2.2 Upload NFT files


Now, it’s time to upload the meat and potatoes of your NFT collection.


Click “Upload files” and choose them from your local storage.


Once uploaded, the total number of uploaded files appears. If you failed to import the same number of NFT files as included in the CSV metadata record, the dashboard notifies you of missing files. Delete the uploaded ones and upload again.


Now go and check how your NFTs would look like — click “Preview your NFTs”.


#### 2.3 Preview NFTs


Check how the collection looks, navigate through pages if there are multiple, and confirm it displays the correct files.


In the top right corner, you can switch to the list view to see whether the CSV file was parsed correctly and that there are no mismatches between NFT files and their metadata.


If everything is ok, proceed with the process, or return if you want to change something.


Now, time for the last step — deploying your NFT collection on the blockchain and minting your unique assets.


### Step 3: Mint NFTs


In this step, set the fine details of your collection, including name, symbol, and behavior.


#### 3.1 Name your collection


Your collection needs a name to stand out among many and be easily searchable.


👉 Enter the Name you want for your collection — here, the sky is the limit.


👉 Enter a Symbol that will act as a token name on the blockchain for the collection. It normally consists of 3 or 4 letters that sum up or refer to its name.


👉 On the dropdown, select the Network (Chain) where you want to deploy your collection. At this stage, you can choose either Moonbeam (Mainnet) to deploy in production mode or Moonbase (Testnet) to deploy in a test environment. In upcoming versions of the platform, more network choices will be available.


Double-check the inputs and click “Proceed”.


#### 3.2 Behavior


Here, you mold the personality of your NFT collection and determine how it should behave in terms of supplying its contents.


👉 Total supply refers to the maximum supply of NFTs in your collection. If it holds a limited number of NFTs, enter the number under How many?


👉 The Revokable function lets the collection owner (you) revoke NFT(s) at any point in time. This comes in handy for limited-time NFTs, such as achievement badges in brand campaigns. Unrevokable NFTs live permanently on the blockchain.


👉 With Soulbound, you can make your NFTs untradeable. Soulbound NFTs cannot leave the wallet they were deposited into and always remain tied to the originator’s wallet address.


👉 To collect royalties from your NFTs, enter your or the recipient’s wallet address, and set the royalties fees in %.


👉 For collections with postponed releases, you can choose Drop. This makes your NFT collection publicly available for users to mint and purchase NFTs after the specified date and at the specified price. To avoid having to pay for your own NFTs, enter the number of NFTs you’d like to Reserve for yourself and mint before the drop. Without drop, only you can mint NFTs for either yourself or others.


Double-check everything and click “Proceed” to preview and start deploying your collection.


#### 3.3 Preview and deploy


Before deploying your first Apillon-made NFT collection to the Moonbeam Network, this is your final chance to review everything.


Swipe through NFTs, and if everything looks good, it’s time to inscribe your creations permanently on the blockchain. Click “Deploy to blockchain”.


Since this is a point of no return, you’re prompted to double-confirm your decision before deploying your NFT collection.


Click “Deploy NFT collection” again, and wait for the Web3 magic to happen.


In a few seconds, you can give yourself a pat on the back — your first NFT collection with Apillon is successfully deployed!


On the next screen, you can view the transaction on blockchain explorer or see its contents in your newly created bucket.


#### 3.4 Display on the internet


Now that you have deployed your NFT collection on the blockchain, you can view the transaction on the blockchain explorer linked at the bottom.


To display NFTs in all their glory (beyond the transaction hash) and make them tradeable and shareable, you should showcase them on a website.


Once the NFT collection is deployed, you will automatically be presented with a finished Apillon website template that can read your NFT metadata and display your collection.


Here, you have two options: you can either create a decentrally hosted website by forking the template on GitHub, or simply integrate the code into your existing website.


1. Fork Apillon NFT website template


The easiest way to display your NFTs is to create a website for your NFT collection using Apillon static website template and host it on a decentralized network.


This static website written in HTML is fairly simple and represents a great starting point, as you can customize it to best suit your NFT collection website. Click “Create website to display NFTs”.


The button takes you to Apillon GitHub repository, where you can create a new fork of the template.

[Apillon GitHub repository](https://github.com/Apillon-web3/nft-template)

You can use the template and simply update the js/env.js file with your own addresses. Find the Contract address on the Apillon dashboard on the list of NFT collections, and copy it to the clipboard.


In GitHub, under the Code button, click Download ZIP. In your visual code editor, paste the address of your NFT website, and save.


Once done, run locally and redeploy with different functionalities to Apillon Web3 Hosting.

[Apillon Web3 Hosting](https://wiki.apillon.io/build/2-web3-services.html#web3-hosting)
[https://github.com/Apillon-web3/nft-template](https://github.com/Apillon-web3/nft-template)

2. Integrate and mint NFT collection on your website


If you prefer having your NFT collection displayed on your existing website, wherever it is hosted, even centrally, you can do so, too.


Click “Display them on your existing website”. Again, you use the code from Apillon GitHub, and integrate it to your website.

[Apillon GitHub](https://github.com/Apillon-web3/nft-template)

#### 3.5 Mint NFTs


To make your NFTs appear in all their glory on your website, you should mint them.


On the Apillon dashboard, you can see the details of the deployed NFT collection: Collection symbol and name, Contract address (copy and paste it into blockchain explorer to verify), and its status (e. g., “Failed”, “Deploying”, or “Deployed”). There is also Mint price and the number of Reserved NFTs.

[blockchain explorer](https://moonscan.io/)

Under Minted/Max supply, you can see how many of the deployed NFTs were actually minted.


To do more actions, minting included, and see more details, click on the Collection name.


On the list of details, the Chain ID indicates the network the collection was deployed on, together with Transaction hash.


Under Transaction type, you can see the initiated action for the contracts, and its Status.


If everything looks fine, go to Actions in the top right corner, and choose to Mint your NFTs.


As you mint your NFTs, you will bring your collection to life linked to your wallet and visible on your website.


Using the code from GitHub, you can simply integrate it to your website.


#### 3.6 Transfer ownership


To transfer ownership to another wallet, simply click it under the Actions drop down, and enter the wallet address into the pop-up.


### Long live NFTs


Well, that’s it. You’ve made it to the end and are now a proud owner of your first NFT collection on the Moonbeam Network!


List them on marketplaces such as tofuNFT, display them locally on your website or dapp, or share them with intended recipients.

[tofuNFT](https://tofunft.com/)

The sky is the limit! Let us know how it went, share your precious NFTs with the Apillon and Moonbeam communities, and inspire other to follow your footsteps.

[Let us know](https://twitter.com/apillon)

1, 2, 3 — NFT!


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