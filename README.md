# interfaces

This repo will focus on building a content management system with a dapp deployer and dapp user interface content type. the goal is to allow anyone to come browse the working UI of any dapp without needing to mess with the blockchain, rpc, nor web server administration beforehand reducing the technical threshold required to brose dapps.


The basic plan is to get this working fully with Django before building similar Wordpress and Drupal CMS modules.

The user will require theMetaMask Chrome extension or Mist browser. Plans to fork Metamask to access a token repository in the plans.

Use Case: Person wants to use The DAO but does not want to run a full node for Mist or does not have the technical capacity. They come to our website, search the DAO and viola! they can use the interface along with their MetaMask wallet.

Use Case: A Person wants people to use their dapp easily, they would host is on our website.

Use Case: A dapp has a security flaw or other potential issue it will/should be flagged, access restricted and investigated.

Use Case: A dapp interface which has multiple views based on permissions should display properly.

Use Case: A dapps address, base data, and ABI can be copied from our site rather than going to Github as well.

Project Success Definition: first app is the in browser compiler which will utilize truffle build process involving migrations to add contract metadata and autobuild the /0x123/contract/[code, abi, data] and /0x123/ui/default page with the given ABI etc.
