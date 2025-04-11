+++
title = "Apillon Simplet #4 — PoAP (Proof-of-Attendance) NFTs"
date = "2025-04-01T13:45:40"
description = "This solution allows brand to issue NFT proofs of attendance to the participants in their event or campaign, serving as a collectable or…"
draft = false
+++

### Apillon Simplet #4 — PoAP (Proof-of-Attendance) NFTs


#### This solution allows brand to issue NFT proofs of attendance to the participants in their event or campaign, serving as a collectable or memorabilia.

[What does this Simplet do?](#c88d)
[Where does it come in handy?](#5fde)
[Why the PoAP NFT simplet?](#b73a)
[How can you use it?](#2e4e)
[How to run this simplet?](#b91b)

In this post, we dive into the fourth on the list of prebuilt solutions by Apillon, a.k.a. simplets — the PoAP NFT simplet.


The PoAP acronym stands for proof of attendance, meaning the distributed NFTs serve as a proof of a person attending a brand event or campaign, which can later be kept as a memorabilia or traded as a collectible.

[Apillon’s prebuilt solutions help brands launch Web3/NFT campaignsThe customizable templates significantly shorten the brands’ campaign launch trajectory and simplify the user…blog.apillon.io](https://blog.apillon.io/apillons-prebuilt-solutions-help-brands-launch-web3-nft-campaigns-be2415ccb9ce)

Let’s inspect the bolts and nuts of this simplet and its mechanics.


### What does this simplet do?


With this solution, you can reward your audience for participating in your event, either live or online, with an NFT souvenir that serves as a proof of their engagement.


### Where does it come in handy?


At live events, attendees often can’t be bothered or don’t have time to deal with the process of acquiring an NFT reward. But they can choose to mint or reserve them later.


To boost the turnout at live events and reward your audience, you can create community campaigns with Proof-of-Attendance NFTs.


The solution comes with a landing page template that hosts a constantly updating QR code and email flow for NFT distribution. Written in React, they are both customizable so you can align them fully with your brand’s look and feel.


At the live event venue, put up a tablet showing your landing page with a QR code that updates every few seconds — this guarantees the scans are done by attendees in person. For online events, you can simply add the QR code to the hosting website.


Once the attendees scan the code, they enter your preset email flow to receive an NFT, and join your contact list easily and fast.


### Why the PoAP (proof of attendance) NFT simplet?


With the PoAP NFT Simplet, you can boost your community engagement and convert event attendees into email leads, without having to understand or navigate the complex blockchain-based back end.

[https://app.apillon.io/dashboard/solution/proof-of-attendance](https://app.apillon.io/dashboard/solution/proof-of-attendance)

Once you’re done creating your NFT collection on the Apillon dashboard, you can attach it to the admin flow and have the attendees mint or email-reserve their NFT rewards at the event.


Thanks to a simplified workflow, such campaigns can be used by all kinds of organizations or events, even when they don’t have a Web3 engineer at hand to build everything from scratch.


### How can you use it?


On your admin panel, you can create new or manage existing events that come with NFT rewards for the attendees.


The QR code to claim or reserve NFTs can be displayed on the event’s venue or website, allowing participants to initiate the process, but — if they wish — finish it later, once the event is over.


On the provided email, attendees receive instructions for minting NFTs and a link to the mint-NFT page.


### How to run this simplet?


Before you launch this simplet at your event and allow participants to mint NFTs, make sure you have put in place the following:

[Apillon NFT Service](https://app.apillon.io/dashboard/service/nft)

#### But why do you need all these things?


Apillon simplets are designed as complete packages of Web3/decentralized solutions. By design, they rely on several decentralized services provided by Apillon that should be implemented for the simplet to work as intended.


In the case of the PoAP NFT Airdrop simplet, these are the following:


#### Implementation


There are two parts to deploying a simplet: the front end and the back end.


The Vue.js front end can be run on your computer or hosted on any website provider, such as WordPress. It’s, however, advisable you host it on your server of choice in a completely decentralized way using Apillon’s Web3 Hosting service.

[Apillon’s Web3 Hosting](https://app.apillon.io/dashboard/service/hosting)

As for the Node.js back end, you can run it locally on your computer or, if you prefer, use a tool called Docker and customize configuration files with your campaign’s information, such as NFT details and email server data.

[GitHub](https://github.com/Apillon/ps-proof-of-attendance)

#### Admin view


Once you’re done setting up both the front and back end of the solution, you can initiate the campaign building on your admin panel. First, connect with you EVM-compatible wallet — MetaMask, Coinbase Wallet, or WalletConnect.


Click on the “Create new PoAP” button, select the NFT collection you’ve created on the Apillon dashboard and click “Next” to start adding details.


Choose the title of the NFT Airdrop campaign and, if you wish, its description. You should also set its start and end time — we advise you inform your community about it so they don’t miss it. Optionally, you can also add the relevant website (where they can claim NFTs?).


When all the details are set, click “Next”.


Review the campaign details once again and if everything seems fine, click “Create”.


Once added, the admin panel displays all the information on a list of PoAP NFT events, so you can easily browse between them and monitor their activity.


When you click on an event on the list, the admin panel further displays relevant details, including countdown to event launch, attendees’ email, the status of their NFT airdrop, wallet address, and transaction hash for already completed NFT claims.


It also comes with links to QR-displaying website and the page where the participants can reserve their NFT proofs of attendance.


#### User view


Once the attendees scan your QR code at the event, they are prompted to enter their email — meaning they don’t need to have a wallet at the moment of NFT claim and they can deal with providing one later, after the event.


The email flow you add to the campaign can contain specific instructions on how to setup a digital wallet (for users who don’t have any) and link to the mint-NFT page where the users can get their rewards.


That’s it — you can convert your event attendees into new leads and an inspired audience with digital rewards. They can store their NFTs in their wallets as memorabilia or decide to exchange or trade them as per your campaign’s T&C.


### Simplet, but make it custom


The PoAP NFT Airdrop simplet is made to boost your community engagement at live events without massive investment in research and development.


Still, if you lack even the basic know-how to use this pre-production simplet, you can always reach out to the Apillon tech team over our Contact form and ask for free support with the installation.

[Contact form](https://apillon.io/contact)

If, on the other hand, your event needs a highly customized solution to cover its specifics, reach out and let’s talk details.
