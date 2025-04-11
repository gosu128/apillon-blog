+++
title = "Reviewed and approved, vol. 2: Apillon’s progress did not go unnoticed"
date = "2023-08-01T06:39:27+0000"
description = "Successfully finalized Milestone 2 of the Substrate Builders Program; Milestone 3 tasks already in progress."
draft = false
+++

### Reviewed and approved, vol. 2: Apillon’s progress did not go unnoticed


#### Successfully finalized Milestone 2 of the Substrate Builders Program; Milestone 3 tasks already in progress.


In May, Apillon officially became a member of the Substrate Builders Program. Since then, we’ve been working even harder to justify the faith and trust put into our venture by Parity Technologies.

[Substrate Builders Program](https://substrate.io/ecosystem/substrate-builders-program/)
[Parity Technologies](https://www.parity.io/)

By delivering what was planned — and some extra features as well — Apillon has completed Milestone 2 of the Substrate Builders Program.


### Heart at work


Besides working on agreed-upon tasks to complete Milestone 2 successfully, a better part of the team’s resources was also directed into the Apillon Bounty Proposal (through Polkadot Treasury funds) that would make the Apillon platform an open-source common good infrastructure on Polkadot.

[Apillon Bounty Proposal](https://polkadot.polkassembly.io/referenda/81)
[an open-source common good infrastructure on Polkadot](https://blog.apillon.io/apillon-aims-to-foster-web3-adoption-as-a-common-good-infrastructure-solution-on-polkadot-6566508190c5)

By bringing this plan to fruition, the platform would provide permanent freemium access to the Polkadot community, fostering Web3 adoption and general growth and enhancing the utility of Polkadot’s native DOT token.


Nevertheless, our progress under the auspices of the Substrate Builders Program was not hindered, as our development team even managed to fulfill some of the tasks designated to Milestone 3, as it went hand in hand with our current development plan.


### Milestone 2 in the rear-view mirror


Apillon advanced on the ladder of Substrate Builders Program’s challenges but before we dive into the specifics, you can read through Milestone 1 tasks, all successfully completed.

[Apillon receives a mark of trust by being accepted into the Substrate Builders ProgramParity Technologies’ program welcomes the Web3 development platform to boost growth with extensive resources and…blog.apillon.io](https://blog.apillon.io/apillon-receives-a-mark-of-trust-by-being-accepted-into-the-substrate-builders-program-1e3ba4f29ff3)
[o](https://blog.apillon.io/apillon-receives-a-mark-of-trust-by-being-accepted-into-the-substrate-builders-program-1e3ba4f29ff3)

As the list of current tasks performed is extensive, we have divided it into several sections:


I. The Apillon platform development

[I. The Apillon platform development](#414a)

II. Apillon’s community building, initiatives, events

[II. Apillon’s community building, initiatives, events](#239b)

III. Apillon’s Treasury proposal

[III. Apillon’s Treasury proposal](#375c)

#### I. The Apillon platform development


First and foremost, parachain integrations are the most crucial part of the Apillon platform. Combined together or separately standing, they provide a range of fully-fledged services we want to offer to Web3 developers.


The first integration of Phala Network resulted in a working demo of so-called Schrödinger’s NFT. The product leverages the ERC-721 Smart contract, deployed on Moonbeam Network, a Phat contract, custom-written by the Apillon dev team within Phala Network’s Closed Beta Program and the IPFS pinning service through Crust Network. The goal is to achieve private NFT data, accessible only via dedicated NFTs as a key.

[a working demo of so-called Schrödinger’s NFT](https://phala-demo.apillon.io/)
[Phala Network’s Closed Beta Program](https://medium.com/phala-network/phat-contract-closed-beta-opens-applications-4d434c7a8e5a)
[Crust Network](https://crust.network/)
[Phala DemoPhala Demo Applicationphala-demo.apillon.io](https://phala-demo.apillon.io/)

This feature allows users to upload specific files and encrypt them using Phala TEE with an NFT in their wallet. Once encrypted, the file is saved on IPFS. Upon request, the file is then pulled from IPFS and decrypted using the same NFT that was used to encrypt it. For this solution, a custom Phat Contract was written in ink! programming language.


The service by KILT Protocol was integrated into the dashboard and can be used to log in to the app. Currently, the service is not yet live in production but it’s fully operational in the development environment.


As we have been developing the full Web3 Authentication service that enables users to pass the email attestation and receive their DID credentials from the platform, the question of a general DID storage immediately surfaced. The only supported tool that is currently able to hold the DID credentials is Sporran Wallet, which could represent a huge friction in the adoption if offered as the only solution we can provide to developers on Apillon.


That’s why, months ago, we started designing and developing a separate solution called DID Vault that would simplify the storage of the DIDs, eliminating the Sporran Wallet from the equation and offering users faster and simpler authentication processes without having them handle another wallet on their Web3 development journey.


To evaluate the platform’s security and check for vulnerabilities that could be exploited in case of attacks, penetration tests were done on the Apillon platform. Presented by the report of suggested improvements, the development team has already revised, implemented and released the upgrades to all environments and we’ve received the final confirmation and the overall rating.


Apillon is currently running a Freemium business model, allowing users to use up to 5 GB of Web3 Storage service, take up to 5 GB of Web3 Hosting service and deploy 2 NFT collections through the NFT Service, all completely free of charge. In parallel, we have been developing an additional business model, allowing us to check the overall limits as well as assign extra limits to users that have specific needs. With that in place, we are ready to proceed with designing the paid models in the next few months.


By continuously working on SDK and CLI, Apillon will soon be able to provide additional tools to speed up the development process on the Apillon platform. Both SDK and CLI tools already support Apillon’s Web3 Hosting service, while other services will soon be equipped too. Currently, the NFT Service and its SDK and CLI tools are being internally reviewed and will soon be up and running.


By joining forces with Astar Network, the Apillon platform now offers multiple chains for deploying digital assets. Following the integration of Moonbeam’s ERC-721 smart contract connectivity on the platform in early May, Astar’s EVM connectivity is the next step toward unlocking true interoperability across multiple chains, all through the Apillon platform.

[Apillon integrates Astar to deliver multi-chain smart contract connectivityBuilding future-proof projects that support free flow of digital assets between Polkadot, Ethereum, Cosmos, and other…blog.apillon.io](https://blog.apillon.io/apillon-partners-with-astar-to-deliver-multi-chain-smart-contract-connectivity-63d1d5f1e288)

When NFTs are deployed through the Apillon platform, users should be able to display them on a website. When the Apillon NFT Service was released, the initial NFT template for the website was on JavaScript. Now, to streamline the process even further by offering more ways to arrive at the finish line fast and easily, there are React and Vue NFT templates ready to be used.

[React and Vue join JavaScript in Apillon’s NFT website template libraryYou can now use NFT website templates in two more languages and customize them to showcase Apillon-minted NFTs.blog.apillon.io](https://blog.apillon.io/react-and-vue-join-javascript-in-apillons-nft-website-template-library-939005ac8770)

#### II. Apillon’s initiatives, events and community building


Web3 adoption cannot happen without joint efforts and collaborations among the teams within the Polkadot ecosystem. It’s crucial we spend time promoting the benefits of blockchain technology — by strengthening the existing Web3 community of believers and also by expanding our discourse outside of the Web3 realm.


Web3Approved represents a joint initiative by Apillon and Crust Network aimed to promote the decentralization of operations within the Web3 ecosystem. To jumpstart the movement, the initiative offers IPFS hosting services for projects to host their websites — completely free of charge. The first 100 projects that join will be provided with free decentralized hosting for their websites for the next 100 years.

[The Web3Approved initiative offers free decentralized hosting for 100 yearsThe initiative is a joint effort of Apillon and Crust Network, inviting Web3 players to practice what they preach.blog.apillon.io](https://blog.apillon.io/the-web3approved-initiative-offers-free-decentralized-hosting-for-100-years-c350a06f33b8)
[Login to Meetup | MeetupNot a Meetup member yet? Log in and find groups that host online or in person events and meet people in your local…www.meetup.com](https://www.meetup.com/subwork/events/292274713)

3. Blocksplit 4 — Split, Croatia

[5 things about Polkadot that were discussed at BlockSplitApillon’s back from BlockSplit where we presented easy Web3 building with the Apillon platform to blockchain…blog.apillon.io](https://blog.apillon.io/5-things-you-should-remember-about-polkadot-after-blocksplit-7d7a38f1b839)

4. Polkadot Day at ETH Belgrade — Belgrade, Serbia


5. Polkadot Prague

[HomePolkadotPrague is a trailblazing event that embraces the transformative potential of the Polkadot ecosystem.dotprague.xyz](https://dotprague.xyz/)

6. Polkadot Decoded: Parachain Summit, presentation on the Ecosystem stage and Showcase Station — Copenhagen, Denmark

[Apillon at Polkadot Decoded 2023Two days of Web3 community networking, exploring the ecosystem field and showcasing recent success and future plans —…blog.apillon.io](https://blog.apillon.io/apillon-at-polkadot-decoded-2023-bf7551452e6e)
[AAG 🥚 #47 - REPLAY! - Polkadot - Sway w/ NAY 💥Special Presentation at 5:29!Action starts at 16:20!Today's AAGenda!👉…t.co](https://t.co/CaBsPzn1Ar)
[AAG 🥚 #42 - REPLAY! - The Great DOT Rush of '23 ⛏️Action starts at 5:32!Today's Full AAGenda!👉…www.youtube.com](https://www.youtube.com/live/BIsaNokzJX0?feature=share)

2. Polkadotters (Twitter spaces):


3. Polkadot Community Call, June 2023 (Twitter Spaces)


3. Phat Contract in Use (Twitter Spaces)


4. Sora Daily (Twitter Spaces)


The franchise of Polkadot Meetup Ljubljana events is becoming one of the leading Web3 events in the wider region; each edition provides a dedicated topic to discuss with the panelists.

[Login to Meetup | MeetupNot a Meetup member yet? Log in and find groups that host online or in person events and meet people in your local…www.meetup.com](https://www.meetup.com/polkadot-ljubljana/events/293857442/)

2. Polkadot Meetup Ljubljana, Slovenia — April 2023

[Top legal experts gather at Polkadot Meetup Ljubljana to talk the future of cryptoThe fourth edition hosts a roundtable with prominent Slovenian lawyers to explore different legal angles and the future…blog.apillon.io](https://blog.apillon.io/top-legal-experts-gather-at-polkadot-meetup-ljubljana-to-talk-the-future-of-crypto-86dc60022ff)

3. Polkadot Meetup Zagreb, Croatia — April 2023

[Apillon, Astar and Polkadot communities take over ZagrebApillon hosts the first Polkadot Meetup Zagreb and solidifies the foundation for accelerating the Web3 movement in the…blog.apillon.io](https://blog.apillon.io/the-polkadot-community-takes-over-zagreb-27fc0a5e14d)

#### III. Apillon Bounty Proposal: Fostering Web3 adoption as a common good infrastructure solution on Polkadot


As of July 18, 2023, the Apillon Proposal is live on Polkassembly, ready to be voted upon.

[Polkassembly](https://polkadot.polkassembly.io/referenda/81)

Since June 19, 2023, we initiated the discussion by posting the Apillon proposal on both Polkassembly and Polkadot Forum. The aim of the proposal is to transform our Web3 development platform into an open-source common-good solution to provide Forever freemium access to developers building on Polkadot.


In accordance with the ecosystem’s meaningful feedback, we then decided to change some structural schemes and empower the community to have more say in the tranches being paid for Apillon’s work instead of asking for an upfront payment.


If Web3 is all about the community and democracy, it’s important how we go about making the ecosystem better. Here’s how we engaged and listened to the Polkadot ecosystem’s loudest preachers.

[How ecosystem engagement helped steer the way of the Apillon ProposalWe made a genuine effort to engage the Polkadot community in our proposal. We had open discussions, listened to the…blog.apillon.io](https://blog.apillon.io/how-ecosystem-engagement-helped-steer-the-way-of-the-apillon-proposal-93af9f568fdb)

And here you can check through the changes we’ve made to the Proposal.

[Apillon Proposal changing course: From Treasury to BountyThe Polkadot community raised a few legitimate concerns regarding the Proposal; hence some structural changes were made…blog.apillon.io](https://blog.apillon.io/apillon-proposal-changing-course-from-treasury-to-bounty-7ff6e2c69800)
[Bounty to back Apillon Web3 development platform as a common good infrastructureBounty to back Apillon Web3 development platform as an open-source, common good infrastructure Requested DOT: 999,999…polkadot.polkassembly.io](https://polkadot.polkassembly.io/referenda/80)
[Apillon Web3 development platform as a common good infrastructure - Polkadot Treasury ProposalThis post is an informal notice as we want the Proposal to reach the complete volume of the Polkadot and Web3…forum.polkadot.network](https://forum.polkadot.network/t/apillon-web3-development-platform-as-a-common-good-infrastructure-polkadot-treasury-proposal/3145)

We have presented the proposal to numerous audiences, including Parity (Ecosystem 101 call), Substrate Builders Program (SBP Office Hours presentation), the Polkadot Community Call, and through multiple AMAs with different ecosystem teams on Twitter. We are thrilled with all the support we have received so far.


Below you can find the proposal and proposal-adjacent links:

[The full Apillon Bounty Proposal](https://ipfs.apillon.io/ipfs/QmZmZLdpeuVN9vpw3WNzJh8F62vzqwZDmrXdh5mBRB1GVh)
[The Apillon Platform Quick Demo](https://www.youtube.com/watch?v=qQJnuvUo-xo)
[The official Apillon Proposal announcement](https://blog.apillon.io/apillon-aims-to-foster-web3-adoption-as-a-common-good-infrastructure-solution-on-polkadot-6566508190c5)
[The AAG on Polkadot and Kusama — Treasury and Proposal funding](https://t.co/CaBsPzn1Ar)

The Apillon team will gladly answer any questions directed our way regarding the Treasury Proposal or any other activity listed above in connection to Substrate Builders Program.


Make sure you follow Apillon’s social media to stay up to date with the latest news and important updates. And, of course, join in on the platform and build your first Web3 project in case you haven’t done that yet. It’s easy peasy, remember?


### ⧓ About Apillon


The Apillon platform serves as a unified gateway to the Web3 services provided by linked Polkadot parachains. Following the multi-chain vision, Apillon powers the transition of developers to Web3, simplifying its adoption in the real economy, and expanding its versatility as the ecosystem grows. With Apillon, Web3 services are within reach for every developer, regardless of their background and experience with blockchain technology.


Website | GitHub | Twitter | Telegram | LinkedIn | Reddit

[Website](https://apillon.io/)
[GitHub](https://github.com/Apillon-web3)
[Twitter](https://twitter.com/apillon)
[Telegram](https://t.me/Apillon)
[LinkedIn](https://www.linkedin.com/company/apillon/)
[Reddit](https://www.reddit.com/r/apillon/)