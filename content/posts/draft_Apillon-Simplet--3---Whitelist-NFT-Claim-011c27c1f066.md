+++
title = "Apillon Simplet #3 — Whitelist NFT Claim"
date = "2025-04-01T13:46:50"
description = "The solution allows brands to distribute NFT prizes to selected recipients only while simplifying admin and user experience."
draft = false
+++

### Apillon Simplet #3 — Whitelist NFT Claim


#### The solution allows brands to distribute NFT prizes to selected recipients only while simplifying admin and user experience.

[What does this simplet do?](#2686)
[Where does it come in handy?](#a381)
[Why the Whitelist NFT Claim simplet?](#cffd)
[How can you use it?](#85df)
[How to run this simplet?](#9ac2)

This post shines a light on the third simplet offered on the Apillon dashboard, the Whitelist NFT Claim solution.


It automates the delivery of NFTs to only the recipients selected by the campaign creator.

[Apillon’s prebuilt solutions help brands launch Web3/NFT campaignsThe customizable templates significantly shorten the brands’ campaign launch trajectory and simplify the user…blog.apillon.io](https://blog.apillon.io/apillons-prebuilt-solutions-help-brands-launch-web3-nft-campaigns-be2415ccb9ce)

Now, let’s see what the Whitelist NFT Claim simplet is all about.


### What does this simplet do?


In short, it help you distribute NFT rewards to only a handful of customers selected manually or automatically.


This way, your brand can launch unique campaigns, such as draws or competitions, where only a few chosen or winning participants have the privilege of receiving your NFT-shaped prizes.


### Where does it come in handy?


Brands that seek to increase customer engagement and participation in their offering can do so through different mechanisms, typically through competitions, gamifications, draws, etc.


With NFTs in the prize pool, they can demonstrate their commitment to constant innovation and competitiveness. Besides, customers are rewarded with an NFT — a prize that transcends brand campaign context, and opens an array of use, collecting or trading opportunities.


### Why the Whitelist NFT Claim Simplet?


With the Whitelist NFT claim simplet, you can launch a brand awareness and growth campaign easily and fast, without the need to dive deep into the nitty gritty back-end of blockchain technology.

[https://app.apillon.io/dashboard/solution/whitelist-claim](https://app.apillon.io/dashboard/solution/whitelist-claim)

With the help of your in-house IT engineer, you can launch an NFT collection in any format in a few minutes, upload the list of rightful NFT recipients, and initiate the automatic distribution to only the listed contacts.


NFT-based campaigns are thus no longer reserved for only the Web3-native brands, but can be accessed and implemented by everyone with a basic coding knowledge.


### What can you do with it?


Without the Apillon simplet, you could have a hard time assigning and allowing only specific user wallets to claim an NFT directly on-chain.


Luckily, Apillon’s Whitelist NFT Claim simplet cuts the long story short.


It incorporates off-chain signatures and on-chain verification method, which not only simplifies the developer and brand admin experience setting, updating and editing the whitelist addresses, but also lets customers claim their NFT rewards in a seamless UX.


### How to run this simplet?


There are a few things you or your enineer need to put in place to launch this simplet and, ultimately, your NFT campaign.

[ApillonNftWhitelistClaim contract](https://github.com/Apillon/apillon-evm-contracts)

#### But why do you need all these things?


Apillon Simplets are designed as complete packages of Web3/decentralized solutions. As such, they rely on several decentralized services that Apillon provides and that need to be implemented for the simplet to work as intended.


In the case of the Whitelist NFT Claim simplet, these are the following:


#### Implementation


The simplet can be deployed in two parts: the front end and the back end.


The Vue 3 front end can be run on your local computer or hosted on any website provider, such as WordPress. Or, you can host it on your server of choice in a completely decentralized way, courtesy of Apillon’s Web3 Hosting service, or using GitHub actions setup.

[Apillon’s Web3 Hosting](https://app.apillon.io/dashboard/service/hosting)

The Node.js back end of the simplet can also be run locally on your computer or, if it speaks more to your brand’s IT rulebook, using a tool called Docker where you can customize configuration files with your campaign’s information, like NFT details and email server data.

[GitHub](https://github.com/Apillon/ps-whitelist-claim)

#### Admin view


When both the back end and the front end are set up, you can continue in your admin panel. First connect your EVM-compatible wallet, either MetaMask, Coinbase Wallet, or WalletConnect.


To add the recipients of your NFT prizes, you can either upload them in bulk in a CSV file by clicking “Upload CSV” or individually by clicking “Add recipient”.


For individual entries, enter the recipient’s wallet addresses and set the amount of NFTs you wish to distribute to them. Click the green checkmark on the right.


For bulk entries of email recipients, click “Upload CSV”.


Once the CSV list is saved on your local drive, upload it and click “Start New Airdrop”.


Lastly, click “Save wallets”.


Once the NFT airdrop is ready on your side, it’s time to let your audience know about it and let them claim their NFTs.


#### User view


Direct the chosen recipients to the landing page you customized to fit your project or campaign.


You can see the example here 👉 https://whitelist-claim-app.demo.apillon.io/

[https://whitelist-claim-app.demo.apillon.io/](https://whitelist-claim-app.demo.apillon.io/)

First, they should connect their EVM-compatible wallet.


Next, they should initiate “Wallet eligibility check” and confirm the action in their wallet.


If their wallet address is on your whitelist, they will be prompted to “Claim their NFT(s)” and confirm the transaction in the wallet pop-up.


Next, their NFT minting starts, which takes a few minutes to complete. Once it’s done, they can see it in their wallet and check its status.


That’s it! Your customers can now enjoy their hard-earned NFTs and put it to further use as per your brand campaign’s rulebook.


### Simplet, but make it custom


The Whitelist NFT Claim simplet is designed to accelerate your brand’s path to launching an NFT-based community incentivizing campaign without massive investment in resources.


Still, if you lack even the basic know-how to use this pre-production simplet, feel free to reach out to the Apillon tech team over our Contact form and ask for free support with the installation.

[Contact form](https://apillon.io/contact)

If, on the other hand, you need a highly customized solution to cover the specifics of your project, reach out and let’s talk details.
