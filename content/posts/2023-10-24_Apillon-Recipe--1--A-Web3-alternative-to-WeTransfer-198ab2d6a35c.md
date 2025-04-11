+++
title = "Apillon Recipe #1: A Web3 alternative to WeTransfer"
date = "2023-10-24T11:56:33+0000"
description = "The first episode of cooking Web3 with Apillon shows you how to store and share files on a decentralized network privately."
draft = false
+++

### Apillon Recipe #1: A Web3 alternative to WeTransfer


#### The first episode of cooking Web3 with Apillon shows you how to store and share files on a decentralized network privately and without the risk of third-party impact.

[Why a Web3 alternative to WeTransfer?](#c587)
[Storing files on IPFS via Crust](#6474)
[Step 1: Create a storage bucket](#8542)
[Step 2: Upload any file](#b480)
[Step 3: Share the link](#1698)
[Step 4: Make it editable](#4e0f)

### Why a Web3 alternative to WeTransfer?


First, to avoid any misunderstanding — WeTransfer is a fantastic tool, and we’re all used to using it, so this post does not mean to degrade it in any shape or form.

[WeTransfer](https://wetransfer.com/)

But we’re also all for applying the Web3 approach where it seems appropriate. And private file sharing could definitely use some upgrades in terms of accessibility and security risk.


So, here’s why a Web3 alternative to WeTransfer (or other similar Web2 platforms):


### Storing files on IPFS via Crust


The Apillon platform allows you to store files of any kind on a decentralized network and share them via a simple link — leading not to the platform where contents still require download to be viewed but directly to the file(s) in question.


Apillon’s Web3 Storage service implements the technology of Crust Network, a Polkadot parachain that pins files to IPFS nodes around the globe.


And it’s all doable without having to know the first thing about coding or Web3, simply by dragging and dropping, copying and pasting.

[FAQ: Apillon Web3 StorageFind answers to your questions on the Apillon Web3 Storage service, how to store files on a decentralized network, and…blog.apillon.io](https://blog.apillon.io/faq-apillon-web3-storage-c99a9b0e8b12)
[Apillon Web3 services | Apillon WikiApillon Wikiwiki.apillon.io](https://wiki.apillon.io/build/2-web3-services.html#web3-storage)

Ok. Let’s dive right in.


### Step 1: Create a storage bucket


Register or log in to the Apillon dashboard. In the menu on the left, navigate to Storage and create a new storage bucket by clicking on the yellow button.

[Apillon dashboard](https://app.apillon.io/login)
[Storage bucket](https://wiki.apillon.io/build/2-web3-services.html#storage-bucket)

In the pop-up, enter your bucket name to easily distinguish it from other-purpose decentralized storage buckets. Add a description, too, and click “Create bucket & continue to management”.


### Step 2: Upload any file


Now, it’s time to bring your files to the platform and pin them on IPFS via Crust Network.


You can upload the files:

[One by one](#6dbc)
[In bulk, within a designated folder/directory](#ce53)

#### 2.1 Upload one by one


On the dashboard, click “Upload files and folders”, and in the local drive, select the files you wish to upload and share via a decentralized network.


Review the chosen selection and, if all is good, click “Upload now”. If you wish to remove any file, simply click the X icon.


Shortly after, you should see them successfully uploaded and listed in your storage bucket.


At this point, the files are being pinned on IPFS via Crust and replicated on dozens of nodes around the globe, which could take a minute or two.


Once the pinning is done, each file gets its own CID (content identifier) and a link leading to its IPFS-pinned version.


Instead of uploading files individually, you could also move multiple at once into a designated folder. 👇


#### 2.2 Upload files in bulk


To upload multiple files in one go, click “Upload files and folders” and choose the files you wish to upload from your local disk.


Now, in the uploaded files list, click “Wrap in directory” and then “Upload now”. This will upload files in a separate folder for you to share the containing files in bulk.


Next, in the pop-up window, enter the folder name and click “Upload”.


Soon after, the directory should appear on the list of uploaded items. Once all containing files are uploaded and get their own IPFS link, the directory itself also gets pinned on IPFS via Crust — its CID and Download link are listed next to the folder name.


### Step 3: Share the link


Now, the Download link that points to your file or folder on IPFS is what matters — double-check its contents before you share it.


If you click on it or copy and paste it into a new browser tab, you get either:


Some browsers, like Web3-powered Brave, offer you a way to redirect to IPFS either manually by clicking on the icon in the right corner of the URL field, or automatically if enabled in your Brave browser settings.


Notice how the URL changes from the apillon.io domain to the IPFS-pinned link as you’re redirected to the IPFS network.


The file’s status of being pinned to IPFS (plus other details) can also be observed in Brave if you click on the IPFS icon in the left corner.


The same goes for folders/directories pinned on IPFS.


Click your directory’s Download link on the Apillon dashboard to open an index of files stored under it in a new browser tab.


If you click the IPFS icon in the right corner of the URL field, you’re redirected from the apillon.io-originated URL to the IPFS-based URL — notice how they change.


The listed items link to their respective IPFS-pinned files. This is also visible when you click the IPFS icon in the left corner. Click on a listed file to open it in your browser.


Notice how the IPFS-based URL of the file that was uploaded individually differs from the one linking to the file that was uploaded in bulk with others in a separate directory.


Now, if your link points to the right content, feel free to share it with your friends, family or colleagues. Your file(s) will be accessible in a direct way, bypassing third-party cloud storage platforms.


### Step 4: Make it editable


If the files you upload and share need to remain editable, for example, spreadsheets or documents, publish them to IPNS, as well.


Under three dots next to a file or folder, click Publish to IPNS.


In the first pop-up window, click “Create new IPNS”, and in another one, enter the name and description of your new IPNS record. Lastly, choose the newly created IPNS record on the drop-down list and click “Publish to IPNS”.


When uploading to IPNS is done, you can find it under the IPNS tab.


Clicking on the IPNS link takes you to the editable register under the IPFS-based URL.


With IPNS, your file or folder acquires a mutable pointer to its CID (content identifier). This link can be updated while still pointing to the same content or file under it.

[IPNS (InterPlanetary Name System) | IPFS DocsLearn about mutability in IPFS, InterPlanetary Name System (IPNS), and how it can be used in conjunction with IPFS.docs.ipfs.tech](https://docs.ipfs.tech/concepts/ipns/)

This is how you can store and share your files in a truly decentralized fashion without relying on third-party cloud storage platforms. Or, if you feel like taking it a step further, you could integrate the same flow into your custom-built UI and create a proper Web3 file sharing platform for others to use, too.


The process should take you no more than a few minutes, so start today and contribute to the adoption of Web3 storage using photos of your cat or doodles you created during the last video meeting.
