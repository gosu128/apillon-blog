+++
title = "Guide: Log in to Apillon dashboard using KILT decentralized identity"
date = "2023-09-01T09:03:09+0000"
description = "Now, you can enter the Apillon platform by simply connecting with Sporran wallet or using your digital credentials."
draft = false
+++

### Guide: Log in to Apillon dashboard using KILT decentralized identity


#### Now, you can enter the Apillon platform by simply connecting with Sporran wallet or using your digital credentials.

[KILT-powered log-in](#7136)
[Flow 1: Use your existing digital identity by KILT](#455b)
[Flow 2: Create a KILT-powered digital identity first](#731a)

### KILT-powered log-in


Data privacy and supreme user experience are equally important features of the Apillon platform as the Web3 services it provides.


In the recent update, Apillon has added a new, self-sovereign log-in method powered by the KILT Protocol, a Polkadot-based parachain specialized in decentralized digital identity, serving user-owned identifiers, credentials, web3names, and identity-storing digital wallet.

[KILT Protocol](https://www.kilt.io/)

Here is how to log in to Apillon using KILT identity, step by step.


On the Apillon dashboard’s log-in page, click “Log in with KILT”.

[log-in page](https://app.apillon.io/login)

Next, follow:

[Flow 1](#455b)
[Flow 2](#731a)

### Flow 1: Use your existing digital identity by KILT


This flow assumes you have already downloaded a Sporran wallet browser extension and set up a digital identity with a unique DID. You should also link an email credential to it and attest it using Social KYC, and have your mnemonic phrase at hand.

[Sporran wallet browser extension](https://www.sporran.org/)
[unique DID](https://kilt-protocol.org/get-did/index.html)
[Social KYC](https://socialkyc.io/)
[CType](https://github.com/KILTprotocol/ctype-index/blob/main/ctypes/0x3291bb126e33b4862d421bfaa1d2f272e6cdfc4f96658988fbcffea8914bd9ac/README.md)
[KILT’s CType data](https://docs.kilt.io/docs/concepts/credentials/ctypes/)

Now, let’s begin.


When you click the “Log in with KILT” button, a pop-up window appears. Select the way you’d like to proceed, using either:

[Credentials](#43ac)
[Identity upload](#0bca)
[Sporran wallet](#8663)

Here is how to log in with each one of them.


#### 1 Credentials


This type of KILT log-in reads your digital identity credentials in a text format.


Under the Credentials tab, paste your verification credentials. To get credentials, open your Sporran wallet extension, choose the identity you want to use, and click “Show credentials”. Next to the email credential, click the download icon, and save it to your local disk.


Next, open the saved file in a text editor of your choice and copy-paste its contents into the Verification credentials field on the Apillon log-in page.


Input your KILT mnemonic phrase, too, and click “Log in”.


#### 2 Identity upload


Similarly to the Credentials copy-paste method, you can upload your credential’s JSON file directly.


Go to Sporran wallet, and — if you have multiple — select the identity you want to go with. Click “Show Credentials”.


Click the download icon on the right and save it as a JSON file on your local disk.


On the Apillon log-in pop-up window, under the Identity upload tab, click “Upload identity”. In your file explorer, select the email digital credential in JSON format.


Enter your KILT mnemonic phrase, too, and click “Log in”.


#### 3 Sporran wallet


To bypass copy-pasting or file upload, log-in directly with KILT’s own Sporran wallet.


Under the third tab, click Sporran wallet and then the “Log in” button.


Next, authorize the Sporran wallet extension to access the Apillon application.


Select the email credential to log in with, and click “Next”. Authorize access by signing with your Sporran password.


That’s it! You’ve successfully logged into the Apillon dashboard using your self-sovereign digital identity by KILT.


### Flow 2: Create a KILT-powered digital identity first


If you have yet to set up your digital identity with KILT, click “Create” at the bottom of the Log in with KILT pop-up window.


Enter your email address and confirm you’re a human by solving an hCaptcha. Click “Send email” and check your inbox.


In the email you receive from Apillon, click the button to confirm your registration.


Now, a window opens with a mnemonic phrase linked to your account registration.


Click the copy icon and, paste the phrase into a Notepad or other text editor, and store it safely. Click “Confirm and continue”. You will need it in case you have to restore your identity.


Next, to verify the mnemonic phrase, input the first, third, and eighth word, and click “Confirm”.


This is where the magic starts to happen. Apillon is now generating a KILT-powered decentralized identity that you will use to log into your Apillon account and will stay permanently in your control.


The process could take a few minutes, so please be patient and don’t close the window until you get a response.


In the back-end, Apillon not only connects to KILT to create your own DID and credential but also works as its attester.


Copy and paste both DID and Credentials in a text editor file, such as Notepad. Or, simply download both (don’t forget to allow download of multiple files) and save them to your local disk.


Hurray, you are now a proud owner of a decentralized digital identity powered by KILT Protocol. Once you have saved your DID and credentials, you’re all set to log into Apillon.

[install Sporran wallet](https://www.sporran.org/)

You can now close the identity generation window and use your KILT-powered decentralized digital identity to log into Apillon.

[log into Apillon](https://app.apillon.io/login)

Follow the steps from Flow 1, and you’re done!

[Flow 1](#455b)

Let us know how it went and spread the word about the self-sovereign digital identity experience on Apillon. See you on the other side!
