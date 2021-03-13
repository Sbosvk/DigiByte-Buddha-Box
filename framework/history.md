# History

## The Name

The name DigiByte \('**Digi**tal **Byte'**\) denotes memory space like a gigabyte or megabyte.

This means that valuable data can be stored on it. The good news is that it is not susceptible to hack or destruction. Once data is stored on it, it cannot be manipulated except the right access is given it by the owner.

## Overview

DigiByte is the name for both an open source cryptocurrency and the decentralized global blockchain on which it operates. The DigiByte Blockchain was created in 2013 by [Jared Tate](https://www.dgbwiki.com/index.php?title=Original_author%28s%29), followed the first DigiByte block was mined on January 10, 2014, and included the headline from USA Today: “Target: Data stolen from up to 110M customers," hashed into the [Genesis Block](https://github.com/digibyte/digibyte/blob/master/src/chainparams.cpp#L52) to mark the importance of security in digital transactions. The goal of DigiByte at that time, was to create a large community for virtual currency users across the world to use seamlessly in real time transactions.

[Jared Tate](https://www.dgbwiki.com/index.php?title=Original_author%28s%29), a programmer and entrepreneur, created DigiByte the goal of creating a fast and secure cryptocurrency that could reach a wider and more decentralized community than Bitcoin.

In 2015, a number of shopkeepers in the Netherlands began using DigiByte as a payment to manufacturers in Hong Kong, which documented the first use of the cryptocurrency on such a large scale. This was a prime example of how a virtual currency could be used to simplify transactions for businesses across different countries, who would otherwise have to deal with the conversion of traditional currencies.

Like many cryptocurrencies, DigiByte intrigues many due to the fact that it isn’t controlled by any central power, such as agovernmentor bank. All money exchanged on the DigiByte Blockchain is cryptographically secured and requires a series of confirmations that ensure users know what they are giving or receiving. DigiByte also offers a number of new and intriguing concepts that make it unique in the virtual currency world.

Adjustments in the code allow for improved functionality, including 15-second block time, real-time difficulty adjustment and improved security.

It is also the first to blockchain to fork from a single proof-of-work algorithm to multi-algorithm mining.

DigiByte is also one the first blockchainsto successfully activate SegWit \(April 2017\), MultiAlgo mining \(September 2014\), DigiShield \(February 2014\) and Odocrypt \(July 2019\).

Since 2014, many other blockchains like Ethereum, Bitcoin Cash, Zcash & Dogecoin have adopted DigiByte technology such as DigiShield.

DigiByte is secured by 285,000 nodes world-wide distributed with 5 parallel cryptographic hashing algorithms \(PoW\) which secure the network and make it truly un-hackable.

You store & send data in megabytes & gigabytes, why not send money and secure data in DigiBytes?

## Launch

* Jared Tate has been involved with Bitcoin since 2012. In the Fall of 2013, he decided to make several improvements to the Bitcoin core protocol which culminated in the launch of DigiByte in 2014. 
* DigiByte was founded by Jared Tate with the goal of creating a fast and secure blockchain that could reach a wider and more decentralized community than Bitcoin. 
* 21 Billion total supply \(1:1000 ratio to BTC. With mass adoption, average people can still afford to buy an entire DigiByte.\) 
* 72000 DGB initial block reward \(1% reduction monthly\) 
* Count-down via [BitcoinTalk](https://bitcointalk.org/index.php?topic=408268.0) 
* 0.5% Pre-Mine \(DigiByte was one of the few coins launched around 2014 with a fair and reasonable pre-mine. There was 0.25% given away to the public to encourage early adoption and ensure the coin didn’t stall, along with 0.25% supporting development for the first 18 months, both of which is disclosed on the website. This funding supported the coin throughout that development period and the team was able to create DigiShield, along with forking to MultiAlgo and subsequently MultiShield all throughout, thanks to the careful governance of their available funds. All these transactions of DGB pre-mine are posted publicly, so you can review anything you would like. This was the purpose of the pre-mine, but built into a system to allow user reviewing. **0% premine remaining.**\)

## Hard Forks

### DigiShield

Block 67,200. February 28th, 2014

Activated in February 2014 this hard fork allowed for the DigiByte blockchain to protect against multi-pools that mine large numbers of DigiByte at a low difficulty. It achieves this by recalculating block difficulty between each block, allowing for a faster correction when a multi-pool begins or ceases contributing to DigiByte, rather than recalculating once every fortnight as is the case with Bitcoin. The DigiByte Core developers assisted the Dogecoin team to successfully implement DigiShield in early 2014 to help resolve the wild swings in chain difficulty. Since then DigiShield has been added into over 25 other cryptocurrency blockchains such as Bitcoin Cash, Dogecoin, Startcoin, Zcash, Aurora Coin, Bitcoin Gold, BitTokens, Creative Coin, Granite, Huncoin, Monacoin, Mooncoin, Nautiluscoin, Quatloo, Sakura Coin, Scorecoin, SmartCoin, StartCoin, SuperiorCoin and Ubiq.

### MultiAlgo

Block 145,000. September 1st 2014

Activated in September 2014 from Myriadcoin source code, this hard fork allowed for multi-algorithm mining. Its purpose was to create a number of different proof of work \(PoW\) mining methods to accommodate the different types of mining capabilities that exist, such as dedicated ASIC mining, GPU and CPU mining. This allows for a larger number of people to access DigiByte mining pools and therefore it creates a more decentralized blockchain with the coins reaching groups who were unable to mine the coin on its original single-algorithm \(Scrypt\).

### MultiShield

Block 400,000. December 10th 2014

Activated in December 2014, this hard fork worked to activate DigiShield across the new MultiAlgo platform and accomplish the same goals on all five mining pools.

### DigiSpeed

Block 1,430,000 December. 4th 2015

Activated in December 2015 this was a hard fork that focused on making the [DigiByte coin Transaction speeds faster](https://bitcointalk.org/index.php?topic=408268.msg13062879#msg13062879). Block time was reduced by 50% to 15 seconds and new block propagation code was added based on [Microsoft Research](http://www.dgbwiki.com/wikifiles/P2P2013_041-DigiSpeed_Research.pdf).

### Odocrypt

Block 9,112,320 July. 21th 2019

Activated in July 2019 this hard fork brought[Odocrypt](https://odocrypt.digibyteservers.io/)to life whichis a unique FPGA-friendly hashing algorithm made specifically for DigiByte that changes itself every 10 days as an anti-ASIC method. This replaced the Myr-groestl algorithm with Odocrypt. Odocrypt uses the Keccak algorithm \(SHA3\) for its hashing function, as it is a relatively streamlined and low-memory requirements \(Perfect for all common FPGAs\). It changes the hashing details every epoch \(10 day time-period\) based on the new seed. This change occurs at midnight UTC. When the epoch changes, the miners must compile a new .sof file \(analog of a binary executable for the FPGA CPU\) and program it on to the hardware. During this time, there is a 2-hour period prior to the midnight of the epoch in which the blockchain will accept the new epoch settings and / or the old epoch settings. This gives all miners a chance to re-optimize their settings and reprogram their FPGA's, without causing immediate issues in the overall hashrate for the algorithm, despite automated re-programming's taking only a matter of seconds in most instances. Once reprogrammed the FPGA uses the new seed as its base, which is required in order to maintain the 'optimized' settings. Without this, the FPGA will be churning out invalid hashes and have an effective efficiency of zero.

[Blog post from Jared Tate \(founder of DigiByte\) regardingDigiByte v7.17.2 Odocrypt Algo Fork](https://blockchain2035.com/blogs/digiassetsprotocol/digibyte-v7-17-2-odocrypt-algo-fork)

## Soft Forks

### DigiSync \(SegWit\)

In April 2017 DigiByte became the first major cryptocurrency blockchain \([in the Top 100 of CoinMarketCap](https://medium.com/@josiah_digibyte/clarifying-segwit-adoption-5770b461a860)\) to implement Segregated Witness \([SegWit](https://en.wikipedia.org/wiki/SegWit)\) via the DigiSync soft fork. The technical milestone laid the foundation for cross chain transactions and atomic swaps, while also resolving the transaction malleability bug that affected all UTXO blockchains.

### CSV

Also part of the BIP68/112/113 soft fork was the [CheckSequenceVerify](https://en.bitcoin.it/wiki/CheckSequenceVerify) opcode,which provides for relative locktime the same feature CLTV \(CheckLockTimeVerify\) provides for absolute locktime. When the CSV opcode is called, it will cause the script to fail unless the nSequence on the transaction indicates an equal or greater amount of relative locktime has passed than the parameter provided to the CSV opcode. Since an input may only be included in a valid block if its relative locktime is expired, this ensures the CSV-based timelock has expired before the transaction may be included in a valid block.

[Source](https://en.bitcoin.it/wiki/Timelock)

### NVersionBits

There are a variety of things that miners may desire to use some of the nVersion field bits for. However, due to their use to coordinate miner activated soft-forks, full node software will generate false warnings about unknown soft forks if those bits are used for non soft fork signalling purposes. By reserving bits from the nVersion field for general use, node software can be updated to ignore those bits and therefore will not emit false warnings. Reserving 16 bits for general use leaves enough for 13 parallel soft-forks using version bits.

## Innovations

### Digi-ID

In May 2018 [Digi-ID](https://www.digi-id.io/) framework was introduced. Digi-ID is an open protocol that allows for fast, simple and yet incredibly secure authentication based on the DigiByte Blockchain. Digi-ID utilizes public key cryptography much in the same way keyless SSH access works, just with a user-friendly wrapper around it.

### DigiAssets

In May 2019 [DigiAssets](https://www.dgbwiki.com/index.php?title=DigiAssets) platform wasintroduced.DigiAssets is a secure, scalable secondary layer on top of the global DigiByte blockchain that allows for the decentralized issuance of assets, tokens, smart contracts, digital identity and much more. DigiAssets can be used to securely and cryptographically represent anything we find in the real world. From real-world assets such as real estate, airplanes, boats and cars to scarce digital pieces of art and music. Signed documents such as wills, deeds, and purchase orders to medical bills and advertisement data and info can be protected as DigiAssets.

### Dandelion

In May 2019 Dandelion was implemented and released in to DigiByte Core 7.17.2 making DigiByte the first major UTXO blockchain to implement it \(After Grin, Beam & ZCoin\). Dandelion is a privacy-enhancement for the DigiByte blockchain that aids in obfuscating the senders IP address.

