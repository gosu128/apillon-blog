+++
title = "Web3 Adoption: RPC/smoldot"
date = "2025-04-01T13:44:27"
description = "RPC stands for Remote Procedure Call, which is a protocol that allows a program to request a service from a program located on a remote…"
draft = false
+++

### Web3 Adoption: RPC/smoldot


RPC stands for Remote Procedure Call, which is a protocol that allows a program to request a service from a program located on a remote computer or network, without having to understand the underlying network details. It enables distributed computing by allowing applications to communicate with each other across different machines and operating systems.


Smoldot is a framework that aims to improve RPC by providing a more efficient and scalable solution. It achieves this by introducing several key features:


1. Asynchronous communication: Smoldot allows multiple requests to be sent simultaneously, and responses are processed as soon as they become available. This minimizes the time spent waiting for responses and maximizes the utilization of network resources.


2. Connection pooling: Smoldot maintains a pool of connections to remote services, which can be reused for multiple requests. This eliminates the overhead of establishing and tearing down connections for each request.


3. Load balancing: Smoldot can distribute requests across multiple instances of a service, ensuring that the workload is evenly distributed and reducing the likelihood of overload on any single instance.


4. Automatic retries: Smoldot can automatically retry failed requests, which can be especially useful in high-traffic or unreliable network environments.


Overall, Smoldot aims to make RPC more efficient, reliable, and scalable, which can be particularly important in large-scale distributed systems.


ce ces na bc sprozit tx, rabis access to nodov, so fully sinchronizirani s chainom


ko dosezejo consensus za novi block, ga vsi zapisejo


js kot dev rabim access do nodov, da sprozi tx, moram interaktiras s chainom


2 poti:


problem je da je centrl, lahko se zrusi, (recmo alchemy), lahko neha delat


polkadot je zato zacel razvijal smoldol, ultralight node client, ko hoces naredit tx iz a v b, tebi se browser page se vanj zloada javascript, smoldot ti pa v ozadju in real-time se posinka s chainom, tam zazivi en mini virtualen node, prek katerga se nardi ta ukaz, ko se to nardi, se ubije lokalni node


alchemy, infura zivijo fully od eth, noben od njih ni bil velk na polkadotu


traja 2–3 min da se case posinka, prevec


gavin pravi, da se isto hitro al hitreje od rpcjev posinka


ko bojo userji vstopal v web3, bojo dobil lih dovolj hitro posinkan nodes, sinhroniziran na tak nacin, da ves da je legit zadeva


problem je bil na front-endu, kot uporabnik, ko si odpru metamask (uporablja infuro, ko ta pade, ni mogu mm nic), na smoldotu se to ne more nardit


devi bojo najbrz se vedno uporabljal infrastrukturo kot je infura, alchemy, ker rabis za 10k tx, smoldot tega neb mogu spelat


banka nlb, nastala v 90h, imajo zgodovino vseh tx, ta file je velik 500gb, en racunalnik ki si posinka vse te info je node, jaz kot dev interaktiram s tem nodom, nanj dodajam nove info


rpc je placljiv, node sam po sebi je zastonj, jes kot dev si ga lah nastavim in laufam, je treba povezat z drugimi nodi, treba updatat, ce se gres resno delat, rabis enga cloveka fully zaposlenega, da se sam s tem ukvarja


ce das 100–200e/mesec je se zmer cenej kot met cloveka


nas radi primerjajo z alchemy in infuro, ampak mi delamo cisto neki drugega, nivo visje, na alchemy ne mores poslat ene slikice da jo shrani na dec nacin, ne mores delat hostinga lala, mi delamo service on top, ceprov se vsi imenujemo dev platform


alchemy/moralis, ki so zaceli kot node providerji, vedno bolj grejo k service/function providanju, ce se ze s kom primerjamo, opcijsko z moralis, ne pa alchemy


https://github.com/paritytech/smoldot

[https://github.com/paritytech/smoldot](https://github.com/paritytech/smoldot)
[GitHub - paritytech/smoldot: Alternative client for Substrate-based chains.Alternative client for Substrate-based chains. Contribute to paritytech/smoldot development by creating an account on…github.com](https://github.com/paritytech/smoldot)

https://twitter.com/gavofyork/status/1636750323682508800

[https://twitter.com/gavofyork/status/1636750323682508800](https://twitter.com/gavofyork/status/1636750323682508800)
[Nino Kutnjak](https://medium.com/u/c6abef30524f)
[Polkadot’s smoldot not so small after allAs an avid advocate of all things decentralized, Polkadot developed a light client smoldot to stand up to all centrally…blog.apillon.io](https://blog.apillon.io/polkadots-smoldot-not-so-small-after-all-d7c349830a24)
[Substrate Connect in Polkadot Wiki](https://wiki.polkadot.network/docs/build-substrate)

https://github.com/paritytech/smoldot

[https://github.com/paritytech/smoldot](https://github.com/paritytech/smoldot)

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