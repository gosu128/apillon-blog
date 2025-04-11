+++
title = "Schrödinger’s NFT Beta live on Apillon"
date = "2024-02-27T13:55:35+0000"
description = "After the initial demo release, the NFT-based encryption functionality is now available for Apillon Beta users."
draft = false
+++

### Schrödinger’s NFT Beta live on Apillon


#### After the initial demo release, the NFT-based encryption functionality is now available for Apillon Beta users.

[Why NFTs for unlocking files?](#a9cc)
[Access restricted to NFT owners](#365d)
[How does it work?](#2b9e)
[Technical details and limitations](#73e8)

Last year, Apillon’s concept of encrypting private files using an NFT as a key was brought to the public eye. Now, it’s available as a ready-to-use functionality for Beta users of the Apillon platform.

[brought to the public eye](https://blog.apillon.io/polkadot-has-decoded-a-new-future-cf1f8bab2a24#c166)
[Schrödinger’s NFT — Unlock encrypted files with NFT keyIn the upgraded NFT Service powered by Phala’s Phat contract logic, private files can be decrypted only via a…blog.apillon.io](https://blog.apillon.io/schr%C3%B6dingers-nft-unlock-encrypted-files-with-nft-key-eeab55ae6bdf)

Schrödinger’s NFT represents the first integration of Phala’s Phat contract on Apillon, where specific logic allows admins to encrypt files and users to decrypt them using an NFT from a linked NFT collection.


In this case, an NFT works as an authorization lock that only unlocks contents when the correct key is used. The encryption/decryption key is generated and used only within the smart contract and never gets exposed externally.


Now, let’s dive into how you could make use of it in your Web3 project.


### Why NFTs for unlocking files?


NFTs have a range of purposes, spanning well beyond their most widely-known utility in collecting. In essence, NFTs are binary blockchain-based proofs of digital asset ownership — you either own something or you don’t.


Starting from this premise, the Apillon team had the idea of giving users the means to build an NFT collection and share exclusive or sensitive files or information only with persons who own a certain NFT key and use it to decrypt the files in question.


However, encryption and decryption of such private files could only happen in a trusted execution environment (TEE) to ensure full Web3 compatibility, privacy, and security. Based on that requirement, Phala’s Phat contracts became the chosen integration that allowed Apillon to achieve the intended functionality.

[Phala’s Phat contracts](https://docs.phala.network/developers/phat-contract)

#### Use cases


Schrödinger’s NFT by Apillon serves as an encryption/decryption method to seal and reveal private files on demand and to rightful users only.


Unlike passwords, which can be shared with dozens of persons and used by all to access the locked contents, an NFT key only works for the person owning it in their wallet.


Schrödinger’s NFT file encryption could be used in a range of scenarios.


The NFT encryption method is handy in the peer-to-peer transfer of assets, files, and other contents. It cuts the need for a trusted intermediary or custodian and, instead, unlocks assets cryptographically.


### Access restricted to NFT owners


Imagine you create an NFT collection and have a unique file, such as a text file or some other content that you want to be accessed exclusively by the owners of your NFTs.


With Schrödinger’s NFT, you can assign such a file to an NFT and encrypt it using a key generated in the smart (Phat) contract. Now, it can be published anywhere online without the risk of unauthorized access. If your followers wish to access the encrypted file, they will not be able to do so unless they own an NFT from your collection.


In essence, the non-fungibility of an asset extends to its accessibility, too.


### How does it work?


Schrödinger’s NFT embodies the first integration of Phala’s Phat contract on the Apillon platform, hence it can be found under the Computing service on the Apillon dashboard.

[Computing](https://app.apillon.io/dashboard/service/computing)

But it also combines the features and capabilities of the Moonbeam, Astar, and Crust Network. Encrypted files are stored on IPFS and pinned via Crust. The complete logic for file encryption, together with the decryption key, is hosted via the Phala network’s decentralized cloud computing and powered by a Phat contract. The NFT that contains the key for encrypting/decrypting files can be issued on Moonbeam or Astar out of the box on the Apillon platform, or any EVM chain — under the Chain RPC URL, you can input custom value.


As a completely decentralized method of sharing private files, mainly thanks to IPFS-based decentralized storage, it’s unstoppable from third-party intervention.


To illustrate the mechanics behind Schrödinger’s NFT, let’s take the diagram below:


The same logic can be expanded to further stages. A user who originally minted an NFT that contains a key may sell or send it to another wallet, transferring the capability to decrypt the files encrypted by the original NFT creator.


### Technical details and limitations


In the process of development and integration of Schrödinger’s NFT into the Apillon platform, certain technical aspects had to be taken into account:


### Start encrypting using NFTs


Schrödinger’s NFT encryption functionality is readily available on the Apillon platform for Beta users.


Protect your sensitive files in a non-fungible manner and start encrypting with Apillon.


### ⧓ About Apillon


The Apillon platform serves as a unified gateway to the Web3 services provided by linked Polkadot parachains. Following the multi-chain vision, Apillon powers developers’ transition to Web3, simplifying its adoption in the real economy and expanding its versatility as the ecosystem grows. With Apillon, Web3 services are within reach for every developer, regardless of their background and experience with blockchain technology.


Website | Wiki | GitHub | X | Telegram | LinkedIn | Reddit

[Website](https://apillon.io/)
[Wiki](https://wiki.apillon.io/)
[GitHub](https://github.com/Apillon-web3)
[X](https://twitter.com/apillon_io)
[Telegram](https://t.me/Apillon_io)
[LinkedIn](https://www.linkedin.com/company/apillon/)
[Reddit](https://www.reddit.com/r/apillon/)