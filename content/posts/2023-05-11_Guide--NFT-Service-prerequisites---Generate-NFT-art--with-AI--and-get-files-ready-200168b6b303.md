+++
title = "Guide: NFT Service prerequisites - Generate NFT art (with AI) and get files ready"
date = "2023-05-11T10:11:28+0000"
description = "In this preliminary guide on the Apillon NFT Service, you will learn how to prepare files and metadata for a smooth deployment of your…"
draft = false
+++

### Guide: NFT Service prerequisites — Generate NFT art (with AI) and get files ready


#### In this preliminary guide through the Apillon NFT Service, you will learn how to prepare files and metadata for a smooth deployment of your NFTs.

[NFT files](#eb24)
[NFT metadata](#a060)

The recently released integration of the Moonbeam Network’s smart contracts into the Apillon dashboard has brought about the first use case: a few-step creation of an NFT collection on this EVM-compatible parachain.

[Make your own NFT collection in minutes — brought to Moonbeam by ApillonApillon’s new easy-to-use NFT Service is designed to cut the process short and make it beginner-dev-proof.blog.apillon.io](https://blog.apillon.io/make-your-own-nft-collection-in-minutes-brought-to-moonbeam-by-apillon-538fdf34fc5)

But regardless of the network choice, you should have some things ready before you start creating your NFT collection.


In its most simplified sense, NFTs are composed of two parts: what you see as a unique asset (a digital file) and what defines it in the background (its metadata).


You should have both to create an NFT collection with Apillon. Here is how to get them ready.


### NFT files


NFTs can represent anything from images and text to music and video. They deliver extraordinary opportunities for yourself or your brand to display art collections, trade products, list services, sell unique experiences, and more.


The ERC-721 standard packs any file format into permanently stored content on the blockchain, and thanks to Moonbeam’s EVM compatibility, they can be deployed quickly and efficiently with Apillon.

[Moonbeam’s EVM compatibility](https://moonbeam.network/networks/moonbeam/nfts/)

Even if you don’t have a collection of digital items yet, or don’t have the skills to create one, you can join the NFT trend. Have an AI tool generate NFT art based on your prompts.


#### Create art with AI


To create graphic art, you can try several AI art generators, such as Midjourney, Stable Diffusion, and Artbreeder.

[Midjourney](https://www.midjourney.com/home/?callbackUrl=%2Fapp%2F)
[Stable Diffusion](https://stablediffusionweb.com/)
[Artbreeder](https://www.artbreeder.com/)
[Artbreeder](https://www.artbreeder.com/)

If you’re more into music, try Soundraw, or if you don’t mind playing with code, OpenAI’s Jukebox might be the tool for you.

[Soundraw](https://soundraw.io/)
[OpenAI’s Jukebox](https://github.com/openai/jukebox/)
[Soundraw](https://soundraw.io)

Before you venture out into the AI world, it’s a good idea to plan out your NFT collection — in terms of what it should represent, its style of it, the number of items you want to create, how they will differ, etc.


All this information will help you gather the metadata of NFT files.

[Artbreeder](https://www.artbreeder.com/create/landscapes)

#### Save files


Once you have your unique items — either AI-generated or fruits of your own creativity — save them with designated names, e.g., 1.jpg, 2.jpg, etc.


With Apillon, you can upload NFT files in batches. It’s advisable you have them all stored in a designated folder so you can easily drag and drop from your folder to the dashboard.


Now, with all your unique files stored, let’s proceed to list their metadata so you can deploy them all together to the blockchain and turn them into NFTs.


### NFT metadata


What makes NFTs unique is not just the jaw-dropping art. It’s also (or mostly) their metadata, the backbone of NFTs.


Without metadata, NFTs are not really NFTs — two or more images can be the same, but the metadata behind them holds information on their creator, date of release, and other distinguishing factors and features that make them one-of-a-kind, permanently inscribed and traceable on the blockchain.


NFT metadata can give information about the color, material or serial number of a physical item a token represents, attire or accessories of generative NFT characters, or music genre and featured artists in audio NFT.


#### Formatting metadata


For metadata to be readable in the process of deploying NFT collection with Apillon, it should be listed as a CSV (comma-separated values) file.


Make sure the attributes in columns conform with the category in the top row.


This is how your metadata CSV file should look like. You can download a CSV sample, replace contents with your own and save it as a CSV file on your disk, or create a new one from scratch and do the same.

[download a CSV sample](https://app-staging.apillon.io/files/example.csv)
[Download](https://app-staging.apillon.io/files/example.csv)

#### Attributes


Attributes represent a crucial trait of NFTs and are a part of metadata that communicates detailed features of NFT contents.


Attributes can give details on the behavior of depicted characters or special abilities of a token that add some spice to the NFTs and give them more personality. A clearly defined theme or purpose of the collection will make it easier to set the attributes of your NFTs and have AI generators produce more accurate and likable results.


NFT collections deployed with Apillon can be shareable with NFT marketplaces, such as tofuNFT. To make your NFTs comply with how marketplaces display them, please read through the standard NFT Attribute guidelines by OpenSea.

[tofuNFT](https://tofunft.com/)
[NFT Attribute](https://docs.opensea.io/docs/metadata-standards#attributes)

#### Storing metadata


As an essential component of your NFT collection, metadata should be managed and stored carefully.


When uploaded via the NFT collection creation tool on the Apillon dashboard, metadata is automatically stored in a newly created Web3 Storage bucket, making it permanently accessible and unstoppable.

[Web3 Storage bucket](https://wiki.apillon.io/build/2-web3-services.html#storage-bucket)

You can also manually create a Web3 Storage bucket on the Apillon dashboard, upload your NFT metadata file, and call the metadata URI in the NFT collection deployment process.


### Deploy NFT collection at Apillon


Now that you have created unique pieces of your artistic expression and have a metadata CSV file at hand, you’re ready to start your NFT journey on the Apillon platform.


Check out the next NFT Service guide and deploy your NFT collection on Moonbeam in just a few steps. 👇

[Guide: NFT Service Pt. 2 — Create and deploy NFT collection on MoonbeamIn this guide, you will learn step-by-step how to go from raw data and files to a permanently deployed NFT collection…blog.apillon.io](https://blog.apillon.io/guide-nft-service-pt-2-create-and-deploy-nft-collection-on-moonbeam-2d7eedf79756)

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