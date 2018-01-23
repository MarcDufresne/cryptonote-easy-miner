M0rkcoin-Easy-Miner
===

This is a simple C# app that helps Windows users start mining without dealing with command-line operated binaries. It is bundled with the latest 64 bit builds of `cpuminer` and `simplewallet`.


First time you start the application you will be prompted to create a new wallet (if you already have one read below), you'll be able to enter a password and create the wallet. The main window will open and you can start mining. If the address field is empty you can restart the application to retry loading the address.

If you already have a wallet, you can simply edit the `.address` file and input your address there. The app will use this file to load your address for mining.

Upon starting you can then input a pool host & port, select how many CPU cores they want to use, the click `Start Mining`.

The app will spawn instances of `cpuminer` for each core with the approperiate command-line arguments.


### Download

Get the latest build here: [releases](//github.com/MarcDufresne/cryptonote-easy-miner/releases)
