+++
title = "w3ndi, a w3n-based digital address index, launched on Nova Wallet"
date = "2023-08-24T08:48:04+0000"
description = "The joint initiative by Apillon, KILT Protocol, and Nova Wallet marks another step towards simplification of Web3 UX."
draft = false
+++

### w3ndi, a w3n-based digital address index, launched on Nova Wallet


#### The joint initiative by Apillon, KILT Protocol, and Nova Wallet marks another step towards simplification of Web3 UX.

[What is w3ndi?](#2bda)
[Why w3ndi and how does it work?](#095a)
[Apillon, KILT, and Nova Wallet joining forces](#adb1)

### What is w3ndi?


w3ndi (you can call it Wendi, too) is an Apillon-built decentralized index of digital accounts that links your web3name (w3n) by KILT Protocol with your digital addresses. It currently supports Polkadot (including KILT and other parachain address types) and other popular chains, such as Ethereum, Bitcoin, etc.

[w3ndi](https://medium.com/@apillon/w3ndi-a-w3n-based-digital-address-index-launched-on-nova-wallet-bb5c3ba70cd8)

With w3ndi, you can browse digital wallet accounts tied to your web3name, KILT’s human-readable format for decentralized identifiers (DIDs), by chains and tags. Instead of copy-pasting lengthy, meaningless strings of alphanumeric characters, you can initiate crypto transfers with just a few clicks.


The first app to integrate w3ndi is Nova Wallet.


### Why w3ndi and how does it work?


UX is a huge friction point of Web3. Everyone is familiar with using lengthy strings of characters and numbers, double-checking just the first and the last few ones, if at all. Too often, users neglect their responsibility to verify addresses, which could even lead to funds drain. Or, they verify a recipient’s address by first transferring a small test amount before moving larger crypto numbers. But users are hardly to blame. Clumsy UX is.

[UX is a huge friction point of Web3](https://blog.apillon.io/why-web3-needs-a-ux-framework-e0db6806a579)
[funds drain](https://twitter.com/cz_binance/status/1686764372616515585)

The user interface of dapps has come a long way since the early days of Web3, with new solutions that stay true to the principles of decentralization while going easy on end users. KILT has redefined how we think of decentralized digital identity by introducing W3C-compliant DIDs, how we attach and attest its components (digital addresses included), and how we represent DIDs in a human-readable, memorable form with web3name (w3n).

[web3name](https://docs.kilt.io/docs/concepts/web3names/)

A few months ago, KILT partnered with Nova Wallet to allow for easy user and digital address search. However, the initial process of associating addresses with web3name required users to master certain technical skills.

[partnered with Nova Wallet](https://medium.com/kilt-protocol/send-funds-to-a-web3name-via-nova-wallet-b3182457c90b)
[the initial process of associating addresses with web3name](https://docs.novawallet.io/nova-wallet-wiki/help-and-support/associate-address-with-web3name)

Now, a more user-friendly w3n-address linking method has come to life with w3ndi.


Link addresses once, and use them as you go with just a few clicks.


#### w3ndi app by Apillon


w3ndi simplifies the process of attaching digital wallet addresses to your DID and w3n by KILT, ultimately, your digital identity.

[https://w3ndi.apillon.io/](https://w3ndi.apillon.io/)

The first integration of the w3ndi app by Apillon is live on Nova Wallet, a leading crypto wallet in the Polkadot ecosystem. With w3ndi enhancing the Nova UX, you can easily find peers in the Web3 community by their web3name, and initiate transactions without having to know or double-check the exact and complete alphanumeric strings of their addresses.

[Nova Wallet](https://novawallet.io/)

#### How does it work?


The free-to-use w3ndi app is accessible at w3ndi.apillon.io.

[w3ndi.apillon.io](https://w3ndi.apillon.io/)

Once you connect with your Sporran wallet from KILT and select the digital identity represented by your DID or w3n by KILT, you can start attaching your digital wallet addresses from multiple networks and create a self-sovereign wallet registry under a single name.


Using tags, you can differentiate between various-purpose addresses, e.g. Friends and family, Business, Charity, etc. You can also choose to make an address work on multiple chains.


In the process of linking w3n with digital addresses, w3ndi generates a JSON file containing identifiers for different wallet addresses that you attached to your web3name on the KILT parachain. To ensure unstoppable access, the file is stored on IPFS and pinned via Crust Network.

[IPFS](https://ipfs.tech/)
[Crust Network](https://crust.network/)
[GitHub - Apillon-web3/w3ndi-app: Repository for: https://w3ndi.apillon.io/Repository for: https://w3ndi.apillon.io/. Contribute to Apillon-web3/w3ndi-app development by creating an account on…github.com](https://github.com/Apillon-web3/w3ndi-app)

With w3ndi on Nova Wallet, your human-readable w3n nickname opens up an index of all your linked digital addresses. Thanks to added tags, you can easily differentiate accounts and mitigate the risk of interacting with the wrong one.


To send funds, simply type in the recipient’s w3n using “w3n:[name]” and select an account based on its tag. Or, to receive a deposit, let the sender know your w3n and the tag that defines the correct address. All in just a few clicks.


In Nova Wallet, w3ndi makes digital asset exchange seamless and user-friendly. When integrated into other apps, w3ndi could expand its usability of linking human-readable w3n with digital addresses.


Learn step-by-step how to use w3ndi. 👇

[Guide: Use w3ndi to connect your digital addresses to w3n by KILT, and use it in Nova WalletLearn how to aggregate all your digital wallet addresses under one web3name and simplify crypto transactions in Nova.blog.apillon.io](https://blog.apillon.io/guide-use-w3ndi-to-connect-your-digital-addresses-to-w3n-by-kilt-and-use-it-in-nova-wallet-de98a1289aae)

#### Fully decentralized


As you save and deploy an address in w3ndi, the address index file is pinned to IPFS via Crust with a unique CID, enabling the w3n name resolution service and keeping it fully decentralized.


Each time you change or add a new address, the address pointers change, too, and a new unique CID is generated.


If you decide to delete all addresses, you must deploy changes, resulting in an empty w3n name resolution. Keep in mind that the minimal period of file pinning is six months, so files are deleted only after that period has passed.


### Apillon, KILT, and Nova Wallet joining forces


w3ndi is a result of collaboration among three Polkadot projects, each contributing its distinct qualities:

[KILT Protocol](https://www.kilt.io/)
[w3ndi by Apillon](http://w3ndi.apillon.io)
[Nova Wallet](https://novawallet.io/)

In addition, Crust Network supplies decentralized storage and pins w3ndi’s index JSON file on IPFS, ensuring permanent access to the owner of the file’s link.

[decentralized storage](https://wiki.apillon.io/build/2-web3-services.html#web3-storage)

Try w3ndi on Nova Wallet today, and use your w3n by KILT for seamless crypto transfers.


#### About KILT Protocol


KILT is a blockchain protocol for generating decentralized identifiers (DIDs) and verifiable credentials, providing secure, practical identity solutions for enterprise, government and consumers.

[KILT](http://kilt.io/)

#### About Nova Wallet


Nova Wallet is a next-gen Polkadot and Kusama ecosystem app that brings a convenient, fast, and secure wallet experience on mobile devices, supporting 80+ networks and assets, NFTs, XCM transfers and more.

[Nova Wallet](https://novawallet.io/)

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