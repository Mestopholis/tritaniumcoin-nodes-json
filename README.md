# tritaniumcoin-nodes-json
JSON List of public daemons for TritaniumCoin

The json file in this repo contains the a list of known public nodes in which users can connect to sync their wallets.
Some of these may contain fees.

This list can be consumed in your application so you'll always have an up-to-date list of public nodes. To consume the list, use the following URL: https://raw.githubusercontent.com/TritaniumCoin/tritaniumcoin-nodes-json/master/tritaniumcoin-nodes.json

Adding a New Node
If you would like to add your public node to the list, please submit a Pull Request to do so. To avoid any possibility of displaying preference for one public node over another, please ensure that any additions are submitted in alphabetical order by the name property.

If you are unfamiliar with github, please reach out to me on Discord to get your node added, @Mestopholis#4572 

# Creating your own public node

If you would like to create your own public node, here are the steps.

*What you’ll need:

1. A computer with an IP address that doesn’t change. If you’re running it from home and use cable or DSL internet, you’re probably already set up with a static IP. (Free Amazon servers or Google Cloud servers are perfect for this) 

2. A TritaniumCoin wallet to collect your earnings. You can use a paper wallet, triwallet or any other TTNZ wallet.  Make sure you have the keys to the wallet.

*Let’s Get Started

1. Connect to your node and install TritaniumCoin. 
You can follow the compile guide on https://github.com/TritaniumCoin/TritaniumCoin or download a Release from https://github.com/TritaniumCoin/TritaniumCoin/releases

2. Decide on a fee, and launch the daemon
Let’s say I want to charge .0005 TRTL per transaction sent, I can launch my daemon like this:
./TritaniumCoind --fee-amount 500 --fee-address Tri1KMKwrgphRAAvHKchfccYQKmB4a3cfLpYbMdRyHdhKGecD3Xr52FdHib2S1MTWL6VmPgfAXgV3MNXf3kpGPTu2pHZrxVaYC

Note that TritaniumCoin uses 6 decimal places to determine its' atomic units.  The decimal is not used by the Daemon.  It only understands units.  So a fee of .000100 equates to 100 atomic units.

*What Do We Do Next?

Get your node listed on Github so that people know you exist!

