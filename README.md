

# hashratecoin

![HashrateCoin Logo](/hashratecoin_logo_220x221.png)

Hashrate Coin is a digital currency for buying and selling computing power and hashrate. It is a cryptonote based coin using the Cryptonight algorithm with several improvements over period of time.

## Coin Specifications
* Ticker: HRCN
* Max Supply: 1,000,000,000
* Emission Factor: 18
* Block Timing: 120 Seconds (2 min)

A standalone GUI wallet is coing soon

## Run Node
> Install required packages

sudo apt-get update

sudo apt-get install libboost-all-dev

sudo apt-get install build-essential cmake pkg-config libssl-dev libunbound-dev libminiupnpc-dev libunwind8-dev liblzma-dev libldns-dev libexpat1-dev libgtest-dev doxygen graphviz

> Get the code from git repository and build

git clone https://github.com/hashratecoin/hashratecoin.git node

cd node

> Get the rocks lib from the hashratecoin wesbite or build yourself

copy librocksdb.a from http://hashratecoin.org/downloads/librocksdb.a or 
https://drive.google.com/file/d/1ocCU8u52tDzP02n0C87Y67Dh5p7_ipa1/view?usp=drive_web

to \external\rocksdb folder before running make

make

> Run the node using the following command.

./hashratecoind

## Run Simple Wallet
Run the simplewallet using the following command: 

./simplewallet 

The Wallet will have prefix XRxN.
