+++
title = "Apillon Milestone 1 Proposal Recap — Done and done ✔️"
date = "2024-04-10T11:11:51+0000"
description = "Despite a heavy load on our plate, nearly all deliverables from Apillon’s Polkadot Treasury Milestone 1 Proposal have been achieved and…"
draft = false
+++

### Apillon Milestone 1 Proposal Recap — Done and done ✔️


#### Despite a heavy load on our plate, nearly all deliverables from Apillon’s Polkadot Treasury Milestone 1 Proposal have been achieved and implemented.

[Apillon Milestone 1 Proposal](#3c39)
[Deliverables status](#9e5d)

### Apillon Milestone 1 Proposal


Back in September last year, Apillon submitted a revised proposal to Polkassembly OpenGov asking for Polkadot Treasury to back up the platform’s technical development.


The main objective was to turn Apillon into a growth-oriented, SaaS Web3 development platform fueled by user subscriptions. Besides, the upgrade would offer a much wider array of Web3 services and solutions to the developer community while allowing builders to participate in the platform’s evolution through open-source code.

[Referendum #161](https://polkadot.polkassembly.io/referenda/161)

The Proposal passed with an overwhelming majority, with 93% of votes in favor. And the work began.


Read 👉 Full Apillon Milestone 1 Proposal

[Full Apillon Milestone 1 Proposal](https://ipfs.apillon.io/ipfs/Qmaeq4CpaLMKL4HBX2z2C8QM2ZZEuJvhv8nfWF7FKANZqv)

### Deliverables status


Acknowledging the broad scope of work needed to be done, Apillon decided to split the mid-term technical development trajectory into milestones, each covering a specific array of tasks and deliverables.


The Milestone 1 Proposal primarily focused on improving the platform’s UI, enhancing the currently provided services with advanced features or options, introducing IPFS-based support on several instances, and equipping developers with ample documentation, SDKs, and CLIs.


✔️ Apillon Goes Open-Source✔️ Schrödinger’s NFT Service✔️ User Accounting✔️ Subscription Module✔️ Fiat Payment✔️ DOT Payment🔜️ PAPI Refactor (moved to Milestone 2) ✔️ NFT Deployment Wizard Improvements / UI Upgrades✔️ SDK for All Services✔️ CLI for All Services✔️ API Expanded With Code Samples in Multiple Languages✔️ WASM Support on Astar✔️ No-Code Wizard for RMRK NFT Standard🔄 Wunderbar in Web3 Hosting (changed to Grill.chat)✔️ Dashboard UI Split to Web3 Services, Multiple Chains and Prebuilt Template Solutions✔️ Prebuilt NFT-Based Solutions✔️ IPFS Cluster and Load Balancer✔️ IPFS Web3-Approved Domains✔️ IPFS CDN✔️ IPFS Custom Gateways✔️ IPFS Bandwidth Monitoring✔️ Wallet Identity SDK✔️ Flutter SDK🔜 Cloud Functions (moved to Milestone 2)

[Apillon Goes Open-Source](#376d)
[Schrödinger’s NFT Service](#5c94)
[User Accounting](#1e55)
[Subscription Module](#1f1b)
[Fiat Payment](#f77d)
[DOT Payment](#b7b0)
[PAPI Refactor](#56ea)
[NFT Deployment Wizard Improvements / UI Upgrades](#15a3)
[SDK for All Services](#7f0b)
[CLI for All Services](#ab31)
[API Expanded With Code Samples in Multiple Languages](#b763)
[WASM Support on Astar](#8083)
[No-Code Wizard for RMRK NFT Standard](#781a)
[Wunderbar in Web3 Hosting](#9cb3)
[Dashboard UI Split to Web3 Services, Multiple Chains and Prebuilt Template Solutions](#1ceb)
[Prebuilt NFT-Based Solutions](#7d6b)
[IPFS Cluster and Load Balancer](#924c)
[IPFS Web3-Approved Domains](#6008)
[IPFS CDN](#7abc)
[IPFS Custom Gateways](#c82b)
[IPFS Bandwidth Monitoring](#9fa4)
[Wallet Identity SDK](#c5db)
[Flutter SDK](#72e4)
[Cloud Functions](#f64d)

Now, let’s dive into the nitty-gritty of the technical work done at Apillon in the past few months.


#### ✔️ Apillon Goes Open-Source


As promised in the Milestone 1 Proposal, the Apillon platform has become entirely open-source and is accessible to developers to propose upgrades.


Before the complete code was released to GitHub, it was reviewed in depth by Go-Lix, a third-party code security reviewer, and scored 9/10 in the security report with only minor issues to fix.


The external code review was essential to protect Apillon’s production version and its current users from potential vulnerabilities that could harm their work.


To complement the code review, Apillon also released a Bug Bounty to encourage developers and white hat hackers to check the code and be rewarded for reporting potential issues.

[Bug Bounty](https://github.com/Apillon/apillon-services/blob/master/BUG_BOUNTY.md)

👉 The complete code is available on Apillon GitHub.

[Apillon GitHub](https://github.com/Apillon/apillon-services)

#### ✔️ Schrödinger’s NFT Service


Apillon’s NFT Service was upgraded with Phala integration into a fully-fledged decentralized file-sharing and encryption solution.


The result, Schrödinger’s NFT service, is backed by out-of-the-box Phat Contract configuration, while deployment-wise, it connects to the NFT and Crust-based Web3 Storage services.


For easier use, it comes equipped with Docs, API, SDK, CLI, and usage templates.


🔎 To view the demo of the Schrödinger’s NFT service, watch this video.

[this video](https://www.youtube.com/watch?v=FhwYaEbuAuk&t=448s)
[Schrödinger’s NFT Beta live on ApillonAfter the initial demo release, the NFT-based encryption functionality is now available for Apillon Beta users.blog.apillon.io](https://blog.apillon.io/schr%C3%B6dingers-nft-beta-live-on-apillon-73f03d6b61cd)
[Phala’s Phat Contract to bring efficient computing to Apillon Beta usersPhat Contract’s off-chain computation enhances a dapp’s performance, is multi-chain compatible, and ensures greater…blog.apillon.io](https://blog.apillon.io/phalas-phat-contract-to-bring-efficient-computing-to-apillon-beta-users-591332fd86a6)

#### ✔️ User Accounting


Apillon was always vocal about providing scalability for Web3 developers through predictable pricing, and a granular user accounting feature was designed to account for all blockchain and non-blockchain infrastructure costs.


Today, the user accounting module delivers average spend-per-account calculations. This allows Apillon to capture each transaction, price it according to the asset price at acquisition time, and keep track of average spending by Freemium or paying accounts.


What’s more, the module enables the formation of explicit pricing models that translate into credits and monthly subscriptions while compensating for asset price volatility by targeting average account consumption.


The feature is accessible on the Apillon Dashboard to all users who engage with credits and/or subscriptions.


#### ✔️ Subscription Module


The monthly subscription module was one of the main objectives in transforming Apillon into a typical SaaS business model, and it has been available to platform users for the past few months.


The feature is powered by Stripe and has introduced smooth payment of subscription plans and credit-based charges for paid platform features.


#### ✔️ Fiat Payment


The implementation of the subscription model above simultaneously required the platform to enable credit card payments for users to acquire credits.


The feature of payment with fiat for Apillon services has been available on the dashboard for the past few months.


#### ✔️ DOT Payment


In the Web3 space, fiat-only payments do not cut it. By complementing them with Polkadot’s DOT payment option, Apillon provided platform users with the option to maintain their Web3 privacy while accessing the full range of Apillon’s offerings.


DOT payments have been available on Apillon in production. The current provider holds a caveat that affects the minimum buy amount, depending on the DOT price during periods of high volatility, requiring additional monitoring and adjustments from the Apillon side. However, the minimum buy ratio on the DOT payments is expected to be fine-tuned within the next few months.

[$DOT payments now fully supported on the Apillon platformApillon integrates NOWpayments to offer a seamless $DOT payment option on their Web3 development platform.blog.apillon.io](https://blog.apillon.io/dot-payments-now-fully-supported-on-the-apillon-platform-7d9293f4104a)

#### 🔜️ PAPI Refactor (moved to Milestone 2 Proposal)


This deliverable aimed at refactoring all Polkadot.js-related services to the PAPI library.


However, since the first stable version of PAPI has not yet been released and should become accessible in August 2024 or later, Apillon was obligated to move the task to the Milestone 2 Proposal without incurring additional charges to OpenGov.


#### ✔️ NFT Deployment Wizard Improvements / UI Upgrades


The flow of creating and launching an autonomous NFT collection on the Apillon dashboard has been updated — it now allows users to create NFTs individually or in bulk using a .csv file.


The NFT service UI was further upgraded to simplify NFT minting for non-developers and attract more beginners to the Web3 space.


#### ✔️ SDK for All Services


The Apillon SDK (software development kit) version 1.0.0 was successfully launched along with Apillon 1.0.0 in 2023 when the platform stepped out of Beta mode.


It is composed in TypeScript and hosted on NPM. Currently, it features its second major version and attracts steadily growing weekly downloads.

[Apillon Wiki](https://wiki.apillon.io/build/5-apillon-sdk.html)

Using SDK, developers can interact with the Apillon API through code statements instead of raw API calls, simplifying and accelerating their development process through prebuilt modules, code classes, and types.


The Apillon SDK currently supports all of the platform’s available modules: Web3 Storage, Web3 Hosting, NFTs, Web3 Computing, and Web3 Social. It also contains a bonus Wallet Identity module for verifying wallet signatures and retrieving on-chain wallet identity.


The links below provide more detailed information, development guides and code examples for each module.


👉 SDK on Apillon GitHub👉 SDK in NPM👉 SDK on Apillon Wiki👉 SDK detailed Typedoc👉 GitHub SDK demo👉 SDK CodeSandbox demo

[SDK on Apillon GitHub](https://github.com/Apillon/sdk)
[SDK in NPM](https://www.npmjs.com/package/@apillon/sdk)
[SDK on Apillon Wiki](https://wiki.apillon.io/build/5-apillon-sdk.html)
[SDK detailed Typedoc](https://sdk-docs.apillon.io/)
[GitHub SDK demo](https://github.com/Apillon/apillon-sdk-demo)
[SDK CodeSandbox demo](https://codesandbox.io/p/github/Apillon/apillon-sdk-demo/master)

#### ✔️ CLI for All Services


The Apillon CLI (command line interface) is a text-based interface that interacts with the Apillon API by typing commands into a terminal or command prompt.


With CLI, developers can send requests and commands to the Apillon API using simple text commands instead of having to write code or send HTTP requests using other tools.

[Apillon Wiki](https://wiki.apillon.io/build/6-apillon-cli.html)

A very strong use case for the CLI, besides facilitating API interactions, is its utility within CI/CD pipelines and scripting. For example, a simple shell script to automate a workflow can be easily written, which would otherwise require manual work on the Apillon dashboard. Or, a few commands can easily be integrated into an automated CI/CD pipeline script to perform an action, e.g., publish a new website code to Apillon Web3 Hosting as soon as the new code is pushed to a dedicated Git repository.


The links below provide more detailed information for all modules supported by the CLI, currently Web3 Storage, Web3 Hosting, and NFTs.


👉 CLI in NPM👉 CLI on Apillon Wiki

[CLI in NPM](https://www.npmjs.com/package/@apillon/cli)
[CLI on Apillon Wiki](https://wiki.apillon.io/build/6-apillon-cli.html)

#### ✔️ API Expanded With Code Samples in Multiple Languages


To enhance developers’ interaction with the Apillon API and accelerate project launches, Apillon provides multiple code samples in different languages that complement the platform’s existing suite of API tools.


The code samples work out of the box and are currently written in PHP, Python, and .NET Core (C#), while Typescript samples are already available on Apillon Wiki. Support for other languages and libraries will make its way to the Apillon users soon.


The examples are fully open-sourced, and developers are encouraged to update the code samples with more code or add support for their favorite language that has not yet been added to the repository.


👉 Code samples GitHub repo👉 SDK demo on GitHub👉 SDK CodeSandbox demo

[Code samples GitHub repo](https://github.com/Apillon/code-examples)
[SDK demo on GitHub](https://github.com/Apillon/apillon-sdk-demo)
[SDK CodeSandbox demo](https://codesandbox.io/p/github/Apillon/apillon-sdk-demo/master)

#### ✔️ WASM Support on Astar


In addition to the EVM-based NFT smart contract offering, Apillon now gives seamless access to WASM smart contract for building NFT collections (PSP-34).


The WASM smart contract option is aligned with the previous NFT creation flow and is supported by the Astar network, allowing users to send NFTs to Substrate-based addresses.


#### ✔️ No-Code Wizard for RMRK NFT Standard


Soon after implementing the support for the RMRK nestable NFT standard on the Apillon platform, the Apillon team recognized the need for a comprehensive UI wizard to boost the adoption of said feature.


The brand new nestable wizard is now available on Apillon production, allowing users to nest their NFTs with a few clicks.


🔎 To view the RMRK nestable standard UI on Apillon, watch this video.

[this video](https://youtu.be/DWS7d9tihrQ)

#### 🔄 Wunderbar in Web3 Hosting (changed to Grill.chat Integration)


In the Milestone 1 Proposal, the integration of the Wunderbar analytics tool was planned to allow dapp monitoring for Apillon users. However, certain challenges led to the Wunderbar project’s hiatus and caused the Apillon to change the deliverable.


Understanding the need for Web3-based social interactions for community building, we decided to bring Subsocial’s Grill.chat to the Apillon platform.


With Grill.chat integration, users can launch a customized decentralized chat instance into any front-end framework within minutes by using 20 lines of pre-made code.


🔎 To view Apillon’s Grill.chat integration, watch this video.

[this video](https://youtu.be/cDhjE2Ia5SY)
[Grill.chat by Subsocial integrated into ApillonIn just a few steps, you can enhance your dapp with a fully decentralized chat room to grow and nurture your Web3…blog.apillon.io](https://blog.apillon.io/grill-chat-by-subsocial-integrated-into-apillon-adfd6b7177a8)

#### ✔️ Dashboard UI Split to Web3 Services, Multiple Chains, and Prebuilt Template Solutions


In its initial version, Apillon offered two Web3 services, namely Decentralized Storage and Decentralized Hosting. However, as the array of services and features offered on the platform expanded, so grew the need to organize and display them neatly.


The revamped Apillon dashboard is now in production and the new setup is primed for long-term compatibility with new features released by Apillon.


To review Apillon’s solutions portfolio reorganization, watch this video.

[this video](https://www.youtube.com/watch?v=KxzNqbgiEeI)

#### ✔️ Prebuilt NFT-Based Solutions


Prebuilt solutions are one of the most significant new features of Apillon and a pinnacle of in-house innovation combining the best of the two worlds.


Apillon prebuilt solutions are open-sourced docker images that include typical Web2 full-stack open-source solutions, e.g., Node.js, Express.js, SQL DB, front-end Vue.js or any other, and docker configs.


They can be deployed by any user with a few clicks by accessing the complete code and adjusting them to their project needs, all without the need to understand or deep-dive into background blockchain complexities.


👉 Email Airdrop👉 Whitelist Claim👉 Signup Email Airdrop👉 Proof of Attendance NFTs👉 WASM Proposal Airdrop👉 PINK NFTs👉 Ment NFT Mint

[Email Airdrop](https://github.com/Apillon/ps-email-airdrop)
[Whitelist Claim](https://github.com/Apillon/ps-whitelist-claim)
[Signup Email Airdrop](https://github.com/Apillon/ps-signup-email-airdrop)
[Proof of Attendance NFTs](https://github.com/Apillon/ps-proof-of-attendance)
[WASM Proposal Airdrop](https://github.com/Apillon/ps-wasm-proposal-airdrop)
[PINK NFTs](https://github.com/Apillon/PinkNft)
[Ment NFT Mint](https://github.com/Apillon/ment-nft-mint)

#### ✔️ IPFS Cluster and Load Balancer


Apillon’s IPFS infrastructure was organized across several cloud platforms, deploying clusters of IPFS servers complemented by load balancers. This setup guarantees uptime, scalability, and performance, enabling decentralized storage solutions and fail-safe website hosting for the platform users.


Leveraging the IPNS protocol, Apillon now provides users with a dynamic storage system that supports mutable files and custom domain options for website hosting. Furthermore, Apillon’s integration of the Crust Network enhances the Web3 Storage service with steadfast file pinning, ensuring the longevity and accessibility of data within the network. The complex blockchain-based development processes were thus simplified for a hassle-free user experience.


#### ✔️ IPFS Web3-Approved Domains


To enhance security and preserve the integrity of Apillon’s base domain, the platform introduced additional domains dedicated to hosting user content.


Initially, Apillon opted for web3approved.com but later transitioned to nectarnode.io. Now, users can access their files, folders, and websites through an IPFS or IPNS-based subdomain of nectarnode.io, formatted as <cid>.ipfs.nectarnode.io or <ipns value>.ipns.nectarnode.io respectively.

[web3approved.com](http://web3approved.com)
[nectarnode.io](http://nectarnode.io)

This approach simplifies how users host static websites built with modern web frameworks without the need for a custom domain setup.


Moreover, Apillon empowers users to connect their custom domains to their content. As part of this service, they can access a complimentary SSL certificate for their websites, ensuring secure encrypted connections. This comprehensive strategy bolsters security and simplifies access to decentralized content hosting.


It goes without saying that the integrity of the platform’s Web3 hosting environment and our commitment to maintaining a safe and clean Internet is high on Apillon’s priority list. To prevent the dissemination of malicious content, the platform implements a manual review process for content deployed by users without a subscription.


#### ✔️ IPFS CDN


Apillon’s public and private token-gated IPFS gateways leverage AWS and Google’s content delivery networks (CDNs). This strategy is designed to reduce the bandwidth demands on the Apillon infrastructure while ensuring that users receive fast, cached content.


Apillon’s premium users also have the flexibility to request the service of setting up a CDN for their custom domains and private IPFS gateways.


#### ✔️ IPFS Custom Gateways


Clients with special requirements can have their private IPFS clusters deployed on demand. This exclusive service allows our partners to utilize the cluster as a dedicated IPFS gateway to the broader network or to host and manage their files and websites seamlessly through the Apillon API, SDK, CLI, or web application interface.


In custom private IPFS clusters, Apillon uses JWT (JSON Web Token) token-gating functionality to safeguard against unauthorized bandwidth consumption by third parties. This feature also enables Apillon customers to securely generate JWT tokens directly through their own applications, guided by clear instructions and configurations available on the Apillon web console.


Customers also have the discretion to determine the accessibility of content through their private gateway. This content can be any file residing on the IPFS network. Moreover, they can share generated links with specific individuals or groups, and configure them to expire after a certain period.


This level of customization enables Apillon customers to exert complete control over the traffic flowing through their cluster.


#### ✔️ IPFS Bandwidth Monitoring


The integration of Apillon’s monitoring solution enhanced the management of traffic across the platform’s IPFS clusters, thus allowing efficient blacklisting or whitelisting of specific data, user accounts, and projects.


To maintain the integrity and exclusivity of the Apillon infrastructure, we implemented token-gated access through Apillon gateways. This system ensures that only requests with a valid JWT (JSON Web Token) are processed, safeguarding against external parties’ unauthorized exploitation of Apillon resources.


A crucial objective of Apillon’s monitoring framework was to guarantee equitable usage of platform-provided services through meticulous tracking of user bandwidth consumption. Users on Apillon’s complimentary plan are allocated up to 20 GB of bandwidth monthly. Users with greater requirements, however, can access additional bandwidth through paid subscription plans.


The Apillon platform notifies users as they approach their bandwidth limit. Once they reach it, their data becomes inaccessible either for the remainder of the month or until they upgrade to a higher-tier plan.


This policy supports Apillon’s commitment to fair usage and allows us to provide uninterrupted, secure services to all users.


#### ✔️ Wallet Identity SDK


The Wallet Identity SDK was added as a bonus module to the existing Apillon SDK to expand the set of tools offered to developers beyond the scope of Apillon modules.


The current functionalities implemented within the Wallet Identity SDK are wallet signature validations for both Substrate and EVM addresses and retrieval of on-chain wallet identity for Substrate addresses from Polkadot Identity and Subsocial (more sources will be added soon).

[Apillon Wiki](https://wiki.apillon.io/build/5-apillon-sdk.html#identity)

The wallet identity SDK has proven very useful since it was an integral part of Apillon’s prebuilt solutions implemented on multiple real-life occasions, such as the Pink NFT airdrop and the MENT Festival. The SDK helped verify signatures by users logging in with the wallet, facilitated their login flow, and introduced more security features, such as limited-time signatures.

[Pink NFT airdrop](https://twitter.com/pinkonomic/status/1755975915098579366)
[MENT Festival](https://medium.com/apillon/apillon-provides-nft-based-festival-memorabilia-for-ment-ljubljana-db375a5ca643)

👉 Wallet Identity SDK on GitHub

[Wallet Identity SDK on GitHub](https://github.com/Apillon/sdk)
[Apillon Features: EVM wallet loginIn addition to the already available Polkadot wallet connectivity, Apillon now supports profile entry using two major…blog.apillon.io](https://blog.apillon.io/apillon-features-evm-wallet-login-7bb550b02dd1)

#### ✔️ Flutter SDK


As we aim to expand the suite of developer tools and Web3 projects outreach further, Apillon published an SDK for the platform’s API written in Flutter. This allows Apillon users to reach an entirely new horizon building a Web3 mobile dapp on Android and iOS.


The Flutter SDK, besides granting mobile developers access to Apillon’s Web3 tools like Web3 Storage, NFTs, Web3 Hosting, and Web3 Authentication, gives them the freedom to integrate mobile-native features into their dapp, such as camera access, location, sensors, and more.

[Apillon Wiki](https://wiki.apillon.io/build/10-flutter-sdk.html)

The Flutter SDK integration creates a massive opportunity for mobile developers to easily create Web3 mobile dapps and capitalize on the vast mobile user landscape, easily leveraging Apillon’s existing infrastructure and facilitating the user flow.


For example, they could create NFTs in a few clicks by uploading them from a mobile phone instead of having to use the desktop browser version.


👉 GitHub repository 👉 SDK in pub.dev👉 Docs and code samples

[GitHub repository](https://github.com/Apillon/flutter-sdk)
[SDK in pub.dev](https://pub.dev/packages/apillon_flutter)
[Docs and code samples](https://wiki.apillon.io/build/10-flutter-sdk.html)

#### 🔜️ Cloud Functions


Decentralized cloud functions or Web3 back-end remain one of the most significant yet complicated features for Apillon to deliver.


In the Milestone 1 Proposal, Apillon aimed to tackle general-purpose decentralized cloud functions and researched both Phala and Acurast as options to provide such a solution. Phala Network works well for creating oracles, functions that directly interact with smart contracts; however, it currently does not enable running general-purpose functions that can be built in JavaScript or similar language. Acurast, on the other hand, supports general-purpose JavaScript functions and has upgraded its offering, allowing Apillon to execute this deliverable as a part of the Milestone 2 Proposal.


Currently, this deliverable is in the R&D phase, and as Acurast reaches maturity, most of the functionalities to deliver state-of-the-art Web3 Cloud features will be accessible to Apillon. To guarantee successful and thorough integration, the cloud functions features have been moved to Milestone 2 Proposal and should be achieved in the following months.


### Up next: Milestone 2


The past eight months have really been something. Even with technical deliverables aside, the Apillon platform saw incredible growth in user adoption, growing from a couple of thousand developers to over 100,000 builders ready to deliver the next big thing to Web3.


As the platform gained strong momentum, it’s the perfect time to continue with the steady pace toward new frontiers of simplified Web3 development for everyone.


Apillon just submitted the Milestone 2 Proposal on Polkassembly OpenGov that would help us deliver more advanced features to Apillon users, new and old, augment the adoption of Polkadot and decentralized technologies, and educate the community on the endless possibilities of Web3 building.

[Milestone 2 Proposal](https://bafybeigg4fzx2h55oedjn6v5jdi35y3qfb3gmcp3byf6psmyaeeokjdc5a.ipfs.web3approved.com/)

Join us and show your support! 🚀
