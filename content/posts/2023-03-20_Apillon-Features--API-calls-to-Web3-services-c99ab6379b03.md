+++
title = "Apillon Features: API calls to Web3 services"
date = "2023-03-20T13:42:23+0000"
description = "Apillon API delivers a straightforward connectivity to Polkadot parachains while respecting the standard development workflow."
draft = false
+++

### Apillon Features: API calls to Web3 services


#### Apillon API delivers a straightforward connectivity to Polkadot parachains while respecting the standard development workflow.

[Drawbacks of standard access to Web3](#0378)
[Apillon Web3 APIs](#9547)
[Web3 Storage API](#05ca)
[Web3 Hosting API](#b03e)

One of the main hinderers of Web3 adoption is the development process. Apillon API shortens the way Web3 products are built by saving developers the trouble of diving into each parachain’s specifics, logic, and requirements.


### Drawbacks of standard access to Web3


If you decide to code a Web3 project or implement a decentralized service provider to your existing website or app from scratch, you face a steep learning curve and a potentially high risk of things going south.


Wrestling with Web3 bare-handed could be extremely heavy on resources while still not guaranteeing any wins. There are plenty of uncertainties along the way, and every developer, even the Web3 veterans, could easily overlook important steps, ultimately leading to deep frustration and even abandonment of the Web3 mission altogether.

[How Apillon changes the way Web3 products are builtApillon brings the development of Web3 products and apps down to just a couple of steps and a few lines of code.blog.apillon.io](https://blog.apillon.io/how-apillon-changes-the-way-web3-products-are-built-ee0adae9b94a)

To simplify the development process and bring it to terms every developer should be familiar with, Apillon introduces API connectivity to linked Polkadot parachains and their Web3 services.


### Apillon Web3 APIs


Apillon integrates multiple Polkadot parachains and offers straightforward access to linked decentralized services in two ways:

[Polkadot](https://polkadot.network/)
[Web3 services](https://blog.apillon.io/apillon-platform-up-close-web3-services-f77530dd274e)

In this post, we will dive into the latter, where Apillon APIs enhance and streamline the coding process of Web3 projects.


#### What is Apillon API?


Apillon API is a set of RESTful API endpoints that allow you to integrate Apillon Web3 services modules into your Web3 project.


Using Apillon APIs, you make a call to a server and receive the response over the HTTP protocol.


To ensure the privacy and safety of Web3 project development, all routes are private and require you to use an API key.


Now, let’s see how to use Apillon APIs when coding your Web3 project.


#### Apillon API specifics


RequestsThe server speaks JSON, and for that reason, every call to the server should include a Content-Type header set to application/json;.

[JSON](https://en.wikipedia.org/wiki/JSON)

Authentication and authorizationApillon API routes ensure privacy by restricting public access and requiring authentication.


When creating requests, you should therefore include a basic auth HTTP header field in the form of Authorization: Basic <credentials>, where credentials represent the Base64 encoding of API key and API key secret joined by a single colon :.

[basic auth](https://en.wikipedia.org/wiki/Basic_access_authentication)

You can generate API keys on the Apillon dashboard under Project settings.

[Apillon dashboard](https://app.apillon.io/dashboard/api-keys)

Once generated, you can use the API key in your project.


ResponsesEvery response has a unique ID to help you identify potential issues in the API connectivity or accessed services. It also includes a status code so you can quickly identify the cause of a potential problem.


Query requests through GET method can return status codes 200, 400, 401, 403, or 500, indicating success, bad request, unauthenticated or unauthorized access, or system error.


Mutations through POST, PUT and DELETE can further return codes 201 and 422, namely successful creation or failed data validation. And, invalid routes return status code 404, indicating path not found.


A successful request includes a data key, which holds a valid response object.

[Apillon Web3 API](https://wiki.apillon.io/build/3-apillon-api.html)
[Apillon Wiki](https://wiki.apillon.io/build/3-apillon-api.html#api-to-web3)

Now with theory out of the way, let’s dive into the contents of APIs connecting to the two Web3 services accessible in the Apillon Beta:

[Web3 Storage API](#05ca)
[Web3 Hosting API](#b03e)
[stay tuned](https://twitter.com/apillon)

### Web3 Storage API


Apillon Web3 Storage API connects to the Crust Network, allowing you to store your files in a decentralized way.

[Crust Network](https://www.crust.network/)

Before you start using the Web3 Storage API, there are two things to keep in mind:

[storage bucket](https://wiki.apillon.io/build/2-web3-services.html#storage-bucket)
[Apillon dashboard](https://app.apillon.io/login)

#### File upload process via Apillon Web3 Storage API


The files you store on the Crust Network are uploaded as follows:


Now, let’s do it step by step using Apillon API.


#### How to use Apillon Web3 Storage API


1. Upload to storage bucketFirst, create file upload requests that return URLs for file upload along with sessionUuid.


🔻 cURL


🔻 Response


2. End upload sessionOnce files are uploaded to the cloud server via the received URL, trigger file sync to IPFS and Crust.


🔻 cURL


🔻 Response


3. Get bucket contentNext, get directories and files in the storage bucket. Note that items are paginated and can be filtered and ordered through query parameters.


🔻 cURL basic


🔻 cURL with params


🔻 Response


4. Get file detailsLastly, get details of a specific file inside a storage bucket.


🔻 cURL


🔻 Response


That’s it, your files should now be stored on Crust Network.


5. Delete fileTo delete a file, you can mark it for deletion inside a storage bucket using id, fileUuid, or CID. The file will be completely deleted from the Apillon system and Apillon IPFS node after three months. Once a file is marked for deletion, it will not be renewed on Crust Network.


🔻 cURL


🔻 Response


Voila, you’ve made it through the whole process of uploading files to decentralized storage via Crust Network and Apillon API.

[Web3 Storage API](https://wiki.apillon.io/build/3-apillon-api.html#web3-storage-api)
[Apillon Wiki](https://wiki.apillon.io/build/3-apillon-api.html#web3-storage-api)

### Web3 Hosting API


Apillon Web3 Hosting API connects to the Crust Network, where you can host your website in a decentralized way.

[Crust Network](https://www.crust.network/)

Before you start using the Web3 Hosting API, there are two things to keep in mind:

[Apillon dashboard](https://app.apillon.io/dashboard/service/hosting)

#### Website deployment process via Apillon Web3 Hosting API


Apillon Hosting API provides endpoints that can be used to implement CI/CD.

[CI/CD](https://en.wikipedia.org/wiki/CI/CD)

The website you host on the Crust Network is deployed as follows:


Now, let’s do it step by step using Apillon API.


#### How to use Apillon Web3 Hosting API


1. Get URLs for files uploadFirst, create file upload requests that return URLs for file upload.


🔻 cURL


🔻 Response


2. End upload sessionNow, transfer files to the website storage bucket, which is used as a source for deployment to a staging (preview) environment.


🔻 cURL


🔻 Response


3. Deploy websiteNext, utilize endpoint to trigger website deployment into specific a environment.


🔻 cURL


🔻 Response


4. Get deploymentNow, trigger endpoint to initiate deployment.


🔻 cURL


🔻 Response


5. Get websiteFinally, get your website by triggering the endpoint to return basic website data, along with IPNS links.


🔻 cURL


🔻 Response


That’s it, in just a few steps, you have upgraded your website’s hosting to a decentralized level.

[Web3 Hosting API](https://wiki.apillon.io/build/3-apillon-api.html#web3-hosting-api)
[Apillon Wiki](https://wiki.apillon.io/build/3-apillon-api.html#web3-hosting-api)

### Web3 access the APIllon way


Apillon API provides straightforward connectivity to Polkadot parachain services while respecting the standard development workflow.


By accessing Web3 services via APIs, you can launch your Web3 project faster and with hardly anything to break since you control all the code.


Let us know how you find Apillon APIs and build away!

[Let us know](https://discord.gg/yX3gTw36C4)

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